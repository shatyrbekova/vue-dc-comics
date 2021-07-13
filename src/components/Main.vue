<template>
  <main>
    <div class="container">
      <div class="row">
        <Card
          v-for="(element, index) in comics"
          :key="index"
          :thumb="element.thumb"
          :price="element.price"
          :title="element.series"
          :type="element.type"
        />
      </div>
    </div>
  </main>
</template>

<script>
import Card from './Card.vue';

export default {
  name: 'Main',
  components: {
    Card,
  },
  props: {
    comics: Array,
  },
  created() {
    console.log(this.comics);
  },
};
</script>

<style scoped lang="scss">
@import '../style/colors';

main {
  background-color: black;
  color: white;
  
}
</style>
