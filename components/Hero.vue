<template>
  <section class="app-hero py-md-5">
    <div class="container">
      <div class="row inner-wrapper">
        <div class="col-md-2" />
        <div class="col-md-8">
          <div class="tagline">
            <h1>Save on your next flight</h1>
            <p>Thounsands of jaw dropping deals made everyday</p>
          </div>
        </div>
        <div class="col-md-2" />
      </div>
      <div class="row">
        <div class="col-md-2" />
        <div class="col-md-8">
          <FlightSearch />
        </div>
        <div class="col-md-2" />
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
</style>
