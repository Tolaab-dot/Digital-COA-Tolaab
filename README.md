<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Corporate Offer Agreement - Tolaab</title>

<link href="https://cdn.jsdelivr.net/npm/daisyui@latest/dist/full.min.css" rel="stylesheet" type="text/css">

<style>
:root {
  --background-color-primary: #5f2eed;
  --background-color-primary-dark: #310d9b;
  --background-color-main: #eceef5;
  --text-color-main: #292d32;
  --text-color-paragraph: #757575;
  --radius-xl: 1rem;
}

body {
  background-color: var(--background-color-main);
  font-family: ui-sans-serif, system-ui, sans-serif;
  color: var(--text-color-main);
  overflow-x: hidden;
  position: relative;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: flex-start;
  padding: 60px 16px;
}

/* 🔹 Background Video */
.bg-video {
  position: fixed;
  top: 0; left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  z-index: 0;
  opacity: 0.35;
  filter: blur(2px);
}

/* Form Card */
.form-card {
  width: 100%;
  max-width: 950px;
  background-color: rgba(255, 255, 255, 0.9);
  border-radius: var(--radius-xl);
  padding: 40px 36px 50px 36px;
  box-shadow: 0 10px 50px rgba(95, 46, 237, 0.25);
  position: relative;
  z-index: 10;
  backdrop-filter: blur(12px);
}

/* Logo */
.logo {
  width: 90px;
  height: 90px;
  margin: 0 auto 20px;
}
.logo img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

/* Titles */
h1 {
  text-align: center;
  font-size: 52px;
  font-weight: 800;
  color: #4011e8;
  margin-bottom: 20px;
}
p {
  text-align: center;
  font-size: 15px;
  color: var(--text-color-paragraph);
  margin-bottom: 40px;
}
.section-title {
  font-weight: 700;
  font-size: 22px;
  color: #4011e8;
  margin-top: 30px;
  margin-bottom: 15px;
  text-align: center;
}

/* Inputs */
input, select, .file-input {
  width: 100%;
  padding: 12px 14px;
  border: 1px solid #ddd;
  border-radius: 10px;
  background: #f9f9fb;
  font-size: 15px;
  color: #333;
  outline: none;
}
input:focus, select:focus {
  border-color: var(--background-color-primary);
  box-shadow: 0 0 0 3px rgba(95, 46, 237, 0.2);
}

/* Buttons */
.btn {
  background: linear-gradient(90deg, var(--background-color-primary), var(--background-color-primary-dark));
  color: white;
  font-size: 16px;
  font-weight: 600;
  padding: 12px;
  border: none;
  border-radius: 12px;
  cursor: pointer;
  margin-top: 25px;
  transition: transform 0.2s ease, box-shadow 0.3s;
  box-shadow: 0 10px 25px rgba(95, 46, 237, 0.3);
}
.btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 14px 30px rgba(95, 46, 237, 0.4);
}

/* Terms Section */
.toggle-section {
  display: none;
  background: #f7f7fb;
  padding: 16px;
  border-radius: 10px;
  font-size: 14px;
  line-height: 1.6;
  color: #555;
  margin-top: 10px;
}

/* Checkboxes */
.checkbox-group {
  display: flex;
  flex-direction: column;
  gap: 10px;
  margin-top: 15px;
}
.checkbox-group label {
  display: flex;
  align-items: center;
  gap: 8px;
  background: #fff;
  padding: 10px 12px;
  border-radius: 10px;
  border: 1px solid #ddd;
  cursor: pointer;
  transition: box-shadow 0.2s;
}
.checkbox-group label:hover {
  box-shadow: 0 4px 10px rgba(95, 46, 237, 0.1);
}
</style>
</head>

