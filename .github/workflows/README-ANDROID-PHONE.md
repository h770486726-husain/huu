# بيانات متكاملة - بناء APK من الهاتف

هذا المشروع Android Native باستخدام Kotlin + Jetpack Compose.

## البناء من الهاتف عبر GitHub Actions

1. أنشئ مستودعًا جديدًا في GitHub باسم `BayanatMutakamila`.
2. اجعله Public لتجنب حدود الدقائق في بعض الحسابات المجانية، ولا تضع أي كلمات مرور أو مفاتيح سرية في المستودع.
3. فك ضغط هذا المشروع على الهاتف.
4. ارفع محتويات مجلد المشروع إلى المستودع، مع الحفاظ على المجلدات، خصوصًا `.github/workflows/build-apk.yml`.
5. بعد الرفع، افتح تبويب **Actions** ثم اختر **Build Android APK** ثم **Run workflow**.
6. بعد نجاح البناء افتح نتيجة التشغيل، ومن قسم **Artifacts** نزّل `BayanatMutakamila-debug-apk`.
7. فك ضغط الـ Artifact وستجد `app-debug.apk` لتثبيته على هاتف Android.

لا يحتاج هذا المسار إلى Android Studio على هاتفك؛ GitHub Actions يقوم بالبناء على خادم سحابي.
