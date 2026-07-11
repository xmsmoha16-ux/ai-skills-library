# أفضل ممارسات هندسة البرمجيات

## تصميم الأنظمة
- **Single Responsibility**: كل وحدة (كلاس/دالة) لها سبب واحد للتغيير
- **DRY (Don't Repeat Yourself)**: كرر المنطق، مشي الكود
- **KISS (Keep It Simple)**: الحل الأبسط اللي بيشتغل غالباً أفضل من الحل الذكي المعقد
- **YAGNI**: متبنش تضيف mizaniya مستقبلية محتاجشالها دلوقتي

## دورة حياة المشروع المحترفة
1. **Requirements** — تحديد المشكلة قبل الحل
2. **Design** — المعمارية قبل الكود
3. **Implementation** — كتابة الكود مع Tests
4. **Code Review** — مراجعة من شخص تاني قبل الدمج
5. **CI/CD** — اختبار ونشر أوتوماتيكي
6. **Monitoring** — مراقبة الأداء بعد الإطلاق

## Version Control (Git)
- Commit صغير وواضح الرسالة أفضل من Commit ضخم غامض
- Branch منفصل لكل ميزة (feature branching)
- Pull Request مع مراجعة قبل الدمج في main

## الأمان (Security Basics)
- ممنوع تخزين أي secrets/API keys جوه الكود نفسه — استخدم environment variables
- تحقق دائمًا من المدخلات (input validation) قبل المعالجة
- طبق مبدأ أقل امتياز (Principle of Least Privilege)
