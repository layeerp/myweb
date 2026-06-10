موقع روابط Layeer الجاهز للنشر على Railway

الروابط الموجودة:
Telegram: https://t.me/T_7_P
TikTok: https://www.tiktok.com/@14sc

طريقة التشغيل محلياً:
1) افتح Terminal داخل المجلد.
2) اكتب: npm start
3) افتح: http://localhost:3000

طريقة رفعه على Railway:
1) ارفع هذا المجلد إلى GitHub كـ Repository.
2) في Railway اختر New Project.
3) اختر Deploy from GitHub repo.
4) اختر هذا الـ Repository.
5) Railway سيستخدم أمر التشغيل الموجود في package.json:
   npm start
6) بعد ما يشتغل المشروع، اربط الدومين layeer.dev من إعدادات Networking / Domains.

ملاحظات:
- لا تحتاج توكن أو كلمات مرور.
- الموقع يستخدم PORT تلقائياً من Railway.
- إذا تريد تعديل الروابط أو الاسم، عدّل ملف public/index.html.
