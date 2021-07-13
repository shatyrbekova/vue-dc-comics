<template>
    <div class="social-media-container">
       <div>
           <button>SIGN-UP NOW!</button>
       </div>
       <div>
           <ul>
               <li>FOLLOW US</li>
               <li>
                     <img src="../assets/footer-twitter.png" alt="">
               </li>
               <li>
                   <img src="../assets/footer-facebook.png" alt="">
               </li>
               <li>
                   <img src="../assets/footer-youtube.png" alt="">
               </li>
               <li>
                   <img src="../assets/footer-pinterest.png" alt="">
               </li>
               <li>
                   <img src="../assets/footer-periscope.png" alt="">
               </li>
           </ul>
       </div>
    </div>
</template>

<script>
export default {
    name: 'FooterSocialMedia'
}
</script>


<style lang="scss" scoped>
  .social-media-container{
      display:flex;
      justify-content: space-around;
      background: rgb(27, 27, 27);
      align-items:center;
       button{
           border: 1px solid rgb(52, 88, 245);
           height:40px;
           background:  rgb(27, 27, 27);
           color:white;
           
       }
       ul{
        display:flex;
        list-style:none;
        align-items:center;
        color:rgb(52, 88, 245);
        font-weight:bold;
        li{
            margin: 0 10px;
        }

    }
  }
   
    
</style>
