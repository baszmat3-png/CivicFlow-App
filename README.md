# CivicFlow (Android)

تطبيق أندرويد لنظام **CivicFlow** لإدارة الصادر والوارد والمعاملات. يفتح الواجهة المستضافة على
https://civicflow-frontend-1-hoy9.onrender.com داخل تطبيق مع دعم رفع الملفات والتنزيل والسحب للتحديث.

## تحميل APK

https://github.com/baszmat3-png/CivicFlow-App/releases/latest/download/CivicFlow.apk

(يُبنى ويُنشر تلقائيًا عبر GitHub Actions عند كل push إلى `main`.)

## التثبيت
1. افتح الرابط من هاتف أندرويد وحمّل الملف.
2. اسمح بالتثبيت من مصادر غير معروفة عند الطلب.
3. افتح التطبيق. قد يحتاج الخادم إلى نحو دقيقة عند أول تشغيل (استضافة Render المجانية).

## تغيير عنوان الموقع
عدّل الثابت `SITE` في `app/src/main/java/com/civicflow/app/MainActivity.java`.
