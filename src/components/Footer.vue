<template>
    <footer class="footer-container">
        <div class="menu-footer">
           <div class="list-menu">
               <div>
                   <ul>
                       <li>
                           <h4>DC COMICS</h4>
                       </li>
                         <li><a href="#">Characters</a></li>
                         <li><a href="#">Comics</a></li>
                         <li><a href="#">Movies</a></li>
                         <li><a href="#">TV</a></li>
                         <li><a href="#">Games</a></li>
                         <li><a href="#">Viedos</a></li>
                         <li><a href="#">News</a></li>
                        
                   </ul>
                   <ul>
                       <li>
                           <h4>SHOP</h4>
                       </li>
                       <li><a href="#">Shop DC</a></li>
                       <li><a href="#">Shop DC Collections</a></li>
                   </ul>
               </div>
               <div>
                   <ul>
                       <li>
                           <h4>DC</h4>
                       </li>
                       <li><a href="#">Terms Of Use</a></li>
                       <li><a href="#">Privacy policy (New)</a></li>
                       <li><a href="#">Ad Choices</a></li>
                       <li><a href="#">Advertising</a></li>
                       <li><a href="#">Jobs</a></li>
                       <li><a href="#">Subscriptions</a></li>
                       <li><a href="#">Talent</a></li>
                       <li><a href="#">CPSC Certicates</a></li>
                       <li><a href="#">Ratings</a></li>
                       <li><a href="#">Shop Help</a></li>
                       <li><a href="#">Contacts Us</a></li>
                   </ul>
                   
               </div>
               <div>
                   <ul>
                       <li><h4>SITES</h4></li>
                       <li><a href="#">DC</a></li>
                       <li><a href="#">MAD Magazine</a></li>
                       <li><a href="#">DC Kids</a></li>
                       <li><a href="#">DC Universe</a></li>
                       <li><a href="#">DC Power Visa</a></li>
                   </ul>
               </div>
           </div>
        </div>
        <div class="logo-footer">
          <img src="../assets/dc-logo-bg.png" alt="">
        </div>
    </footer>
</template>


<script>
export default {
    name: 'Footer'
}
</script>

<style lang="scss" scoped>
    .footer-container{
       background: url("../assets/footer-bg.jpg");
       height: 400px;
       display:flex;
       justify-content:space-around;

       .logo-footer img{
          width:80%
       }
       .list-menu{
           display: flex;

           ul{
               list-style:none;
                color:white;
               a{
                 text-decoration: none;
                 color:grey;
               }
           }
       }
    }
</style>