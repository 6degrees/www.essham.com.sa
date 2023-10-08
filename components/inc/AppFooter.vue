<template>
    <footer class="footer alqabas">
        <div class="container py-5">
            <div class="row">
                <div class="col-md-4">
                    <div class="d-flex flex-column align-items-end h-100">
                        <p class="mb-3 px-3 py-3">هدفنا</p>
                        <p class="mb-3 px-3 py-3 text-end">تصميم خدماتنا بناءً على متطلبات العملاء <br> لنقدم لهم خدمات
                            إدارة مرافق على أعلى <br> قدر من الكفاءة والفعالية والجودة</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="d-flex flex-column align-items-end h-100">
                        <a href="#AboutUs" class="mb-3 px-3 py-3 text-decoration-none text-white">من نحن</a>
                        <a href="#Services" class="mb-3 px-3 py-3 text-decoration-none text-white">خدماتنا</a>
                        <a href="#ContactUs" class="mb-3 px-3 py-3 text-decoration-none text-white">تواصل معنا</a>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="d-flex flex-column align-items-end h-100">
                        <div class="d-flex align-items-center justify-content-end">
                            <p class="mb-0 ms-2 px-3 py-3 text-end">6919 طريق الأمير تركي – الخبر<br>03 مركز الكفاءة – مكتب
                            </p>
                            <img :src="require('~/static/images/location.webp')" alt="" class="img-fluid img-width">
                        </div>
                        <div class="d-flex align-items-center justify-content-end">
                            <p class="mb-0 ms-2 px-3 py-3">+966 548064886</p>
                            <img :src="require('~/static/images/telephone.webp')" alt="" class="img-fluid img-width">
                        </div>
                        <div class="d-flex align-items-center justify-content-end">
                            <p class="mb-0 ms-2 px-3 py-3">Essham_1@outlook.com</p>
                            <img :src="require('~/static/images/envelope.webp')" alt="" class="img-fluid img-width">
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="container-fluid bg-black py-3">
        </div>
    </footer>
</template>
    
<script>
export default {
    name: 'AppFooter'
}
</script>