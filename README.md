# 1. سحب المشروع لجهازك والدخول لمجلد المشروع
git clone https://github.com/2dhammahmoud/FEgL.git
cd FEgL

# 2. التأكد من الوقوف على الفرع الرئيسي وسحب أحدث التعديلات
git checkout main
git pull origin main

# 3. إنشاء فرع جديد للجولة المكلف بها والانتقال إليه (عدّل رقم الجولة حسب دورك)
git checkout -b feature/gameweek-2

# 4. بعد إضافة ملفات الماتشات وتشغيل كود الدمج، احفظ التعديلات وارفعها
git add .
git commit -m "feat: add match data and CSV for Game Week 2"
git push -u origin feature/gameweek-2
