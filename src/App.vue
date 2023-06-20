<template>
  <HeaderItem />
  <router-view />
  <FooterItem />
</template>

<script>
import FooterItem from "./components/layout/FooterItem.vue";
import HeaderItem from "./components/layout/HeaderItem.vue";
export default {
  components: { HeaderItem, FooterItem },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Manrope:wght@400;500;600;700;800&display=swap");
</style>
<style lang="scss">
html {
  scroll-behavior: smooth;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Inter", sans-serif;
}
.container {
  max-width: 1270px;
  margin: 0 auto;
}
.d-center {
  display: flex;
  justify-content: center;
  align-items: center;
}
ul li {
  list-style: none;
}
.row {
  display: flex;
  flex-wrap: wrap;
  padding: 0 -15px;
}
.d-flex {
  display: flex;
}

.col-2 {
  width: 16.66%;
}
.col-7 {
  width: 58.33%;
}
.col-3 {
  width: 25%;
  padding: 10px;
}
.col-4 {
  width: 33.33%;
  padding: 10px;
}
.col-8 {
  width: 66.66%;
}
.col-6 {
  width: 50%;
}

.mt-50 {
  margin-top: 50px;
}
.mb-70 {
  margin-bottom: 70px;
}
.mb-50 {
  margin-bottom: 50px;
}
.mt-70 {
  margin-top: 70px;
}
.mt-a {
  margin-top: auto;
}
</style>
