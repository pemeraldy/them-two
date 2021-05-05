<template>
  <section class="footer bg-secondary">
    <div class="container-fluid pt-md-3">
      <div class="row py-md-5">
        <div class="col-md-2 col-sm-12 mt-5 mt-md-0">
          <div class="footer-logo">
            <img src="https://res.cloudinary.com/travel-wahoo/image/upload/v1616752338/travel-tiqwa-06_icbmz7.svg" alt="tiqwa">
          </div>
        </div>
        <div class="col-md-5 col-sm-12">
          <h4 class="footer-header">
            Subscribe to our special offers
          </h4>
          <p class="mt-5">
            Save with our latest fares and offer
          </p>
          <div class="news-letter">
            <form class="form-inline">
              <input class="form-control py-3" name="email" type="text" placeholder="Enter your email">
              <button class="btn bg-primary text-white ml-md-3 mt-2 mt-md-0">
                Subscribe
              </button>
            </form>
          </div>
          <div class="unscribe mt-3">
            <a>
              Unsubscribe or change your preferences
            </a>
          </div>
          <div class="col-md-8 pl-md-0 mt-2">
            For details on how we use your information, please see our <a class="privacy" href="">privacy policy</a>.
          </div>
        </div>
        <div class="col-md-2 col-sm-12 mt-3 mt-md-0">
          <h4 class="footer-header">
            Plan Your Trip
          </h4>
          <div>
            <!-- <button class="btn bg-primary text-white "> -->
              Check my trip
            <!-- </button> -->
          </div>
        </div>
        <div class="col-md-3 col-sm-12">
          <div class="d-flex flex-column w-100 justify-content-end ">
            <h3 class="footer-header mt-3 mt-md-0">
              Connect with us
            </h3>
            <div class="d-flex">
              <div class="icon">
                <i class="fa fa-instagram" />
              </div>
              <div class="icon ml-2 ">
                <i class="fa fa-twitter" />
              </div>
              <div class="icon ml-2 ">
                <i class="fa fa-facebook" />
              </div>
              <div class="icon ml-2 ">
                <i class="fa fa-linkedin" />
              </div>
            </div>
            <div class="footer-contacts">
              <p class="mt-2">
                111 Royce road Owerri
              </p>
              <p class="mt-2">
                hello@tqwa.com
              </p>
              <p class="mt-2">
                08092179343
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style>
.footer-logo{
  width: 280px;
  height: 70px;
  position: relative;
}
.footer-logo img{
  left: -72px;
  top: -20px;
  position: absolute;
}
.footer-header, .unscribe, .footer-contacts{
  font-weight: 700;
  font-size: 16px;
  color: #000;
}
.footer .icon{
  width: 25px;
  height: 25px;
  background: var(--primary);
  color: #fff;
  border-radius: 50%;
  text-align: center;
}
.news-letter form input{
  border-radius: 8px;
}
.news-letter form button{
  width:120px;
  border-radius: 4px;
}
.news-letter form input, .news-letter form button{
  border: none;
  height: 50px;
}
.unscribe {
  text-decoration: underline;
  font-size: 16px;
}
.privacy{
  color: black;
  font-size: 16px;
  font-weight: 700;
  text-decoration: underline;
}
@media (min-width: 320px) and (max-width: 480px) {

}
</style>
