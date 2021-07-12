<template>
    <header class="header-container">
        <ul>
           <li>
              <img src="../assets/dc-logo.png" alt="">
           </li>
            
         </ul>
         <ul class="menu-list">
           <li><a href="#">CHARACTERS</a></li>
           <li><a href="#">COMICS</a></li>
           <li><a href="#">MOVIES</a></li>
           <li><a href="#">TV</a></li>
           <li><a href="#">GAMES</a></li>
           <li><a href="#">COLLECTIBLES</a></li>
           <li><a href="#">VIEDOS</a></li>
           <li><a href="#">FANS</a></li>
           <li><a href="#">NEWS</a></li>
           <li><a href="#">SHOP</a></li>
      
         </ul>
    </header>
</template>

<script>
export default {
    name: 'Header'
}
</script>



<style lang="scss" scoped>
    .menu-list{
        display: flex;
        
    }
    .header-container{
        display:flex;
        justify-content: space-around;
        align-items: center;
        // height:90px;
        margin-top: 60px;
        background-color: white;
        ul{
            list-style:none;
            li{
                font-size: 14px;
                margin: 0 15px;
                font-weight:bold;
                a{
                    text-decoration: none;
                    color: black;
                }
            }
        }
    }
</style>