<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-primary">
    <div class="container">
      <a class="navbar-brand text-white" href="#">
        <!-- Tiqwa -->
        <!-- <i class="fa fa-home" /> -->
        <img class="app-logo ml-md-n5 d-none d-md-inline-block" src="https://res.cloudinary.com/travel-wahoo/image/upload/v1616752338/tiqwa-logo-white_guz7nr.svg" alt="">
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon" />
      </button>

      <div id="navbarSupportedContent" class="collapse navbar-collapse">
        <ul class="navbar-nav text-white  mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Flight</a>
          </li>
          <li class="nav-item ml-3">
            <a class="nav-link" href="#">Sign in</a>
          </li>
          <li class="nav-item ml-3">
            <a class="nav-link" href="#">Sign up</a>
          </li>
        </ul>
        <div class="form-inline my-2 my-lg-0">
          <button class="btn btn-outline-light my-2 my-sm-0 px-md-4 py-md-2 " type="submit">
            <i class="fa fa-phone" /> Book via phone
          </button>
          <button class="btn btn-secondary my-2 ml-3 my-sm-0 px-md-4 py-md-2" type="submit">
            Check my trip
          </button>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.app-logo{
  width: 90%;
}
.navbar-light .navbar-nav .nav-link{
  color: #fff
}
.navbar-light .navbar-nav .nav-link:hover{
  color: var(--secondary);
}
.navbar-light .navbar-nav .active > .nav-link{
  border-bottom: 2px solid white;
  color: white;
}
</style>
