<h1 dir="rtl"> الوصف </h1>

<div dir="rtl">

- الملف الخاص بالمهمة الثالثة في مسار الروبوت و الذكاء الاصطناعي  "Robot arm"

- الهدف من هذه المهمة هو تصميم دارة تشغيل لمحركات القاعدة و برمجة الاردوينو للتحكم بها


</div>

<h3 dir="rtl"> ملاحضات </h3>

<div dir="rtl">
  
- تم تصميم الدارة باعتبار محركين فقط و يمكن اضافة او حذف محرك بنفس المبدأ
- تم الاعتماد على الدارة المتكاملة "L293D" ك "motor driver" كونها قادرة على قيادة محركين في نفس الوقت. و لأنها القطعة المتوفرة على برنامج المحاكاة (توجد قطع في السوق تقدم أداء افضل. تدعم حمل أكبر. و طريقة تركيب أسهل)
- تم اختيار مصدر التيار بطارية 9v على سبيل المثال متبوعة بمنظم جهد. و يمكن تبديلها بمصدر اخر
- ملف البرمجة .ino موجود داخل المجلد "base_motors_control"
  
  </div>

cartographer
