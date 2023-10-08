<template>
    <div class="container" id="Services">
        <div>
            <h2 class="text-center py-5"><a class="link-offset-3">خدماتنا</a></h2>
        </div>
        <div class="row">
            <div class="col-md-6 d-flex">
                <div class="card py-4 my-5 border-2 flex-fill rounded-1">
                    <div class="card-body text-center">
                        <img :src="require('~/static/images/icon1.webp')" class="icon-img" alt="">
                        <h3 class="card-title mt-5">خدمات الصيانة</h3>
                        <p class="card-text mt-4 text-end">تتضمن الخدمات الإضافية خدمات النظافة والصيانة صيانة
                            المصاعد،الإنارة،اعمال الدهان، اعمال السباكة والكهرباء صيانة الابواب ، الممرات الداخلية، كاميرات
                            المراقبة.صيانة مظلات السيارات اجهزة السلامة،انظمة دخول المبني</p>
                    </div>
                </div>
            </div>
            <div class="col-md-6 d-flex">
                <div class="card py-4 my-5 border-2 flex-fill rounded-1">
                    <div class="card-body text-center">
                        <img :src="require('~/static/images/icon2.webp')" class="icon-img" alt="">
                        <h3 class="card-title mt-5">خدمات النظافة</h3>
                        <p class="card-text mt-4 text-end">تأسيس نظام داخلي،إنشاء مجموعة رقمية للمستأجرين والملاك، إنشاء
                            حساب في منصة ملاك، تطبيق لوائح اتحاد الملاك، تأمين وتوريد المياه،تصريف المياه، تأمين مصادر
                            الطاقة، خدمة عملاء على مدار الساعة</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Services'
    }
</script>