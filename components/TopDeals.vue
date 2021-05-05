<template>
  <section class="top-deals py-md-5">
    <div class="container">
      <div class="row">
        <div class="col-12 text-center mt-md-5">
          <h1 class="top-deals-title mt-5 mb-1 mt-md-0">
            Top Flight Deals
          </h1>
          <p class="top-deals-summ my-md-3">
            Whether it’s your first flight or simply your latest, we work to anticipate your every need
          </p>
        </div>
      </div>
      <div class="row my-md-5 mt-3">
        <div class="col-md-3">
          <div class="flight-wrap p-3 mb-4 p-md-3">
            <div class="top d-flex justify-content-between align-items-center">
              <div class="airline-logo-wrap">
                <img src="~/assets/images/icons/airline-logo.png" alt="airline name">
              </div>
              <p class="airline-name m-0">
                Singapore Airlines
              </p>
            </div>
            <div class="flight-price mt-4">
              <h3>N445,553.60</h3>
            </div>
            <hr>
            <div class="flight-destinations">
              <div class="d-flex  justify-content-between align-items-center">
                <h1>LOS - LHR </h1><p>8h 40m</p>
              </div>
              <p class="m-0 airport-fulll-name">
                Murtala Muhammed International Airport Terminal 1
              </p>
            </div>
            <div class="flight-bottom">
              <h4>13 April, 2021</h4>
              <p>Book economy promo until May 21st</p>
            </div>
          </div>
        </div>
        <div class="col-md-3">
          <div class="flight-wrap p-3 mb-4 p-md-3">
            <div class="top d-flex justify-content-between align-items-center">
              <div class="airline-logo-wrap">
                <img src="~/assets/images/icons/airline-logo.png" alt="airline name">
              </div>
              <p class="airline-name m-0">
                Singapore Airlines
              </p>
            </div>
            <div class="flight-price mt-4">
              <h3>N445,553.60</h3>
            </div>
            <hr>
            <div class="flight-destinations">
              <div class="d-flex  justify-content-between align-items-center">
                <h1>LOS - LHR </h1><p>8h 40m</p>
              </div>
              <p class="m-0 airport-fulll-name">
                Murtala Muhammed International Airport Terminal 1
              </p>
            </div>
            <div class="flight-bottom">
              <h4>13 April, 2021</h4>
              <p>Book economy promo until May 21st</p>
            </div>
          </div>
        </div>
        <div class="col-md-3">
          <div class="flight-wrap p-3 mb-4 p-md-3">
            <div class="top d-flex justify-content-between align-items-center">
              <div class="airline-logo-wrap">
                <img src="~/assets/images/icons/airline-logo.png" alt="airline name">
              </div>
              <p class="airline-name m-0">
                Singapore Airlines
              </p>
            </div>
            <div class="flight-price mt-4">
              <h3>N445,553.60</h3>
            </div>
            <hr>
            <div class="flight-destinations">
              <div class="d-flex  justify-content-between align-items-center">
                <h1>LOS - LHR </h1><p>8h 40m</p>
              </div>
              <p class="m-0 airport-fulll-name">
                Murtala Muhammed International Airport Terminal 1
              </p>
            </div>
            <div class="flight-bottom">
              <h4>13 April, 2021</h4>
              <p>Book economy promo until May 21st</p>
            </div>
          </div>
        </div>
        <div class="col-md-3">
          <div class="flight-wrap p-3 mb-4 p-md-3">
            <div class="top d-flex justify-content-between align-items-center">
              <div class="airline-logo-wrap">
                <img src="~/assets/images/icons/airline-logo.png" alt="airline name">
              </div>
              <p class="airline-name m-0">
                Singapore Airlines
              </p>
            </div>
            <div class="flight-price mt-4">
              <h3>N445,553.60</h3>
            </div>
            <hr>
            <div class="flight-destinations">
              <div class="d-flex  justify-content-between align-items-center">
                <h1>LOS - LHR </h1><p>8h 40m</p>
              </div>
              <p class="m-0 airport-fulll-name">
                Murtala Muhammed International Airport Terminal 1
              </p>
            </div>
            <div class="flight-bottom">
              <h4>13 April, 2021</h4>
              <p>Book economy promo until May 21st</p>
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

<style >
.top-deals{
  background: url(~/assets/images/heroes/body-bg.png);
  background-size: cover;
  background-position: center;
}
.top-deals-title{
  font-weight: 700;
  font-size: 48px;
}
.top-deals-summ{
  width: 400px;
  margin: 0 auto;
  font-weight: 500;
  font-size: 18px;
}
.flight-wrap{
  border: 1px solid #fff;
  border-radius: 8px;
  min-width: 262px;
  background: rgba(255, 230, 255, 0.5);
  transition: all 0.25s ease-in;
}
.flight-wrap:hover{
  box-shadow: -3px 10px 37px 2px rgba(59,59,59,0.37); -webkit-box-shadow: -3px
10px 37px 2px rgba(59,59,59,0.37); -moz-box-shadow: -3px 10px 37px 2px
rgba(59,59,59,0.37);
}
.airline-logo-wrap{
  width: 40px;
  height: 40px;
  border-radius: 4px;
  background: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
}
.airline-name{
  font-weight: 500;
  font-size: 14px;
  color:#4E4B66;
}
.flight-price h3{
  font-weight: 700;
  font-size: 22px;
  color: #4E4B66;
}
.flight-destinations h1{
  font-weight: 700;
  font-size: 28px;
}
.flight-destinations p{
  font-size: 12px;
  font-weight: 500;
  color: #14142B;
}
.airport-fulll-name{
  max-width: 220px;
}
.flight-bottom h4{
  margin-top: 20px;
  margin-bottom: 0;
  font-size: 14px;
  font-weight: 600;
}
.flight-bottom p{
  font-size: 10px;
  font-weight: 400;
  color: #14142B;
}
@media (min-width: 320px) and (max-width: 480px) {
    .top-deals-summ{
      width: 100%;
    }
    .top-deals-title{
      font-size: 30px;
    }
}
</style>
