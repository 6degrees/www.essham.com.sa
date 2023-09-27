<template>
    <div class="container">
      <div>
        <h2 class="text-center py-5"><a class="link-offset-3">شركاء النجاح</a></h2>
      </div>
      <div class="container text-center">
        <div class="row row-cols-2 row-cols-sm-1 row-cols-lg-4 row-cols-md-3 g-4">
          <div class="col-12 col-sm-6 col-md-3 mb-4">
            <div class="card justify-content-center rounded-0 p-3 border-0" style="height: 9rem;">
              <img src="~/static/images/rawas.png" alt="Image 1" class="mt-2 img-fluid p-2 partner-logo">
            </div>
          </div>
          <div class="col-12 col-sm-6 col-md-3 mb-4">
            <div class="card justify-content-center rounded-0 p-3 border-0" style="height: 10rem;">
              <img src="~/static/images/PE.png" alt="Image 2" class="mt-2 img-fluid p-2 partner-logo">
            </div>
          </div>
          <div class="col-12 col-sm-6 col-md-3 mb-4">
            <div class="card justify-content-center rounded-0 p-3 border-0" style="height: 10rem;">
              <img src="~/static/images/EC.png" alt="Image 3" class="mt-2 img-fluid p-2 partner-logo">
            </div>
          </div>
          <div class="col-12 col-sm-6 col-md-3 mb-4">
            <div class="card justify-content-center rounded-0 p-3 border-0" style="height: 10rem;">
              <img src="~/static/images/Al.png" alt="Image 4" class="mt-2 img-fluid p-2 partner-logo">
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Partners'
  }
  </script>
  
  <style scoped>
  .partner-logo {
    width: 100%;
    height: 100%;
    object-fit: contain;
  }
  </style>
  