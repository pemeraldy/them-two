/* eslint-disable */
<template>
  <div class="">
    <AppHeader />
    <Hero />
    <TopDeals />
    <Conversion />
    <AppFooter />
  </div>
</template>

<script>

export default {
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap');
html{
  overflow-x: hidden;
}
body{
  min-height: 100vh;
  font-family: 'Inter', sans-serif;
  overflow-x: hidden;
}
textarea:focus,
textarea.form-control:focus,
input.form-control:focus,
input[type=text]:focus,
input[type=password]:focus,
input[type=email]:focus,
input[type=number]:focus,
[type=text].form-control:focus,
[type=password].form-control:focus,
[type=email].form-control:focus,
[type=tel].form-control:focus,
[contenteditable].form-control:focus {
  box-shadow: inset 0 -1px 0 #ddd;
}

@media (min-width: 320px) and (max-width: 480px) {
    .top-deals-summ{
      width: 100%;
    }

}
</style>