<body>
  <!-- 🌌 Background Video -->
  <video autoplay muted loop playsinline class="bg-video">
    <source src="https://www.dropbox.com/scl/fi/4onunbre7r0fi44ex8mbc/Introduction.mp4?rlkey=1v56pxpvw8nadepu415jyni0d&dl=1" type="video/mp4">
  </video>

  <div class="form-card">
    <!-- 🎥 Intro Video -->
    <div style="margin-bottom: 30px; text-align: center;">
      <video width="100%" controls poster="https://tolaab.com/wp-content/uploads/2025/06/ic_launcher.png"
        style="border-radius: 16px; box-shadow: 0 10px 40px rgba(95, 46, 237, 0.25); max-height: 480px;">
        <source src="https://www.dropbox.com/scl/fi/4onunbre7r0fi44ex8mbc/Introduction.mp4?rlkey=1v56pxpvw8nadepu415jyni0d&dl=1" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <p style="font-size: 14px; color: #555; margin-top: 8px;">
        🎬 Watch this short introduction before filling your agreement.
      </p>
    </div>

    <!-- Logo -->
    <div class="logo">
      <img src="https://tolaab.com/wp-content/uploads/2025/06/ic_launcher.png" alt="Tolaab Logo">
    </div>

    <!-- Main Title -->
    <h1>Corporate Offer Agreement - Tolaab</h1>
    <p>This form will be <b>Digitally Signed</b> after submission and <b>Stamped & Shared</b> back with you.</p>

    <!-- Form -->
    <form id="coaForm" action="https://formspree.io/f/mdklpbdd" method="POST" enctype="multipart/form-data">

      <div class="section-title">تفاصيل الشريك / Partner Details</div>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
        <div><label>اسم الشركة / Company Name:</label><input type="text" name="company_name" required></div>
        <div><label>العلامة التجارية / Brand(s):</label><input type="text" name="brands" required></div>
        <div><label>رقم الرخصة التجارية / License No.:</label><input type="text" name="license_no" required></div>
        <div>
          <label>الفئة / Category:</label>
          <select name="category" required>
            <option disabled selected>Select a category</option>
            <option>Retailers & Lifestyle</option><option>Restaurants</option><option>Cafes</option>
            <option>Clinic & Beauty</option><option>Auto Centers</option><option>Salons & SPA</option>
            <option>Pharmacy</option><option>Fitness</option><option>Education</option>
            <option>Entertainment</option><option>Perfume</option><option>Medical Centers</option><option>Other</option>
          </select>
        </div>
        <div>
          <label>الإمارة المقر الرئيسي / Headquarter Emirate:</label>
          <select name="headquarter_emirate" required>
            <option disabled selected>Select Emirate</option>
            <option>Abu Dhabi</option><option>Dubai</option><option>Sharjah</option>
            <option>Ajman</option><option>Umm Al Quwain</option><option>Ras Al Khaimah</option><option>Fujairah</option>
          </select>
        </div>
      </div>

      <div class="section-title">بيانات الاتصال / Contact Details</div>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
        <div><label>الشخص الذي يمكن الاتصال به / Contact Person:</label><input type="text" name="contact_person" required></div>
        <div><label>رقم الهاتف المتحرك / Mobile No.:</label><input type="tel" name="mobile_no" required></div>
      </div>

      <div class="section-title">Upload Documents</div>
      <div class="mb-4"><label>Trade License:</label><input type="file" name="trade_license" class="file-input" required></div>
      <div class="mb-4"><label>Tax Registration:</label><input type="file" name="tax_registration" class="file-input"></div>

      <div class="section-title">Transaction Commission / عمولة المعاملات</div>
      <div class="flex flex-col gap-2 mb-4">
        <label class="flex items-center gap-3 bg-white p-3 rounded-lg border cursor-pointer hover:shadow">
          <input type="radio" name="commission_option" value="option1" class="radio radio-primary" required>
          <span>First Option: 1499 AED registration + 3% transaction</span>
        </label>
        <label class="flex items-center gap-3 bg-white p-3 rounded-lg border cursor-pointer hover:shadow">
          <input type="radio" name="commission_option" value="option2" class="radio radio-primary">
          <span>Second Option: Zero upfront, 5% on transactions</span>
        </label>
      </div>

      <div class="section-title">Terms & Conditions</div>

      <div class="checkbox-group">
        <label>
          <input type="checkbox" name="accept_terms" class="checkbox checkbox-primary" required>
          <span>I accept the Terms & Conditions (<span class="text-primary cursor-pointer" onclick="toggleTerms()">Read</span>)</span>
        </label>

        <label>
          <input type="checkbox" name="marketing_consent" class="checkbox checkbox-primary" required>
          <span>I confirm marketing files are editable by Tolaab</span>
        </label>

        <label>
          <input type="checkbox" name="discount_agreement" class="checkbox checkbox-primary" required>
          <span>I confirm discount applies in all UAE branches</span>
        </label>
      </div>

      <div id="termsContent" class="toggle-section grid grid-cols-1 md:grid-cols-2 gap-6 mt-2">
        <div>
          نحن "<span id='companyNamePlaceholderAr'>Company Name</span>" نوافق على دعم برنامج طلاب والالتزام بالشروط أدناه.<br><br>
          تسري لمدة سنة من 1 نوفمبر 2025، ما لم يخطر أحد الطرفين الآخر 30 يوماً مسبقاً.<br>
          تحتفظ طلاب بحق إيقاف الخدمات في حال عدم السداد بعد 5 أيام أو الإخلال بالشروط.<br>
          يحق لأي طرف إنهاء الاتفاقية بإشعار 30 يوماً.<br>
          يتعهد الطرف الثاني بأن تكون ملفات التسويق قابلة للتحرير للطرف الأول.<br>
          يتعهد الطرف الثاني بمنح الخصم بجميع الفروع.<br>
          العمولة شهرية والتفاصيل بلوحة التحكم.<br>
          الالتزام بسرية المعلومات.<br>
          عدم استخدام المنصة لأغراض غير قانونية.<br>
          تخضع الاتفاقية لقوانين أبوظبي والإمارات.
        </div>
        <div>
          We, "<span id='companyNamePlaceholder'>Company Name</span>", agree to support Tolaab program and abide by terms below.<br><br>
          Valid for 1 year from 1st Nov 2025 unless 30-day renewal notice.<br>
          Suspension possible for non-payment or breach.<br>
          Either party may terminate with 30-day notice.<br>
          Marketing files editable for Tolaab’s use.<br>
          Discount applies to all UAE branches.<br>
          Commission tracked monthly in dashboard.<br>
          Confidentiality required.<br>
          No illegal use of Tolaab platform.<br>
          Governed by Abu Dhabi and UAE federal laws.
        </div>
      </div>

      <button type="submit" class="btn w-full">Go Next Step</button>
    </form>
  </div>

<script>
function toggleTerms() {
  const content = document.getElementById('termsContent');
  content.style.display = content.style.display === 'grid' ? 'none' : 'grid';
}
</script>
</body>
</html>
