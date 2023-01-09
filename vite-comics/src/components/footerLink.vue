<script>
export default{

}

</script>

<template>
    <footer>
        <div class="container-top-foot">
            <nav>
                <div>
                    <ul>
                      <h4>DC Comics</h4>
                      <li>Characters</li>
                      <li>Comics</li>
                      <li>Movies</li>
                      <li>TV</li>
                      <li>Games</li>
                      <li>Videos</li>
                      <li>News</li>   
                    </ul>
                    
                    <ul>
                       <h4>SHOP</h4>
                       <li>Shop DC</li>
                       <li>Shop DC collectibles</li>
                    </ul>
                </div>

               <ul>
                 <h4>DC</h4>
                 <li>Terms of use</li>
                 <li>Privacy policy (new)</li>
                 <li>Ad choise</li>
                 <li>Advertising</li>
                 <li>Jobs</li>
                 <li>Subscriptions</li>
                 <li>Talent workshop</li>
                 <li>CPSC Certificates</li>
                 <li>Ratings</li>
                 <li>Contacts Us</li>
               </ul>

               <ul>
                 <h4>SITES</h4>
                 <li>DC</li>
                 <li>Mad magazine</li>
                 <li>DC kids</li>
                 <li>DC universe</li>
                 <li>DC power visa</li>
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
                    <i class="fa-brands fa-facebook"></i>
                    <i class="fa-brands fa-twitter"></i>
                    <i class="fa-brands fa-youtube"></i>
                    <i class="fa-brands fa-pinterest-p"></i>
                </div>
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

footer{
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
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
        div button{
            border: solid 1px $dc-color;
            padding: 0.5rem 1rem;
            background-color: transparent;
            color: $main-color;
        }
        .icon{
            color: $main-color;
            display: flex;
            justify-content: space-around;
            align-items: center;
            h3{
                color: $dc-color;
            }
            i{
                border-radius: 100%;
                background-color: $link-color;
                padding: 1rem;
                
            }
        }
    }
}
nav{
    width: 45%;
    display: flex;
    flex-wrap: wrap;
}
ul{
    list-style-type: none;
    padding-left: 0;
    padding-right: 1rem;
    h4{
        color: $main-color;
    }
    li{
        color: $link-color;
    }
}

.image {
    width: 35%;   
    img{
        width: 100% ;
    }
}

</style>
