<template>
  <header class="header">
    <div class="header-top">
      <a href="tel:9998989373788">
        <img
          src="https://uploads-ssl.webflow.com/63e857eaeaf853471d5335ff/63e884fbeaf853f075555d17_Call.svg"
          alt="call"
        />
        <span>+9998989373788</span>
      </a>
      <p class="header-top-text">
        Get 50% Off on Selected Items | Shop Now <i class="flag flag-us"></i>
      </p>
      <div class="header-select">
        <select name="" id="">
          <option value="">En</option>
          <option value="">Ru</option>
          <option value="">Uz</option>
        </select>
        <select name="" id="">
          <option value="" selected>Location</option>
          <option value="">Uzbekistan</option>
          <option value="">Russian</option>
          <option value="">USA</option>
        </select>
      </div>
    </div>
    <div class="header-bottom">
      <router-link to="/"
        ><img
          src="https://uploads-ssl.webflow.com/63e857eaeaf853471d5335ff/63e86ab4c21faa7bc0bd90dd_Logo.svg"
          alt="logo"
          class="header-logo"
      /></router-link>
      <ul class="header-menu">
        <li>
          <router-link to="/">Home</router-link>
        </li>
        <li>
          <a href="#category">Category</a>
        </li>
        <li>
          <router-link to="/">About</router-link>
        </li>
        <li>
          <router-link to="/show">Blog</router-link>
        </li>
      </ul>

      <label for="">
        <input type="text" placeholder="Search..." />
        <button>
          <img src="../../assets/images/search.gif" alt="" />
        </button>
      </label>

      <div class="d-center">
        <a href="/create-product" class="acount">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="25"
            height="25"
            fill="currentColor"
            class="bi bi-person"
            viewBox="0 0 16 16"
          >
            <path
              d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6Zm2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0Zm4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4Zm-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h10Z"
            /></svg
          ><span>Acount</span>
        </a>
        <a href="/cart" class="acount">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="22"
            height="22"
            fill="currentColor"
            class="bi bi-bag"
            viewBox="0 0 16 16"
          >
            <path
              d="M8 1a2.5 2.5 0 0 1 2.5 2.5V4h-5v-.5A2.5 2.5 0 0 1 8 1zm3.5 3v-.5a3.5 3.5 0 1 0-7 0V4H1v10a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V4h-3.5zM2 5h12v9a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5z"
            />
          </svg>
          <span>Cart</span>
        </a>
      </div>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style lang="scss">
.header-top {
  padding: 7px 30px;
  background-color: #003d29;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #fff;
  font-size: 12px;
  line-height: 140%;
  a {
    color: #fff;
    text-decoration: none;
    display: flex;
    justify-content: flex-start;
    align-items: center;
    gap: 15px;
  }
  &-text {
    margin-left: auto;
  }
}
.header {
  &-bottom {
    padding: 15px 30px;
    display: flex;
    justify-content: center;
    align-items: center;
    label {
      width: 350px;
      height: 40px;
      display: flex;
      justify-content: center;
      align-items: center;
      border: 1px solid #525151;
      border-radius: 25px;
      padding: 0 10px;
      margin-left: auto;
      input {
        width: 80%;
        height: 80%;
        border: unset;
        outline: unset;
        font-size: 16px;
      }
      button {
        cursor: pointer;
        width: 20%;
        height: 100%;
        border: unset;
        outline: unset;
        background: unset;
        img {
          width: 40%;
          height: 70%;
        }
      }
    }
  }
  &-menu {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-left: auto;
    gap: 40px;
    li {
      list-style-type: none;
      a {
        color: #003d29;
        text-decoration: none;
        font-weight: 700;
      }
    }
  }
  &-select {
    margin-left: auto;
    select {
      background: unset;
      color: #fff;
      border: unset;
      outline: unset;
      &:last-child {
        margin-left: 50px;
      }
      option {
        color: #003d29;
      }
    }
  }
}

.acount {
  border: none;
  background: none;
  outline: none;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 15px;
  margin-left: 40px;
  cursor: pointer;
  font-size: 16px;
  color: #000;
  text-decoration: none;
  a {
    color: #000;
    text-decoration: none;
  }
}
</style>