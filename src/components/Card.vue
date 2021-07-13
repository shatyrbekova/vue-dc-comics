<template>
  <div class="product-card col-2 px-15">
    <div
      class="img-container"
      :style="{ backgroundImage: 'url(' + thumb + ')' }"
    ></div>
    <h3>{{ title }}</h3>
    <h4>{{ price }}</h4>
    <h4>{{ type }}</h4>
  </div>
</template>

<script>
export default {
  name: 'Card',
  props: {
    thumb: String,
    price: String,
    title: String,
    type: String,
  },
};
</script>

<style scoped lang="scss">
@import '../style/colors';
</style>
