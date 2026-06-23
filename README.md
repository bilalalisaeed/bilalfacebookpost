<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Facebook Post - Bilal Ali</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700;800&family=Noto+Nastaliq+Urdu:wght@400;700&display=swap');

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: linear-gradient(135deg, #1a1a2e 0%, #16213e 50%, #0f3460 100%);
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 20px;
    font-family: 'Poppins', sans-serif;
  }

  .card {
    background: white;
    border-radius: 20px;
    max-width: 680px;
    width: 100%;
    overflow: hidden;
    box-shadow: 0 30px 80px rgba(0,0,0,0.4);
  }

  .header {
    background: linear-gradient(135deg, #0f3460, #533483);
    padding: 35px 30px;
    text-align: center;
    position: relative;
  }

  .flag {
    font-size: 40px;
    margin-bottom: 10px;
  }

  .header h1 {
    color: #FFD700;
    font-size: 26px;
    font-weight: 800;
    line-height: 1.3;
    text-shadow: 0 2px 10px rgba(0,0,0,0.3);
  }

  .header p {
    color: rgba(255,255,255,0.85);
    font-size: 14px;
    margin-top: 8px;
  }

  .badge {
    display: inline-block;
    background: #FFD700;
    color: #0f3460;
    font-weight: 700;
    font-size: 13px;
    padding: 5px 16px;
    border-radius: 20px;
    margin-top: 14px;
  }

  .body {
    padding: 30px;
  }

  .section-en {
    margin-bottom: 30px;
  }

  .section-title {
    font-size: 13px;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 2px;
    color: #533483;
    margin-bottom: 12px;
    border-left: 4px solid #FFD700;
    padding-left: 10px;
  }

  .section-en p {
    font-size: 15px;
    color: #2d2d2d;
    line-height: 1.8;
  }

  .steps {
    background: #f8f6ff;
    border-radius: 14px;
    padding: 20px;
    margin: 20px 0;
  }

  .step {
    display: flex;
    align-items: flex-start;
    gap: 14px;
    margin-bottom: 14px;
  }

  .step:last-child { margin-bottom: 0; }

  .step-num {
    background: #533483;
    color: white;
    font-weight: 700;
    font-size: 12px;
    width: 26px;
    height: 26px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-shrink: 0;
    margin-top: 2px;
  }

  .step p {
    font-size: 14px;
    color: #333;
    line-height: 1.6;
  }

  .highlight-box {
    background: linear-gradient(135deg, #0f3460, #533483);
    border-radius: 14px;
    padding: 20px;
    text-align: center;
    margin: 20px 0;
  }

  .highlight-box .big {
    font-size: 42px;
    font-weight: 800;
    color: #FFD700;
  }

  .highlight-box p {
    color: white;
    font-size: 14px;
    margin-top: 4px;
  }

  .divider {
    border: none;
    border-top: 2px dashed #e0d8f5;
    margin: 25px 0;
  }

  /* URDU SECTION */
  .section-urdu {
    direction: rtl;
    font-family: 'Noto Nastaliq Urdu', serif;
  }

  .section-urdu .section-title {
    font-family: 'Poppins', sans-serif;
    border-left: none;
    border-right: 4px solid #FFD700;
    padding-left: 0;
    padding-right: 10px;
    text-align: right;
  }

  .section-urdu p {
    font-size: 17px;
    color: #2d2d2d;
    line-height: 2.4;
    text-align: right;
  }

  .urdu-steps {
    background: #f8f6ff;
    border-radius: 14px;
    padding: 20px;
    margin: 16px 0;
  }

  .urdu-step {
    display: flex;
    flex-direction: row-reverse;
    align-items: flex-start;
    gap: 14px;
    margin-bottom: 14px;
  }

  .urdu-step:last-child { margin-bottom: 0; }

  .urdu-step p {
    font-size: 16px;
    color: #333;
    line-height: 2.2;
    text-align: right;
  }

  .help-box {
    background: #fff8e1;
    border: 2px solid #FFD700;
    border-radius: 14px;
    padding: 18px 20px;
    margin-top: 20px;
    text-align: center;
  }

  .help-box p {
    font-size: 14px;
    color: #333;
    line-height: 1.7;
  }

  .help-box .urdu-help {
    font-family: 'Noto Nastaliq Urdu', serif;
    font-size: 17px;
    direction: rtl;
    color: #333;
    line-height: 2.3;
    margin-top: 10px;
  }

  .footer {
    background: #0f3460;
    padding: 18px 30px;
    text-align: center;
  }

  .footer p {
    color: rgba(255,255,255,0.7);
    font-size: 12px;
  }

  .footer .name {
    color: #FFD700;
    font-weight: 700;
    font-size: 15px;
    margin-bottom: 4px;
  }

  .tools {
    display: flex;
    justify-content: center;
    gap: 10px;
    margin-top: 10px;
    flex-wrap: wrap;
  }

  .tool-tag {
    background: rgba(255,255,255,0.15);
    color: white;
    font-size: 11px;
    padding: 4px 12px;
    border-radius: 20px;
  }
</style>
</head>
<body>
<div class="card">

  <!-- HEADER -->
  <div class="header">
    <div class="flag">🇵🇰 🎓 🇨🇾</div>
    <h1>From a Small Village in Mirpurkhas<br>to a Master's Degree in Cyprus! 🎉</h1>
    <p>Near East University — Computer Engineering</p>
    <div class="badge">✅ 55% Scholarship Achieved!</div>
  </div>

  <div class="body">

    <!-- ENGLISH SECTION -->
    <div class="section-en">
      <div class="section-title">🇬🇧 My Story — In English</div>

      <p>Assalam o Alaikum everyone! 🙏<br><br>
      I am <strong>Bilal Ali</strong> from a small village in <strong>Mirpurkhas, Sindh, Pakistan</strong>. I am a private teacher with very limited resources — but Alhamdulillah, I never gave up on my dream of higher education.<br><br>
      Today, I am proud to share that I have been <strong>conditionally accepted</strong> into the <strong>Master's Program in Computer Engineering</strong> at <strong>Near East University, Cyprus</strong> — and I have been awarded a <strong>55% Scholarship!</strong> 🎉
      </p>

      <div class="highlight-box">
        <div class="big">55%</div>
        <p>Scholarship from Near East University, Cyprus 🇨🇾</p>
      </div>

      <p>Here is how I did it — step by step:</p>

      <div class="steps">
        <div class="step">
          <div class="step-num">1</div>
          <p><strong>Found the University:</strong> I researched online and applied to Near East University (NEU) in Cyprus.</p>
        </div>
        <div class="step">
          <div class="step-num">2</div>
          <p><strong>Filled the Application Form:</strong> With the help of <strong>ChatGPT</strong> and <strong>Claude AI</strong>, I filled out my application form correctly and professionally.</p>
        </div>
        <div class="step">
          <div class="step-num">3</div>
          <p><strong>Emailed the Admissions Department:</strong> I wrote a polite and professional email to the admission director — again with AI assistance.</p>
        </div>
        <div class="step">
          <div class="step-num">4</div>
          <p><strong>Received Conditional Acceptance:</strong> The university evaluated my credentials and sent me a Conditional Acceptance Letter with a 55% scholarship.</p>
        </div>
        <div class="step">
          <div class="step-num">5</div>
          <p><strong>Never gave up:</strong> Even with limited resources, I kept pushing forward — and it paid off! 💪</p>
        </div>
      </div>

      <p>If I can do this from a small village — <strong>so can you!</strong> 🌟<br>
      AI tools like ChatGPT and Claude helped me communicate professionally in English, understand university requirements, and draft perfect emails. <strong>Use these tools — they are free and powerful!</strong></p>
    </div>

    <hr class="divider">

    <!-- URDU SECTION -->
    <div class="section-urdu">
      <div class="section-title">🇵🇰 میری کہانی — اردو میں</div>

      <p>
        السلام علیکم دوستو! 🙏<br><br>
        میں <strong>بلال علی</strong> ہوں — میرپورخاص، سندھ کے ایک چھوٹے سے گاؤں سے تعلق رکھتا ہوں۔ میں ایک پرائیویٹ ٹیچر ہوں اور وسائل بہت محدود ہیں — لیکن الحمدللہ، اپنے خواب سے کبھی پیچھے نہیں ہٹا۔<br><br>
        آج میں فخر کے ساتھ بتانا چاہتا ہوں کہ مجھے <strong>نیئر ایسٹ یونیورسٹی، قبرص</strong> میں <strong>کمپیوٹر انجینئرنگ کے ماسٹرز پروگرام</strong> میں داخلہ مل گیا ہے — اور ساتھ میں <strong>55% اسکالرشپ</strong> بھی! 🎉
      </p>

      <div class="urdu-steps">
        <div class="urdu-step">
          <div class="step-num">1</div>
          <p><strong>یونیورسٹی تلاش کی:</strong> آن لائن ریسرچ کرکے نیئر ایسٹ یونیورسٹی میں اپلائی کیا۔</p>
        </div>
        <div class="urdu-step">
          <div class="step-num">2</div>
          <p><strong>فارم بھرا:</strong> <strong>ChatGPT</strong> اور <strong>Claude AI</strong> کی مدد سے اپلیکیشن فارم صحیح اور پروفیشنل طریقے سے بھرا۔</p>
        </div>
        <div class="urdu-step">
          <div class="step-num">3</div>
          <p><strong>ایڈمیشن ڈیپارٹمنٹ کو ای میل کی:</strong> AI کی مدد سے ایک شاندار اور پُر اثر ای میل لکھی۔</p>
        </div>
        <div class="urdu-step">
          <div class="step-num">4</div>
          <p><strong>کنڈیشنل لیٹر ملا:</strong> یونیورسٹی نے میری قابلیت دیکھی اور 55% اسکالرشپ کے ساتھ داخلہ دیا۔</p>
        </div>
        <div class="urdu-step">
          <div class="step-num">5</div>
          <p><strong>ہمت نہیں ہاری:</strong> محدود وسائل کے باوجود ڈٹا رہا — اور کامیاب ہوا! 💪</p>
        </div>
      </div>

      <p>
        اگر میں ایک چھوٹے سے گاؤں سے یہ کر سکتا ہوں — <strong>تو آپ بھی کر سکتے ہیں!</strong> 🌟<br><br>
        ChatGPT اور Claude جیسے AI ٹولز نے مجھے انگریزی میں پروفیشنل طریقے سے بات کرنے، یونیورسٹی کی ضروریات سمجھنے اور بہترین ای میلز لکھنے میں مدد کی۔ <strong>یہ ٹولز بالکل مفت اور بہت طاقتور ہیں — ضرور استعمال کریں!</strong>
      </p>
    </div>

    <!-- HELP BOX -->
    <div class="help-box">
      <p>💬 <strong>Need help with university applications, scholarships, or emails?</strong><br>
      I am ready to guide you — feel free to message me anytime! DM me or comment below. 👇</p>
      <div class="urdu-help">
        💬 اگر آپ کو یونیورسٹی داخلے، اسکالرشپ یا ای میل میں کوئی مدد چاہیے تو مجھ سے رابطہ کریں — میں مدد کے لیے ہمیشہ حاضر ہوں! 🙏
      </div>
    </div>

  </div>

  <!-- FOOTER -->
  <div class="footer">
    <div class="name">— Bilal Ali | Mirpurkhas, Sindh 🇵🇰</div>
    <p>Master's Student | Near East University, Cyprus</p>
    <div class="tools">
      <span class="tool-tag">🤖 ChatGPT</span>
      <span class="tool-tag">🤖 Claude AI</span>
      <span class="tool-tag">🎓 NEU Cyprus</span>
      <span class="tool-tag">💡 55% Scholarship</span>
    </div>
  </div>

</div>
</body>
</html>