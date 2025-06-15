├── dist/
│ └── css/
│ ├── main.css
│ └── main.css.map
│
├── docs/
│ └── wireframe.md
│
├── images/
│ └── hero-learning.jpg
│
├── sass/
│ ├── abstracts/
│ │ ├── \_functions.scss
│ │ ├── \_mixins.scss
│ │ ├── \_placeholders.scss
│ │ ├── \_variables.scss
│ │ └── index.scss
│ │
│ ├── base/
│ │ ├── \_base.scss
│ │ ├── \_reset.scss
│ │ ├── \_typography.scss
│ │ └── index.scss
│ │
│ ├── components/
│ │ ├── \_buttons.scss
│ │ ├── \_carousel.scss
│ │ ├── \_cover.scss
│ │ ├── \_dropdown.scss
│ │ └── index.scss
│ │
│ ├── layout/
│ │ ├── \_footer.scss
│ │ ├── \_forms.scss
│ │ ├── \_grid.scss
│ │ ├── \_header.scss
│ │ ├── \_navigation.scss
│ │ ├── \_sidebar.scss
│ │ └── index.scss
│ │
│ ├── pages/
│ │ ├── \_contact.scss
│ │ ├── \_home.scss
│ │ └── index.scss
│ │
│ ├── themes/
│ │ ├── \_admin.scss
│ │ ├── \_theme.scss
│ │ └── index.scss
│ │
│ ├── vendors/
│ │ ├── \_bootstrap.scss
│ │ ├── \_jquery-ui.scss
│ │ └── index.scss
│ │
│ └── main.scss
│
├── index.html
├── note
└── package.json

✅ لطباعة كل ملف على حدة مع اسمه (مفيد جدًا لقراءة مريحة ومنظمة):

for file in sass/abstracts/_.scss sass/base/_.scss; do
echo "========== $file =========="
  cat "$file"
echo ""
done

---

✅ مكونات الهيدر (header):

🖥️ على شاشة الديسكتوب (Desktop View):
اللوجو على أقصى اليسار.

الروابط بالمنتصف باتجاه اليمين قليلاً.

زر إنشاء الحساب على أقصى اليمين.

البرجر أيقون مخفي.

📱 على شاشة الموبايل (Mobile View):
اللوجو في مكان مناسب (عادة على اليسار أو المنتصف).

الروابط وزر إنشاء الحساب يختفون.

يظهر البرجر أيقون.

عند النقر على البرجر:

يتحول إلى أيقونة X.

تظهر قائمة عمودية منسدلة تحت الهيدر.

في أسفلها زر إنشاء الحساب.
