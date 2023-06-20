<template>
  <div class="category" id="category">
    <h2>Shop Our Top Categories</h2>
    <div class="row">
      <div class="col-2">
        <div class="category-box">
          <img
            src="https://uploads-ssl.webflow.com/63e857eaeaf853471d5335ff/63e8c4e570738029a725e686_Furniture-min.png"
            alt=""
          />
          <span>Furniture</span>
        </div>
      </div>
      <div class="col-2">
        <div class="category-box">
          <img
            src="https://uploads-ssl.webflow.com/63e857eaeaf853471d5335ff/63e8c4e52d6553668075697e_hand%20bag-min.png"
            alt=""
          />
          <span>Hand Bag</span>
        </div>
      </div>
      <div class="col-2">
        <div class="category-box">
          <img
            src="https://uploads-ssl.webflow.com/63e857eaeaf853471d5335ff/63e8c4e460afc22b7ea53520_books-min.png"
            alt=""
          />
          <span>Books</span>
        </div>
      </div>
      <div class="col-2">
        <div class="category-box">
          <img
            src="https://uploads-ssl.webflow.com/63e857eaeaf853471d5335ff/63e8c4e754ac2e32897cb53b_tech-min.png"
            alt=""
          />
          <span>Tech</span>
        </div>
      </div>
      <div class="col-2">
        <div class="category-box">
          <img
            src="https://uploads-ssl.webflow.com/63e857eaeaf853471d5335ff/63e8c4e64b769118272f244f_sneakers-min.png"
            alt=""
          />
          <span>Sneakers</span>
        </div>
      </div>
      <div class="col-2">
        <div class="category-box">
          <img
            src="https://uploads-ssl.webflow.com/63e857eaeaf853471d5335ff/63e8c4e71eb4ad6d07e7568f_travel-min.png"
            alt=""
          />
          <span>Travel</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.category {
  .row {
    margin-left: -10px;
    margin-right: -10px;
    .col-2 {
      padding: 10px;
    }
  }
  h2 {
    margin: 20px 0;
    margin-top: 50px;
  }
  &-box {
    position: relative;
    display: flex;
    justify-content: center;
    border-radius: 10px;
    min-height: 241px;
    width: 100%;
    border-radius: 10px;
    overflow: hidden;
    &:hover {
      img {
        transform: scale(1.05);
        transition: transform 0.5;
      }
    }
    span {
      position: absolute;
      top: 20px;
      left: auto;
      background-repeat: no-repeat;
      z-index: 1;
      width: 100%;
      color: #fff;
      font-size: 24px;
      font-weight: 600;
      text-align: center;
    }
    img {
      object-fit: cover;
      background-size: cover;
      width: 100%;
      min-height: 241px;
      cursor: pointer;
    }
  }
}
</style>