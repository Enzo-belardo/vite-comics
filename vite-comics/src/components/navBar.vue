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
                    <li v-for="element in links" :class="(element.active) ? 'active' : ''">
                        {{ element.link }}
                    </li>
                </ul>
            </div>
        </nav>  
    </header>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;
 nav{
    display: flex;
    width: 80%;
    margin: auto;
    justify-content: space-between;
 }
 .logo img{
    width: 50%;
    margin-top: .5rem;
 }

 ul{
    display: flex;
    li{
        list-style-type: none;
        padding: .5rem;
        cursor: pointer;
        &.active,
        &:hover{
           color: blue;
           border-bottom: solid 2px $dc-color;
        }
    }
 }

</style>
