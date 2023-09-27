<template>
  <div>
    <div class="carousel slide" data-bs-ride="carousel" id="carouselExampleRide">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="~/static/images/Essham1.png" class="d-block w-100" alt="Slider image 1">
        </div>
        <div class="carousel-item">
          <img src="~/static/images/Essham2.png" class="d-block w-100" alt="Slider image 2">
        </div>
        <div class="carousel-item">
          <img src="~/static/images/Essham3.png" class="d-block w-100" alt="Slider image 3">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleRide" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleRide" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
      <div class="carousel-text text-white ">
        <h1>ماذا يميز <span class="highlight">إسهام</span>؟</h1>
        <h4 d-sm-none>تصميم خدماتنا بناء على متطلبات العملاء لنقدم لهم خدمات, إدارة مرافق على أعلى قدر من الكفاءة
          والفعالية والجودة </h4>
        <a href="https://api.whatsapp.com/send?phone=996570573333&text=مرحبا ، معكم مؤسسة اسهام"
          class="btn btn-secondary py-1 px-4 mt-sm-5">اتصل بنا</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'slider'
}
</script>