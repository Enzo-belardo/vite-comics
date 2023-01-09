<script>
export default{

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
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                </ul>
            </div>
        </nav>  
    </header>
</template>

<style lang="scss" scoped>
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
    }
 }

</style>
