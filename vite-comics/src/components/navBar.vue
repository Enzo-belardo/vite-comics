<script>
export default{
    data(){
        return{
            links:[

                {
                    link: 'CHARACTERS',
                    active: false,
                },
                {
                    link: 'COMICS',
                    active: true,
                },
                {
                    link: 'MOVIES',
                    active: false,
                },
                {
                    link: 'TV',
                    active: false,
                },
                {
                    link: 'GAMES',
                    active: false,
                },
                {
                    link: 'COLLECTIBILIES',
                    active: false,
                },
                {
                    link: 'VIDEOS',
                    active: false,
                },
                {
                    link: 'FANS',
                    active: false,
                },
                {
                    link: 'NEWS',
                    active: false,
                },
                {
                    link: 'SHOP',
                    active: false,
                },        
            ],
        }
    }

}

</script>

<template>
    <header>
        <nav>
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <div class="list-nav">
                <ul>
                    <li v-for="element in links" :class="{ 'active': element.active }">
                        {{ element.link }}
                    </li>
                </ul>
            </div>
        </nav>  
    </header>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;
header{
    color: $main-color;
}
 nav{
    display: flex;
    width: 80%;
    margin: auto;
    justify-content: space-between;
    align-items: center;
    color: $nav-color;
}
.logo img{
    width: 50%;
    margin-top: .5rem;
}

ul{
    display: flex;
    li{
        padding: .3rem;
        list-style-type: none;
        cursor: pointer;
        &.active,
        &:hover{
           color: $dc-color;
           border-bottom: solid 2px $dc-color;  
        }
    }
 }

</style>
