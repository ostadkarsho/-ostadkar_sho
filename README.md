<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>استادکار شو | خدمات ساختمانی</title>
<style>
*{box-sizing:border-box}
body{margin:0;font-family:Tahoma,Arial;background:#f3f6fa;color:#202b3c}
header{background:#123b65;color:white;padding:25px 16px;text-align:center}
header h1{margin:0 0 10px;font-size:30px}
header p{margin:0;line-height:2}
main{max-width:700px;margin:22px auto;padding:0 14px}
.card{background:white;padding:22px;border-radius:16px;margin-bottom:18px;box-shadow:0 4px 16px #0000000c}
h2{margin-top:0;color:#123b65}
.services{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.service{background:#edf4fb;border:1px solid #d4e4f5;border-radius:12px;padding:15px;text-align:center;font-weight:bold}
label{display:block;margin:15px 0 7px}
input,select,textarea{width:100%;padding:12px;border:1px solid #ccd4df;border-radius:9px;font:inherit}
button{width:100%;padding:14px;background:#f2a900;color:#17283b;border:0;border-radius:10px;font-size:17px;font-weight:bold;margin-top:18px}
.note{font-size:13px;line-height:2;color:#596579}
footer{text-align:center;padding:22px;color:#68758a}
</style>
</head>
<body>
<header>
<h1>استادکار شو 🏠</h1>
<p>استادکار موردنیازت رو پیدا کن!</p>
<p>ثبت درخواست خدمات ساختمانی، ساده و سریع</p>
</header>
<main>
<section class="card">
<h2>چه خدمتی لازم داری؟</h2>
<div class="services">
<div class="service">🎨 نقاش ساختمان</div>
<div class="service">⚡ برقکار</div>
<div class="service">🧱 کنافکار</div>
<div class="service">🚰 لوله‌کش</div>
</div>
</section>
<section class="card">
<h2>ثبت درخواست استادکار</h2>
<form id="requestForm">
<label for="service">نوع خدمات</label>
<select id="service" required>
<option value="">انتخاب کن</option>
<option>نقاش ساختمان</option>
<option>برقکار</option>
<option>کنافکار</option>
<option>لوله‌کش</option>
<option>کاشی‌کار</option>
<option>بنّا</option>
<option>سایر خدمات ساختمانی</option>
</select>
<label for="city">شهر</label>
<input id="city" required placeholder="مثلاً اصفهان">
<label for="name">نام و نام خانوادگی</label>
<input id="name" required placeholder="نام شما">
<label for="phone">شماره تماس</label>
<input id="phone" type="tel" required placeholder="شماره موبایل">
<label for="details">توضیحات کار</label>
<textarea id="details" rows="4" required placeholder="چه کاری باید انجام شود؟"></textarea>
<button type="submit">ثبت درخواست</button>
</form>
<p class="note">با ثبت درخواست، اطلاعاتت باید به سامانه استادکار شو ارسال شود. اتصال سامانه دریافت درخواست در مرحله بعد راه‌اندازی خواهد شد.</p>
</section>
</main>
<footer>استادکار شو | ارتباط مشتری و استادکار</footer>
<script>
document.getElementById('requestForm').addEventListener('submit',function(e){
e.preventDefault();
alert('فرم آماده است، اما سامانه دریافت درخواست هنوز متصل نشده است. برای ارسال واقعی درخواست، باید مرحله اتصال پایگاه داده انجام شود.');
});
</script>
</body>
</html>
