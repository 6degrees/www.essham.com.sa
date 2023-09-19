<template>


<div class="contact-us-section py-5">
<div class="container container-contact py-5">
    <div>
        <h2 class="text-end py-3">إرسل طلبك</h2>
    </div>
    <div class="row text-center">
        <div class="col-md-6 mb-3">
            <div class="form-group">
                <input type="text" class="form-control text-end" id="first-name" placeholder="رقم الشقة / الوحدة">
            </div>
        </div>
        <div class="col-md-6 mb-3">
            <div class="form-group">
                <input type="text" class="form-control text-end" id="last-name" placeholder="الاسم">
            </div>
        </div>
        <div class="col-md-6 mb-3">
            <div class="form-group">
                <input type="email" class="form-control text-end" id="email" placeholder="رقم الهاتف">
            </div>
        </div>
        <div class="col-md-6 mb-3">
            <div class="form-group">
                <input type="text" class="form-control text-end" id="phone" placeholder="اسم المشروع">
            </div>
        </div>
        <div class="col-md-12 mb-3">
            <div class="form-group">
                <select class="form-control text-end" id="request-type">
                    <option value="type1">Type 1</option>
                    <option value="type2">Type 2</option>
                    <option value="type3">Type 3</option>
                </select>
            </div>
        </div>
        <div class="col-md-12 mb-3">
             <input class="form-control" type="file" id="formFile">
        </div>
        <div class="col-md-12">
            <div class="form-group">
                <textarea class="form-control text-end" id="notes" rows="4" placeholder="الملاحظات"></textarea>
            </div>
        </div>
        <div class="col-md-12">
            <div class="form-group text-end">
                <button type="submit" class="btn btn-secondary py-1 px-4 mt-sm-3">Submit</button>
            </div>
        </div>
    </div>
</div>

</div>
</template>

<script>
export default {
name: 'Contact'
}

</script>