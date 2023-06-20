<template>
  <footer class="footer container">
    <div class="row">
      <div class="col-4">
        <div class="footer-box">
          <img
            src="https://uploads-ssl.webflow.com/63e857eaeaf853471d5335ff/63e86ab4c21faa7bc0bd90dd_Logo.svg"
            alt="logo"
            class="footer-logo"
          />
          <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ipsa
            molestiae quis expedita eum pariatur maxime reprehenderit labore
            aperiam sed praesentium dolore totam ducimus provident asperiores
            beatae eius exercitationem, nihil illum?
          </p>

          <h2>Accepted Payments</h2>

          <div class="row">
            <div class="payment-icon">
              <a href="/"
                ><img
                  src="https://uploads-ssl.webflow.com/63e857eaeaf853471d5335ff/63eb1ce8816711ebecac46d8_stripe.png"
                  loading="lazy"
                  alt=""
              /></a>
            </div>
            <div class="payment-icon">
              <a href="/"
                ><img
                  src="https://uploads-ssl.webflow.com/63e857eaeaf853471d5335ff/63eb1ce82d440b7ab84a993f_visa.png"
                  loading="lazy"
                  alt=""
              /></a>
            </div>
            <div class="payment-icon">
              <a href="/">
                <img
                  src="https://uploads-ssl.webflow.com/63e857eaeaf853471d5335ff/63eb1ce8f032504012a5896b_Mastercard.png"
                  loading="lazy"
                  alt=""
                />
              </a>
            </div>
            <div class="payment-icon">
              <a href="/">
                <img
                  src="https://uploads-ssl.webflow.com/63e857eaeaf853471d5335ff/63e8c4e48b497e6ce846b7ff_Amazon.png"
                  loading="lazy"
                  alt=""
                />
              </a>
            </div>

            <div class="payment-icon">
              <a href="/"
                ><img
                  src="https://uploads-ssl.webflow.com/63e857eaeaf853471d5335ff/63eb1ce8816711ebecac46d8_stripe.png"
                  loading="lazy"
                  alt=""
              /></a>
            </div>
            <div class="payment-icon">
              <a href="/"
                ><img
                  src="https://uploads-ssl.webflow.com/63e857eaeaf853471d5335ff/63eb1ce82d440b7ab84a993f_visa.png"
                  loading="lazy"
                  alt=""
              /></a>
            </div>
            <div class="payment-icon">
              <a href="/">
                <img
                  src="https://uploads-ssl.webflow.com/63e857eaeaf853471d5335ff/63eb1ce8f032504012a5896b_Mastercard.png"
                  loading="lazy"
                  alt=""
                />
              </a>
            </div>
            <div class="payment-icon">
              <a href="/">
                <img
                  src="https://uploads-ssl.webflow.com/63e857eaeaf853471d5335ff/63e8c4e48b497e6ce846b7ff_Amazon.png"
                  loading="lazy"
                  alt=""
                />
              </a>
            </div>
          </div>
        </div>
      </div>
      <div class="col-8">
        <div class="row footer-right">
          <div class="col-4">
            <div class="footer-menu">
              <h3>Department</h3>
              <a href="/">Fashion</a>
              <a href="/">Education Product</a>
              <a href="/">Frozen Food</a>
              <a href="/">Beverages</a>
              <a href="/">Organic Grocery</a>
              <a href="/">Electronics & Gadget</a>
              <a href="/">Books</a>
              <a href="/">Beauty Products</a>
              <a href="/">Office Supplies</a>
              <a href="/">Travel Accessories</a>
              <a href="/">Fitness</a>
              <a href="/">Sneakers</a>
              <a href="/">Toys</a>
              <a href="/">Furniture</a>
            </div>
          </div>
          <div class="col-4">
            <div class="footer-menu">
              <h3>Page</h3>
              <a href="/">Home</a>
              <a href="/">Blog</a>
              <a href="/">About</a>
              <a href="/">Service</a>
              <a href="/">Contact</a>
            </div>
          </div>
          <div class="col-4">
            <div class="footer-menu">
              <h3>Contact</h3>
              <a href="/">389048324820</a>
              <a href="/">gmail@email.com</a>
              <a href="/">this my telegram link</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
  <div class="header-top">
    <p>Lorem ipsum dolor sit amet consectetur</p>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.footer {
  padding-top: 70px;
  padding-bottom: 50px;
  &-logo {
    margin-bottom: 30px;
  }
  &-right {
    margin-left: 150px;
    margin-top: 100px;
  }
  &-menu {
    display: flex;
    justify-content: flex-start;
    align-items: flex-start;
    flex-direction: column;
    h3 {
      margin-bottom: 20px;
    }
    a {
      color: #000;
      font-size: 16px;
      margin-bottom: 10px;
      text-decoration: none;
    }
  }
  h2 {
    margin-top: 30px;
    margin-bottom: 20px;
  }
  .payment-icon {
    width: 25%;
    margin-bottom: 20px;
    outline: 10px solid transparent;
    display: flex;
    justify-content: center;
    align-items: center;
    a {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 40px;
      border: 1px solid #003d29;
      border-radius: 8px;
    }

    img {
      padding: 10px 20px;
      cursor: pointer;
    }
  }
}
</style>