<template>
  <div class="search-flight-wrap">
    <h3>Search & Book cheap flights</h3>
    <div class="search-component-container">
      <form>
        <div class="form-row">
          <div class="col-3 col-sm-12">
            <input type="text" class="form-control" placeholder="City">
          </div>
          <div class="col-3 col-sm-12">
            <input type="text" class="form-control" placeholder="State">
          </div>
          <div class="col-3 col-sm-12">
            <input type="text" class="form-control" placeholder="Zip">
          </div>
        </div>
      </form>
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
  min-width:930px;
  background: rgba(137, 17, 137, 0.2);
  border-radius: 16px;
}
</style>
