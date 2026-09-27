Turbo Delivery Android App
==========================

هذا مشروع Android Studio جاهز ومربوط بالموقع:
https://turbo.wuaze.com/index.php

المشروع لا يحتوي على قاعدة بيانات جديدة ولا يغير بيانات الموقع.
التطبيق عبارة عن WebView احترافي للموقع.

طريقة إخراج APK:
1) افتح المجلد في Android Studio.
2) انتظر Gradle Sync.
3) Build > Build APK(s)
4) ملف الـAPK سيظهر داخل:
   app/build/outputs/apk/debug/app-debug.apk

ملاحظة:
إذا كان الموقع يفتح 403 من بعض الشبكات/الخوادم، فالتطبيق سيعرض نفس المشكلة لأن مصدر البيانات هو الموقع نفسه.
