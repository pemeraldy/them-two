<template>
  <div class="search-flight-wrap">
    <h3>Search & Book cheap flights</h3>
    <div class="search-component-container mt-md-3">
      <div class="d-flex">
        <div class="pillz active">
          One-way
        </div>
        <div class="pillz">
          Round trip
        </div>
        <div class="pillz">
          Multi city
        </div>
      </div>
      <div class="p-4">
        <form class="flight-form bg-white p-md-2">
          <div class="form-row">
            <div class="col-2">
              <div class="d-flex align-items-center">
                <img src="~/assets/images/icons/departure.png" alt="departure">
                <input type="text" class="form-control" placeholder="From">
              </div>
            </div>
            <div class="col-2">
              <input type="text" class="form-control" placeholder="To">
            </div>
            <div class="col-3">
              <input type="text" class="form-control" placeholder="When to leave">
            </div>
            <div class="col-3">
              <input type="text" class="form-control" placeholder="When to return">
            </div>
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
  background: rgba(137, 17, 137, 0.2);
  border-radius: 16px;
  margin: 0 auto;
}
@media only screen and (min-width: 768px) {
  .search-component-container{
    width:930px;
  }
  .search-flight-wrap h3{
    width: 930px;
    margin: 0 auto;
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
</style>
