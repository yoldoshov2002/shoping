<template>
  <div class="cart container">
    <h2 class="text-center">Sizning savatingizdagi mahsulotlar</h2>
    <div class="row">
      <div class="col-12">
        <div class="cart-box mt-50 mb-50">
          <img
            src="https://cdn.shopclues.com/images1/thumbnails/116250/320/320/153050056-116250401-1649837829.jpg"
            alt=""
          />

          <h4>PAUSE Cotton Yellow Solid</h4>
          <div class="">
            <h5>Narxi:</h5>
            <p class="nowrap">300 000 sum</p>
          </div>
          <p class="w-50">
            <strong>Haqida: </strong>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit
            quod eos qui, id labore error repellendus quidem culpa. Dolorem
            fugit alias, illum laborum officiis perferendis dignissimos sed rem
            quod error.
          </p>
          <a href="/" class="cart-button nowrap"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              width="25"
              height="25"
              fill="currentColor"
              class="bi bi-x-lg"
              viewBox="0 0 16 16"
            >
              <path
                d="M2.146 2.854a.5.5 0 1 1 .708-.708L8 7.293l5.146-5.147a.5.5 0 0 1 .708.708L8.707 8l5.147 5.146a.5.5 0 0 1-.708.708L8 8.707l-5.146 5.147a.5.5 0 0 1-.708-.708L7.293 8 2.146 2.854Z"
              /></svg
          ></a>
        </div>
        <div class="cart-box mt-50 mb-50">
          <img
            src="https://cdn.shopclues.com/images1/thumbnails/116250/320/320/153050056-116250401-1649837829.jpg"
            alt=""
          />

          <h4>PAUSE Cotton Yellow Solid</h4>
          <div class="">
            <h5>Narxi:</h5>
            <p class="nowrap">300 000 sum</p>
          </div>
          <p class="w-50">
            <strong>Haqida: </strong>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit
            quod eos qui, id labore error repellendus quidem culpa. Dolorem
            fugit alias, illum laborum officiis perferendis dignissimos sed rem
            quod error.
          </p>
          <a href="/" class="cart-button nowrap"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              width="25"
              height="25"
              fill="currentColor"
              class="bi bi-x-lg"
              viewBox="0 0 16 16"
            >
              <path
                d="M2.146 2.854a.5.5 0 1 1 .708-.708L8 7.293l5.146-5.147a.5.5 0 0 1 .708.708L8.707 8l5.147 5.146a.5.5 0 0 1-.708.708L8 8.707l-5.146 5.147a.5.5 0 0 1-.708-.708L7.293 8 2.146 2.854Z"
              /></svg
          ></a>
        </div>

        <div class="d-center">
          <h4>Ummumiy Narx: <small>1 000 000 sum</small></h4>
          <a href="/" class="cart-button nowrap ms-auto"> Buyurtma berish </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.cart {
  margin-top: 70px;
  &-box {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 15px;
    background: #f5f5f5;
    padding: 15px;
    border-radius: 10px;
    img {
      width: 200px;
      height: 150px;
      background-repeat: no-repeat;
      object-fit: contain;
      background-size: contain;
    }
  }
}
.nowrap {
  white-space: nowrap;
  margin-top: 0;
}
</style>