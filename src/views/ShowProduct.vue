<template>
  <div class="show container mt-70">
    <div class="row">
      <div class="col-6">
        <div class="show-img">
          <img
            src="https://cdn.shopclues.com/images1/thumbnails/116250/320/320/153050056-116250401-1649837829.jpg"
            alt=""
          />
        </div>
      </div>
      <div class="col-6">
        <div class="show-box">
          <h2>
            PAUSE Cotton Yellow Solid Round Slim Fit Short Sleeve Men's T-Shirt
            and shorts
          </h2>
          <div class="d-flex mt-5">
            <h4 class="text-success">Product Price:</h4>
            <p class="mb-70 ms-5">300 000 sum</p>
          </div>
          <a href="/" class="cart-button mt-5">Add to Cart</a>
        </div>
      </div>
      <div class="col-12">
        <h3 class="mt-50 mb-3">Description</h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic
          recusandae perferendis nostrum voluptatibus. Illum corporis neque
          dolor soluta quo quibusdam, illo ab iure, exercitationem, sunt maiores
          sequi facere placeat natus. Ducimus deserunt mollitia quisquam ullam
          sapiente aperiam numquam alias soluta in maiores iure totam corrupti
          animi, culpa non cumque labore voluptatum ipsa consequatur asperiores!
          Explicabo deserunt dolorem voluptatum aliquam quaerat? Placeat debitis
          laborum eius neque totam, quisquam provident vel odit ab, quos nobis!
          Illo error, iusto quibusdam quisquam id, sequi provident quaerat
          similique commodi voluptatem ipsam vel necessitatibus ipsum tempore?
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.show {
  &-img {
    width: 400px;
    height: 400px;
    overflow: hidden;
    border-radius: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
    &-box {
      display: flex;
      flex-direction: column;
    }
    img {
      width: 100%;
      height: 100%;
      background-repeat: no-repeat;
      object-fit: contain;
      background-size: contain;
    }
  }
}
</style>