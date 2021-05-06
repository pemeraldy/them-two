<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-primary">
    <div class="container">
      <a class="navbar-brand text-white" href="#">
        <!-- Tiqwa -->
        <!-- <i class="fa fa-home" /> -->
        <img class="app-logo ml-md-n5 d-md-inline-block" src="https://res.cloudinary.com/travel-wahoo/image/upload/v1616752338/tiqwa-logo-white_guz7nr.svg" alt="">
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
            <span class="border-bottom" />
          </li>
          <li class="nav-item ml-3">
            <a class="nav-link" href="#">Sign in</a>
            <span class="border-bottom" />
          </li>
          <li class="nav-item ml-3">
            <a class="nav-link" href="#">Sign up</a>
            <span class="border-bottom" />
          </li>
        </ul>
        <div class="form-inline my-2 my-lg-0">
          <button class="btn phone-book btn-outline-light my-2 my-sm-0 " type="submit">
            <i class="fa fa-phone" /> Book via phone
          </button>
          <button class="btn check-trip btn-secondary my-2 ml-3 my-sm-0" type="submit">
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
.btn.phone-book{
  width: 201px;
}
.btn.check-trip{
  color: var(--primary);
  background: #fff;
  width: 164px;
}
.btn.phone-book, .btn.check-trip{
  font-weight: 700;
  padding: 12px;
  border-radius: 8px;
}
.app-logo{
  width: 90%;
}
.navbar-light .navbar-nav .nav-link{
  color: #fff
}
.navbar-light .navbar-nav .nav-link:hover{
  color: var(--secondary);
}
.nav-item{
  height: 43px;
  overflow: hidden;
}
.border-bottom{
  transition: .3s margin ease-in;
  width: 23px;
  height: 2px;
  margin: 0 auto;
  background: #fff;
  display: block;
  margin-top: 3px;
}
.navbar-nav .nav-item:hover .nav-link ~ .border-bottom{
  margin-top: 0;
}
.navbar-nav .nav-item.active .nav-link ~ .border-bottom{
  margin-top: 0;
}
.navbar-light .navbar-nav .active > .nav-link{
  color: white;
}
@media (min-width: 400px) and (max-width: 480px) {
  .app-logo{
    margin-left: -50px;
  }
}
.yopee-wrapper:not(:focus-within):not(:hover) .hover::before {
  content: "Am avaialble :)";
}
</style>
