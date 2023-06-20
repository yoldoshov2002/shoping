<template>
  <div class="home">
    <img
      class="home-img"
      src="https://img.freepik.com/free-photo/black-friday-elements-assortment_23-2149074076.jpg"
      alt=""
    />
    <div class="home-box">
      <div class="home-box-title">Shopping And Department Store.</div>
      <div class="home-box-text">
        Shopping is a bit of a relaxing hobby for me, which is sometimes
        troubling for the bank balance.
      </div>
      <a href="/"> Learn More</a>
    </div>
    <div class="container">
      <CategoryItem />
      <ProductBox />
      <BrandBox />
      <ProductBox />
    </div>
    <div class="relative">
      <img
        class="home-img mt-50"
        src="https://t4.ftcdn.net/jpg/02/32/16/07/360_F_232160763_FuTBWDd981tvYEJFXpFZtolm8l4ct0Nz.jpg"
        alt=""
      />
      <div class="home-box">
        <div class="home-box-title">Shopping And Department Store.</div>
        <div class="home-box-text">
          Shopping is a bit of a relaxing hobby for me, which is sometimes
          troubling for the bank balance.
        </div>
        <a href="/"> Learn More</a>
      </div>
    </div>
    <div class="container">
      <ProductMini />
    </div>
  </div>
</template>

<script>
import CategoryItem from "@/components/home-comp/CategoryItem.vue";
import ProductBox from "@/components/home-comp/ProductBox.vue";
import BrandBox from "@/components/home-comp/BrandBox.vue";
import ProductMini from "@/components/home-comp/ProductMini.vue";
export default {
  name: "HomeView",
  components: { CategoryItem, ProductBox, BrandBox, ProductMini },
};
</script>



<style lang="scss">
.relative {
  position: relative;
}
.home {
  position: relative;
  &-img {
    width: 100%;
    height: 600px;
  }
  &-box {
    position: absolute;
    top: 140px;
    left: 100px;
    z-index: 2;
    width: 600px;
    a {
      font-family: Eina01, sans-serif;
      color: #fff;
      font-size: 18px;
      line-height: 24px;
      font-weight: 600;
      text-decoration: none;
      background: #003d29;
      padding: 15px 30px;
      border-radius: 20px;
    }
    &-title {
      color: #003d29;
      text-transform: capitalize;
      margin-top: 0px;
      font-family: Eina02, sans-serif;
      font-size: 64px;
      line-height: 74px;
      font-weight: 700;
    }
    &-text {
      width: 500px;
      max-width: 495px;
      margin-bottom: 40px;
      -webkit-box-align: start;
      font-family: Inter, sans-serif;
      color: #231f1e;
      font-size: 20px;
      line-height: 145%;
    }
  }
}
</style>