<template>
  <div id="main-banner">
    <h1>Burger</h1>
  </div>
</template>

<script>
export default {
    name: "Banner"
}
</script>

<style scoped>
    #main-banner {
    background-image: url('/public/img/burger.jpg');
    background-position: 0 -100px;
    background-size: cover;
    height: 750px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
  }

  #main-banner h1 {
    color: #FFF;
    text-align: center;
    font-size: 60px;
    background-color: #222;
    padding: 20px 40px;
  }
</style>