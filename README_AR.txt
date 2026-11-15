تطبيق خرائط شمر - مشروع Android Studio

هذا مجلد مشروع أندرويد جاهز للفتح في Android Studio، ويحتوي صفحة الموقع الحالية داخل التطبيق.
لإنشاء APK:
1) ثبّت Android Studio مع Android SDK Platform 35.
2) افتح مجلد KharaitShammarAndroid في Android Studio.
3) انتظر انتهاء Gradle Sync.
4) من القائمة Build اختر Build Bundle(s) / APK(s) ثم Build APK(s).
5) ستجد الملف غالباً في app/build/outputs/apk/debug/app-debug.apk

ملاحظات:
- التطبيق يعرض محتوى الويب داخل WebView.
- يلزم اتصال بالإنترنت لتحميل مكتبة Three.js وملفات خامات الأرض من CDN.
- يتطلب جهازاً يدعم WebGL وتسريع الرسوميات للحصول على أفضل أداء.
- هذا المشروع ليس APK مُجمّعاً؛ يجب بناء APK عبر Android Studio أو Gradle مع Android SDK.
