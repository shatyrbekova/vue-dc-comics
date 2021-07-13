<template>
  <section>
    <div class="container">
      <div class="col">
        <img src="../assets/buy-comics-digital-comics.png" alt="" />
        <span>DIGITAL COMICS</span>
      </div>
      <div class="col">
        <img src="../assets/buy-comics-merchandise.png" alt="" />
        <span>DC MECHANDISE</span>
      </div>
      <div class="col">
        <img src="../assets/buy-comics-subscriptions.png" alt="" />
        <span>SUBSCRIPTION</span>
      </div>
      <div class="col">
        <img src="../assets/buy-comics-shop-locator.png" alt="" />
        <span>COMIC SHOP LOCATOR</span>
      </div>
      <div class="col">
        <img src="../assets/buy-dc-power-visa.svg" alt="" />
        <span>CD POWER VISA</span>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "SectionBlu",
};
</script>


<style scoped lang="scss">
@import "../style/colors";

section {
  background-color: #0c7cec;;
  padding: 30px 0;
}
.container {
  display: flex;
  align-items: text-bottom;

  .col {
    width: calc(100% / 5);
    text-align: center;
    height: 60px;
    vertical-align: center;

    img {
      height: 50px;
      vertical-align: middle;
    }

    span {
      color: white;
      font-family: "Roboto Condensed", sans-serif;
      line-height: 60px;
    }
  }
}
</style>