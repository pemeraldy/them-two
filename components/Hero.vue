<template>
  <section class="app-hero py-3 pb-5 py-md-5">
    <div class="container">
      <div class="row inner-wrapper">
        <div class="col-md-2" />
        <div class="col-md-8 ">
          <div class="tagline">
            <h1>Save on your next flight</h1>
            <p>Thounsands of jaw dropping deals made everyday</p>
          </div>
        </div>
        <div class="col-md-2" />
      </div>
      <div class="row">
        <div class="col-md-1" />
        <div class="col-md-10">
          <FlightSearch />
        </div>
        <div class="col-md-1" />
      </div>
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@media only screen and (min-width: 768px){
  .inner-wrapper{
    /* width: 930px; */
    margin: 0 auto;
  }
}
.app-hero{
  min-height: 70vh;
  background: url(~/assets/images/heroes/hero-bg.png);
  background-size: cover;
  background-position: center;
}
.tagline {
  padding: 100px 0;
}
.tagline h1{
  font-weight: 700;
  font-size: 60px;
  color: #fff;
}
.tagline p{
  font-size: 24px;
  font-weight: 400;
  color: #fff;
}
@media (min-width: 360px) and (max-width: 480px) {
  .tagline{
    padding: 20px 0;
  }
  .tagline h1{
    font-size: 35px;
  }
  .tagline p{
    font-size: 12px;
  }
}
</style>
