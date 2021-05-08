<template>
  <section class="conversion">
    <div class="blur-bg  d-md-block" />
    <div class="row">
      <div class="col-md-6">
        <div class=" align-items-baseline ml-3 ml-md-0 align-items-md-center d-flex flex-column conversion-content justify-content-center align-items-center">
          <div class="conversion-inner">
            <h1>Check my trip</h1>
            <p>
              Whether it’s your first flight or simply your latest, we work to anticipate your
              every need.
            </p>
            <button class="bg-primary text-white">
              Check my trip
            </button>
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
.conversion{
  position: relative;
  background: url(~/assets/images/heroes/dessert-bg.png);
  background-size: cover;
  background-position: center;
  height: 444px;
}

.blur-bg{
  position: absolute;
  width: 100%;
  height: 100%;
  background:rgba(137, 17, 137, 0.1);
  width: 50%;
  background: url(~/assets/images/heroes/img-blur.png);
  background-size: cover;
  /* z-index: ; */
}

.conversion-inner button{
  border: none;
  outline: none;
  border-radius: 8px;
  font-weight: 500;
  font-size: 16px;
  width: 205px;
  height: 44px;
}
.conversion-inner p{
  width: 350px;
}

.conversion .row, .container .row{
  height: 100%;
}
.conversion h1{
  font-weight: 700;
  font-size: 48px;
  color: #fff;
}
.conversion p{
  font-weight: 500;
  font-size: 14px;
  color: #fff;
}
.conversion-content{
  height: 100%;
}
@media (min-width: 320px) and (max-width: 480px) {
  .conversion{
    background: url(~/assets/images/heroes/dessert-BG-mobile.png);
    background-size: cover;
  }
  .blur-bg{
    background: url(~/assets/images/heroes/dessert-BG-mobile-blur.png);
    background-size: cover;
  }
  .conversion-inner h1{
    font-size: 18px;
  }
  .conversion-inner p{
    font-size: 10px;
    width:128px;
  }
}
</style>
