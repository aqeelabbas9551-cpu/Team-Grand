# Team Grand — Android Project

هذا مشروع Android Studio كامل لتطبيق Team Grand، مبني على WebView ويضع واجهة التطبيق الحالية داخل تطبيق Android أصلي.

## البناء إلى APK
1. افتح المجلد في Android Studio.
2. اسم المشروع: TeamGrand.
3. تأكد من تثبيت Android SDK 35 وBuild Tools.
4. انتظر Gradle Sync.
5. من Build اختر Generate App Bundles or APKs > Generate APKs.
6. ملف debug APK سيظهر عادة داخل `app/build/outputs/apk/debug/`.

## AI الطعام
واجهة تحليل الوجبات موجودة في `assets/index.html`، لكنها تحتاج Endpoint AI حقيقي يعيد JSON بالصيغة التي يتوقعها التطبيق. لا تضع مفتاح API سري داخل التطبيق.
