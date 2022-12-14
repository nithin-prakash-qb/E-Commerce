<script setup></script>

<template>
  <section id="categories">
    <div id="furniture"></div>
    <div id="mobile"></div>
    <div id="grocery"></div>
    <div id="medicine"></div>
    <div id="fashion"></div>
  </section>
</template>

<style scoped>
#categories{
    display: flex;
    justify-content: space-evenly;
    padding: 20px 20px;
    background-color: #f5e1da;
}
#furniture {
  height: 150px;
  width: 150px;
  background: url("public/Images/furniture.jpeg") center no-repeat;
  background-size: cover;
}
#mobile {
  height: 150px;
  width: 150px;
  background: url("public/Images/mobile.jpg") center no-repeat;
  background-size: cover;
}
#grocery {
  height: 150px;
  width: 150px;
  background: url("public/Images/grocery.jpg") center no-repeat;
  background-size: cover;
}
#medicine {
  height: 150px;
  width: 150px;
  background: url("public/Images/medicine.jpg") center no-repeat;
  background-size: cover;
}
#fashion {
  height: 150px;
  width: 150px;
  background: url("public/Images/Fashion.jpg") center no-repeat;
  background-size: cover;
}
</style>
