<script>
export default{

}

</script>

<template>
    <footer>
        <div class="container-top-foot">
            <nav>
               <ul>
                 <h4>DC Comics</h4>
                 <li>characters</li>
                 <li>comics</li>
                 <li>movies</li>
                 <li>tv</li>
                 <li>games</li>
                 <li>videos</li>
                 <li>news</li>   
               </ul>

               <ul>
                 <h4>DC</h4>
                 <li>terms of use</li>
                 <li>privacy policy (new)</li>
                 <li>ad choise</li>
                 <li>advertising</li>
                 <li>jobs</li>
                 <li>subscriptions</li>
                 <li>talent workshop</li>
                 <li>cpsc certificates</li>
                 <li>ratings</li>
                 <li>contacts us</li>
               </ul>

               <ul>
                 <h4>SITES</h4>
                 <li>dc</li>
                 <li>mad magazine</li>
                 <li>dc kids</li>
                 <li>dc universe</li>
                 <li>dc power visa</li>
               </ul>

               <ul>
                  <h4>SHOP</h4>
                  <li>shop dc</li>
                  <li>shop dc collectibles</li>
               </ul>
            </nav>
            <div class="image">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
        <div class="container-down-foot">
            <div>
                <div>
                    <button>SIGN UP NOW!</button>
                </div>
                <div class="icon">
                    <h3>FOLLOW US</h3>
                </div>
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
footer{
    background-image: url(../assets/img/footer-bg.jpg);
}
.container-top-foot{
    width: 80%;
    margin: auto;
    display: flex;
    justify-content: space-between;
}
.container-down-foot{
    background-color: black;
    div{
        width: 80%;
        margin: auto;
        display: flex;
        justify-content: space-between;
        padding: .5rem 0;
        button{
            border: solid 1px blue;
            padding: 0.5rem 1rem;
            background-color: transparent;
            color: white;
        }
        .icon{
            color: white;
        }
    }
}
nav{
    width: 40%;
    display: flex;
    flex-wrap: wrap;
    color: white;
}
ul{
    list-style-type: none;
    li{
        padding: 0;
    }
}

.image {
    width: 40%;   
    img{
        width: 90% ;
    }
}

</style>
