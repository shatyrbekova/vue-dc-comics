<template>
    <section class="icons-container">
        <ul>
            <li>
                <img src="../assets/buy-comics-digital-comics.png" alt="">
                <a href="#">DIGITAL COMICS</a>
            </li>
            <li>
                <img src="../assets/buy-comics-merchandise.png" alt="">
                <a href="#">DC MERCHANDISE</a>
            </li>
            <li>
                <img src="../assets/buy-comics-subscriptions.png" alt="">
                <a href="#">SUBSCRIPTION</a>
            </li>
            <li>
                <img src="../assets/buy-comics-shop-locator.png" alt="">
                <a href="#">COMIC SHOP LOCATOR</a>
            </li>
            <li>
               <img src="../assets/buy-dc-power-visa.svg" alt="">
                <a href="#">DC POWER VISA</a>
            </li>
           
        </ul>
    </section>
</template>

<script>
export default {
    name: 'SectionIcons'
}
</script>

<style lang="scss" scoped>
    .icons-container{
       background-color: rgb(58, 138, 212);
       color:white;
    //    display:flex;
    
       ul{
           list-style: none;
           display:flex;
           width:1400px;
           margin: 0 auto;;
           li{
             margin: 0 10px;
             padding: 30px;
             font-size: 12px;
             display: flex;
             align-items: center;
             a{
                 text-decoration:none;
                 color:white;
                 margin-left:15px;
             }
             img{
                 width:25%;
             }
           }
       }
    }
</style>