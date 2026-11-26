# Cloud Bites — النسخة الثانية
موقع عربي متجاوب يعمل بـ HTML وCSS وJavaScript فقط. التنقل بين الصفحات عبر روابط hash لكي يعمل على GitHub Pages ومن دون خادم خلفي.

## فتح الموقع
1. فك ضغط ZIP كاملا في مجلد واحد.
2. افتح index.html في Chrome أو Edge أو Safari على الكمبيوتر. لا تنقل index.html وحده من المجلد.
3. على الجوال يفضل استخدام رابط GitHub Pages بعد النشر. توجد نسخة HTML مستقلة أيضا، لكن بعض تطبيقات معاينة الملفات لا تشغل JavaScript.

## نشر GitHub Pages
1. سجل الدخول إلى github.com/new وأنشئ مستودعا عاما باسم cloud-bites.
2. من Add file > Upload files ارفع محتويات المجلد (index.html, style.css, script.js, assets, .nojekyll)، وليس ملف ZIP نفسه. ثم Commit changes.
3. Settings > Pages > Build and deployment > Source: Deploy from a branch > main / (root) > Save.
4. بعد اكتمال النشر افتح https://USERNAME.github.io/cloud-bites/ مع استبدال USERNAME باسم حسابك.

## التعديل
- script.js: قائمة المنتجات والأسعار ورسوم التوصيل والصفحات.
- style.css: الألوان والخطوط والتنسيق المتجاوب.
- index.html: الهيكل العام والتنقل.
- assets: رسومات SVG للمنتجات.

الأسعار والمدن ورسوم التوصيل افتراضية. إتمام الطلب محاكاة محلية، لا يرسل بيانات العميل ولا يستقبل دفعات أو طلبات حقيقية. السلة تحفظ محليا إذا سمح المتصفح؛ بيانات التوصيل لا تحفظ. يلزم ربط نظام طلبات وخادم آمن وبوابة دفع قبل التشغيل التجاري.
