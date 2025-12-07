<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>🌟 تطبيق الأسطورة - كل الأدوات في مكان واحد</title>
<style>
body {
    font-family: 'Arial', sans-serif;
    background: linear-gradient(135deg, #e0f7fa 0%, #b2ebf2 100%); /* تدرج أزرق فاتح وجذاب */
    margin: 0;
    padding: 20px;
}
.container {
    max-width: 800px;
    margin: auto;
    background: #ffffff;
    padding: 30px;
    border-radius: 15px;
    border: 5px solid #00bcd4; /* لون مائي مميز */
    box-shadow: 0 8px 25px rgba(0,0,0,0.3); /* ظل أكثر عمقاً */
    transition: transform 0.3s ease;
}
.container:hover {
    transform: translateY(-5px); /* تأثير رفع خفيف عند التمرير */
}
.title {
    text-align: center;
    font-size: 30px;
    color: #ff5722; /* لون برتقالي مميز وجذاب */
    font-weight: 900;
    margin-bottom: 25px;
    padding-bottom: 10px;
    border-bottom: 3px dashed #ffab91;
    text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
}
.subtitle {
    text-align: center;
    font-size: 18px;
    color: #4a4a4a;
    margin-bottom: 30px;
}
.section-title {
    font-size: 24px;
    margin-top: 30px;
    margin-bottom: 15px;
    color: #00838f; /* لون أزرق سماوي غامق */
    font-weight: bold;
    border-right: 5px solid #ff9800; /* خط جانبي للتأكيد */
    padding-right: 10px;
}
ul {
    list-style: none;
    margin: 15px 0;
    padding: 0;
}
li {
    font-size: 17px;
    margin-bottom: 12px;
    padding: 10px 40px 10px 15px;
    position: relative;
    color: #333;
    background: #f4f6f9; /* خلفية فاتحة للبنود */
    border-radius: 8px;
    transition: background-color 0.3s;
}
li:hover {
    background-color: #e3f2fd; /* تمييز عند التمرير */
}
li::before {
    content: attr(data-icon); /* استخدام خاصية البيانات للأيقونة */
    position: absolute;
    right: 10px;
    font-size: 20px;
    line-height: 1;
    color: #00bcd4;
}
/* تنسيق زر التحميل الجذاب */
.download-section {
    text-align: center;
    margin-top: 40px;
    padding-top: 20px;
    border-top: 2px solid #eeeeee;
}
.download-button {
    display: inline-block;
    padding: 15px 35px;
    font-size: 22px;
    font-weight: bold;
    color: #ffffff;
    background: linear-gradient(45deg, #ff5722, #ff9800); /* تدرج لوني دافئ */
    border: none;
    border-radius: 50px;
    text-decoration: none;
    box-shadow: 0 6px 20px rgba(255, 87, 34, 0.5);
    transition: all 0.3s ease;
    animation: pulse 1.5s infinite; /* إضافة نبض لجذب الانتباه */
}
.download-button:hover {
    background: linear-gradient(45deg, #ff9800, #ff5722);
    transform: scale(1.05);
    box-shadow: 0 8px 25px rgba(255, 87, 34, 0.7);
}
@keyframes pulse {
    0% { transform: scale(1); box-shadow: 0 6px 20px rgba(255, 87, 34, 0.5); }
    50% { transform: scale(1.03); box-shadow: 0 8px 25px rgba(255, 87, 34, 0.7); }
    100% { transform: scale(1); box-shadow: 0 6px 20px rgba(255, 87, 34, 0.5); }
}
</style>
</head>
<body>

<div class="container">

    <div class="title">✨ تطبيق الأسطورة ✨</div>
    <div class="subtitle">جميع الأدوات والميزات التي تحتاجها في مكان واحد!</div>

    <div class="section-title">🤖 خدمات الذكاء الاصطناعي والبرمجة (AI & Code)</div>
    <ul>
        <li data-icon="🧠">معالج الأسطورة الذكي للمحادثات (**A.I. Core**).</li>
        <li data-icon="💻">محرر ومراجع الأكواد البرمجية (**Code Editor**).</li>
        <li data-icon="🌐">المترجم الفوري الاحترافي (Professional Translator).</li>
        <li data-icon="📚">مكتبة وموسوعة الذكاء الاصطناعي (AI Library).</li>
        <li data-icon="📜">منسق الأكواد البرمجية (Code Formatter).</li>
    </ul>

    <div class="section-title">🎨 التصميم وتعديل البيانات (Design & Data)</div>
    <ul>
        <li data-icon="🖼️">منصة تصميم الجرافيك والواجهات (Design Platform).</li>
        <li data-icon="🧊">منصة التصميم ثلاثي الأبعاد والنمذجة (**3D Modeling**).</li>
        <li data-icon="📊">أدوات تحليل البيانات المتقدمة (**Data Visualization**).</li>
        <li data-icon="📷">البحث عن الصور بدون حقوق (Stock Photos).</li>
    </ul>

    <div class="section-title">⚙️ الإنتاجية والإدارة (Productivity & Management)</div>
    <ul>
        <li data-icon="☁️">وحدة التخزين السحابي الآمن (**Secure Cloud Storage**).</li>
        <li data-icon="🔗">أداة اختصار الروابط (URL Shortener).</li>
        <li data-icon="🔠">مصحح ومدقق النصوص العربية (Text Corrector).</li>
        <li data-icon="🔒">إنشاء كلمات مرور قوية (Password Generator).</li>
        <li data-icon="🔄">محول صيغ الملفات الشامل (Universal Converter).</li>
        <li data-icon="📄">مدير ومحول ملفات PDF (PDF Management).</li>
        <li data-icon="🔢">حاسبة متقدمة ورسوم بيانية (Advanced Calculator).</li>
        <li data-icon="⛓️">مستكشف البلوك تشين (Blockchain Explorer).</li>
    </ul>

    <div class="section-title">🎮 الترفيه والبث المباشر (Entertainment & Streaming)</div>
    <ul>
        <li data-icon="⚽">محطة البث المباشر للمباريات (**SportStream**).</li>
        <li data-icon="📰">مركز الأخبار العاجلة (News Feed).</li>
        <li data-icon="📻">شبكة الراديو العالمية والعربية (RadioNet).</li>
        <li data-icon="🎬">مكتبة الأنمي والأفلام الكرتونية (AniZone).</li>
        <li data-icon="🏆">لعبة ضوء المعرفة التفاعلية (QuizRealm).</li>
    </ul>

    <div class="section-title">🛠️ أدوات مساعدة إضافية</div>
    <ul>
        <li data-icon="🚀">اختبار سرعة الإنترنت (Speed Test).</li>
        <li data-icon="🚫" style="opacity: 0.6;">خدمة الأسطورة لإزالة العلامات المائية (حالياً تحت الصيانة).</li>
    </ul>

    <div class="download-section">
        <p style="font-size: 20px; color: #00838f; font-weight: bold; margin-bottom: 20px;">لا تفوت هذه المجموعة المذهلة من الأدوات! حمل التطبيق الآن:</p>
        <a href="https://www.appcreator24.com/app3630106-tuf3dh" class="download-button" target="_blank">
            ⬇️ اضغط للتحميل المباشر ⬇️
        </a>
    </div>

</div>

</body>
</html>
