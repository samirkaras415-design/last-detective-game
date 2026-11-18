# المحقق الأخير — Prototype 0.3 (تحكم لمس)

## الإضافات
- عصا حركة افتراضية على يسار الشاشة.
- زر جري يعمل طوال فترة الضغط.
- زر فحص الأدلة.
- منطقة سحب على يمين الشاشة لتحريك كاميرا الشخص الثالث.
- استمرار دعم WASD والأسهم وShift في محرر Unity.

## التشغيل
1. افتح مشروع Unity 3D، ويفضل Unity 2022.3 LTS.
2. انسخ مجلد Assets من هذه الحزمة إلى مشروعك واسمح بدمج الملفات.
3. انتظر اكتمال Compile.
4. من القائمة اختر `Last Detective > Build First Playable Scene`.
5. اضغط Play لاختبار المشهد في المحرر. استخدم WASD أو الأسهم، وShift للجري.
6. على الهاتف، عصا اللمس والجري والسحب للكاميرا تعمل عند تشغيل المشهد على جهاز يدعم اللمس.

## إخراج APK
1. من Unity Hub ثبّت Android Build Support مع SDK, NDK, OpenJDK.
2. في Unity: File > Build Settings > Android > Switch Platform.
3. Player Settings > Resolution and Presentation: Landscape.
4. Player Settings > Other Settings: فعّل ARM64 واختر IL2CPP.
5. Build لإخراج APK، ثم انقل الملف إلى هاتفك وثبّته بعد السماح بالتثبيت من هذا المصدر.

## حدود النسخة
هذه نسخة Prototype وليست لعبة مكتملة. الشخصية والفيلا مجسمات أولية، وقد تحتاج إعدادات اللمس إلى ضبط حسب أبعاد الشاشة. يلزم بناء APK من Unity على كمبيوتر؛ هذه الحزمة لا تحتوي APK جاهزاً.
