<template>
    <div class="contact-us-section py-5" id="ContactUs">
        <form action="https://formsubmit.co/Essham_1@outlook.com" method="post">
            <input type="hidden" name="_next" value="http://localhost:3000/submit">
            <div class="container container-contact py-5">
                <div>
                    <h2 class="text-end py-3">إرسل طلبك</h2>
                </div>
                <div class="row text-center">
                    <div class="col-md-6 mb-3">
                        <div class="form-group">
                            <input type="text" class="form-control text-end" id="apartment_number" name="apartment_number"
                                placeholder="رقم الشقة / الوحدة">
                        </div>
                    </div>
                    <div class="col-md-6 mb-3">
                        <div class="form-group">
                            <input type="text" class="form-control text-end" id="name" name="name" placeholder="الاسم">
                        </div>
                    </div>
                    <div class="col-md-6 mb-3">
                        <div class="form-group">
                            <input type="text" class="form-control text-end" id="email" name="phone_number" placeholder="رقم الهاتف">
                        </div>
                    </div>
                    <div class="col-md-6 mb-3">
                        <div class="form-group">
                            <input type="text" class="form-control text-end" id="phone" name="project_name"  placeholder="اسم المشروع">
                        </div>
                    </div>
                    <div class="col-md-12 mb-3">
                        <div class="form-group">
                            <select class="form-select text-end" aria-label="Default select example" name="selected_service">
                                 <option selected>الخدمة</option>
                                 <option value="support_and_administrative">خدمات الإدارة والدعم</option>
                                 <option value="addtional_services">خدمات اضافية</option>
                            </select>
                        </div>
                    </div>
                    <div class="col-md-12">
                        <div class="form-group">
                            <textarea class="form-control text-end" name="notes" id="notes" rows="4" placeholder="الملاحظات"></textarea>
                        </div>
                    </div>
                    <div class="col-md-12">
                        <div class="form-group text-end">
                            <button type="submit" class="btn btn-secondary py-1 px-4 mt-3">إرسال</button>
                        </div>
                    </div>
                </div>
            </div>
        </form>
    </div>
</template>

<script>
export default {
    name: 'Contact'
}
</script>