AS Trade - Android Studio source project

طريقة بناء APK من الموبايل باستخدام GitHub Actions:
1) أنشئ حسابًا مجانيًا على github.com وسجّل الدخول.
2) أنشئ Repository جديدًا باسم AS-Trade، واجعله Public أو Private.
3) ارفع محتويات هذا المجلد إلى جذر المستودع (فك ضغط ZIP أولًا؛ لا ترفع ملف ZIP وحده).
4) افتح تبويب Actions ثم اختر Build AS Trade APK ثم Run workflow.
5) بعد نجاح التشغيل، افتح التشغيل المكتمل وانزل إلى Artifacts وحمّل AS-Trade-debug-APK.
6) فك ضغط الملف الذي تم تنزيله، ثم ثبّت app-debug.apk. قد يطلب أندرويد السماح بالتثبيت من هذا المصدر.

ملاحظات:
- هذا مشروع Android Studio وليس ملف Sketchware Pro قابلًا للاستيراد.
- APK الناتج Debug للتجربة، وليس إصدارًا جاهزًا للنشر على Google Play.
- يتطلب البناء اتصال إنترنت، وقد تختلف أسماء القوائم قليلًا في واجهة GitHub على الموبايل.
- يفتح التطبيق الموقع https://abusaid.voar44.workers.dev/
