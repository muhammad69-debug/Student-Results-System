# Student Results Management System

## تشغيل المشروع
1. فك ضغط الملف.
2. افتح مجلد `Student-Results-System`.
3. افتح `index.html` باستخدام Google Chrome أو Microsoft Edge.
4. يحتاج Bootstrap وخط Cairo إلى اتصال بالإنترنت لتحميلهما من CDN.

## هيكل الملفات
- `index.html`: واجهة المستخدم.
- `css/style.css`: تنسيق الواجهة.
- `js/main.js`: كلاس Student والتحقق من البيانات وإدارة الطلاب ولجنة الرأفة.

## ملاحظات
- تم الحفاظ على بنية التكليف الثاني: `id`, `name`, `grades`, `attendance`، مع `calculateAverage()` و`getGrade()`.
- الدرجات الثلاث ونسبة الحضور يجب أن تكون أرقاماً من 0 إلى 100.
- لجنة الرأفة تختار الطلاب الذين متوسط درجاتهم من 40 إلى 49 (شاملاً)، ثم تضيف 5 درجات إلى متوسط كل منهم.
