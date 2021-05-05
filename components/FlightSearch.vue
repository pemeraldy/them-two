<template>
  <div class="search-flight-wrap">
    <h3>Search & Book cheap flights</h3>
    <div class="search-component-container mt-md-3">
      <div class="d-flex pillz-wrapper">
        <div class="pillz">
          One-way
        </div>
        <div class="pillz active">
          Round trip
        </div>
        <div class="pillz">
          Multi-city
        </div>
      </div>
      <div class="p-4">
        <form class="flight-form p-md-2">
          <div class="form-row bg-white p-2 rounded-lg">
            <div class="col-md-3">
              <div class="d-flex align-items-center">
                <img width="20" height="10" src="~/assets/images/icons/departure.png" alt="departure">
                <input type="text" class="form-control" placeholder="From">
              </div>
            </div>
            <div class="col-md-3">
              <div class="d-flex align-items-center">
                <img width="20" src="~/assets/images/icons/arrival.png" alt="arrival">
                <input type="text" class="form-control" placeholder="To">
              </div>
            </div>
            <div class="col-md-3">
              <div class="d-flex align-items-center">
                <img width="14" src="~/assets/images/icons/calender.png" alt="when to leave">
                <input type="text" class="form-control" placeholder="When do you leave?">
              </div>
            </div>
            <div class="col-md-3">
              <div class="d-flex align-items-center">
                <img width="14" src="~/assets/images/icons/calender.png" alt="when to return">
                <input type="text" class="form-control" placeholder="When do you return?">
              </div>
            </div>
          </div>
          <div class="d-flex mt-4">
            <div class=" form-row w-100">
              <div class="col-md-4 mt-3 mt-md-0">
                <div class="select-wrap">
                  <label for="">Passenger</label>
                  <select id="" name="passenger-select">
                    <option value="">
                      1 Adult, 2 Kids
                    </option>
                  </select>
                </div>
              </div>
              <div class="col-md-4 mt-3 mt-md-0">
                <div class="select-wrap">
                  <label for="">Cabin class</label>
                  <select id="" name="">
                    <option value="">
                      Economy
                    </option>
                    <option value="">
                      Premium
                    </option>
                  </select>
                </div>
              </div>
              <div class="ml-auto col-md-2 col-12 mt-3 mt-md-0 d-flex justify-content-end">
                <button class="btn bg-primary text-white">
                  Book Flight
                </button>
              </div>
            </div>
            <!-- <div class="">

            </div> -->
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.search-flight-wrap{
  color: white;
}
.search-component-container{
  border: 1px solid rgba(255, 255, 255, 0.5);
  /* background: rgba(137, 17, 137, 0.2); */
  background: #8d6fd3;
  border-radius: 16px;
  margin: 0 auto;
}
@media only screen and (min-width: 768px) {
  .search-component-container{
    /* width:930px; */
  }
  .search-flight-wrap h3{
    /* width: 930px; */
    /* margin: 0 auto; */
  }
}
.pillz:first-child{
  border-top-left-radius: 16px;
}
.pillz.active{
  background: #fff;
  color: var(--primary);
  font-weight: 500;
}
.pillz{
  width: 110px;
  border: 1px solid #fff;
  padding: 10px;
}
.flight-form{
  border-radius: 8px;
}
.flight-form input:focus{
  outline: none !important;
  border: none !important;
}
.flight-form input{
  background: none;
  border: none;
}
.flight-form select{
  background: transparent;
  border:none;
  color:#fff;
  width: 100%;
}
.select-wrap{
  position: relative;
  min-width: 150px;
  max-width: 100%;
  padding: 10px;
  border: 1px solid #fff;
  border-radius: 8px;
  background: transparent;
}
.select-wrap label{
  font-size: 12px;
  top: -10px;
  position: absolute;
  background: #8d6fd3;
  padding: 0 5px
}
.passenger-select{
  width: 200px;
}
@media (min-width: 320px) and (max-width: 480px) {
    .pillz-wrapper{
      align-items: center;
    }
    .pillz{
      flex-grow: 1;
    }
    .pillz:last-child{
      border-top-right-radius: 16px;
    }
    .search-flight-wrap h3{
    font-size: 20px;
  }
}
</style>
