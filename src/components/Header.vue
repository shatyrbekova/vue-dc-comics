<template>
    <header class="header-container">
        <ul>
           <li>
              <img src="../assets/dc-logo.png" alt="">
           </li>
            
         </ul>
         <ul class="menu-list">

           <li v-for="element in menuList" :key="element.id" >
                <a :href="element.link">{{element.name}}</a>
           </li>
      
         </ul>
    </header>
</template>

<script>
export default {
  name: "Header",
  props:{
      menuList: Array,
  }
};
</script>



<style lang="scss" scoped>
.menu-list {
  display: flex;
}
.header-container {
  display: flex;
  justify-content: space-around;
  align-items: center;
  margin-top: 60px;
  margin-bottom: 30px;
  background-color: white;


  li {
    font-size: 14px;
    margin: 0 15px;
    font-weight: bold;
    a {
      color: black;
      font-family: "Roboto Condensed", sans-serif;
      font-weight: bold;
     
      &:hover {
        color: #0c7cec;;
        border-bottom: 5px solid #0c7cec;;
      }
    }
  }
}
</style>