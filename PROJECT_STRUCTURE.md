# 📂 Project Structure Guide | دليل هيكل المشروع

<div dir="rtl">

## نظرة عامة
هذا الدليل يشرح هيكل المشروع وتنظيم الملفات والمجلدات.

</div>

---

## 🏗️ Complete Structure | الهيكل الكامل

```
Popal999.github.io/
│
├── 📄 index.html                 # الصفحة الرئيسية / Main homepage
├── 📄 README.md                  # توثيق المشروع / Project documentation
├── 📄 .gitignore                 # ملفات Git المتجاهلة / Git ignore file
│
├── 📁 css/                       # ملفات الأنماط / Stylesheets
│   ├── style.css                 # الأنماط الرئيسية / Main styles
│   └── responsive.css            # الأنماط المتجاوبة / Responsive styles
│
├── 📁 js/                        # ملفات JavaScript
│   ├── main.js                   # الملف الرئيسي / Main JavaScript
│   └── utils.js                  # وظائف مساعدة / Utility functions
│
├── 📁 assets/                    # الموارد / Assets
│   ├── 📁 images/               # الصور / Images
│   │   ├── logo.png
│   │   ├── hero-bg.jpg
│   │   └── og-image.jpg         # صورة مشاركة وسائل التواصل / Social media image
│   │
│   ├── 📁 fonts/                # الخطوط المخصصة / Custom fonts
│   │   └── custom-font.woff2
│   │
│   └── 📁 icons/                # الأيقونات / Icons
│       ├── favicon.ico
│       └── apple-touch-icon.png
│
└── 📁 pages/                     # صفحات إضافية / Additional pages
    ├── about.html                # صفحة من نحن / About page
    └── contact.html              # صفحة التواصل / Contact page
```

---

## 📝 File Descriptions | وصف الملفات

### Root Files | الملفات الجذرية

<div dir="rtl">

#### `index.html`
- الصفحة الرئيسية للموقع
- تحتوي على الهيكل الكامل للصفحة الرئيسية
- مُحسَّنة لمحركات البحث (SEO)

#### `README.md`
- توثيق المشروع الرئيسي
- يحتوي على معلومات التثبيت والاستخدام
- متعدد اللغات (عربي/إنجليزي)

#### `.gitignore`
- قائمة الملفات والمجلدات المُستثناة من Git
- يمنع رفع الملفات غير المرغوبة

</div>

---

### CSS Directory | مجلد الأنماط

<div dir="rtl">

#### `css/style.css`
**الهدف:** الأنماط الرئيسية للموقع

**يحتوي على:**
- متغيرات CSS (الألوان، الخطوط، المسافات)
- أنماط العناصر الأساسية
- Navigation styles
- Hero section
- Buttons
- Services grid
- Contact form
- Footer
- Animations

#### `css/responsive.css`
**الهدف:** التجاوب مع مختلف أحجام الشاشات

**يحتوي على:**
- Tablet breakpoints (768px)
- Mobile breakpoints (480px)
- Large screen optimizations (1200px+)
- Print styles

</div>

---

### JavaScript Directory | مجلد JavaScript

<div dir="rtl">

#### `js/main.js`
**الهدف:** الوظائف الرئيسية للموقع

**الوظائف:**
- `initNavigation()` - قائمة التنقل المحمولة
- `initSmoothScroll()` - التمرير السلس
- `initFormValidation()` - التحقق من النماذج
- `initAnimations()` - الرسوم المتحركة
- `showMessage()` - عرض الرسائل
- Navbar scroll effects

#### `js/utils.js`
**الهدف:** وظائف مساعدة قابلة لإعادة الاستخدام

**الوظائف:**
- `debounce()` - تحديد معدل تنفيذ الوظائف
- `throttle()` - ضمان تنفيذ الوظيفة مرة واحدة في فترة زمنية
- `formatDate()` - تنسيق التواريخ
- `scrollToTop()` - التمرير للأعلى
- `copyToClipboard()` - نسخ النص
- `storage` - تخزين محلي
- `lazyLoadImages()` - تحميل الصور الكسول

</div>

---

### Assets Directory | مجلد الموارد

<div dir="rtl">

#### `assets/images/`
**استخدامات:**
- صور الخلفيات
- الشعارات
- صور المحتوى
- صور وسائل التواصل الاجتماعي (og-image.jpg)

**تنسيقات موصى بها:**
- PNG للشعارات والأيقونات
- JPG للصور الفوتوغرافية
- WebP للأداء الأفضل
- SVG للرسوميات المتجهية

#### `assets/fonts/`
**استخدامات:**
- الخطوط المخصصة للموقع
- تحسين الأداء بالخطوط المحلية

**تنسيقات موصى بها:**
- WOFF2 (الأفضل)
- WOFF (دعم احتياطي)

#### `assets/icons/`
**الملفات المهمة:**
- `favicon.ico` - أيقونة التبويب
- `apple-touch-icon.png` - أيقونة Apple
- أيقونات وسائل التواصل

</div>

---

### Pages Directory | مجلد الصفحات

<div dir="rtl">

#### `pages/about.html`
صفحة "من نحن" - معلومات عن الموقع أو الشركة

#### `pages/contact.html`
صفحة التواصل - نموذج وبيانات الاتصال

</div>

---

## 🎯 Best Practices | أفضل الممارسات

<div dir="rtl">

### تنظيم الملفات
1. ✅ احتفظ بالصور في مجلد `assets/images/`
2. ✅ ضع كل ملفات CSS في مجلد `css/`
3. ✅ ضع كل ملفات JavaScript في مجلد `js/`
4. ✅ استخدم أسماء ملفات واضحة ومعبرة
5. ✅ استخدم الأحرف الصغيرة والشرطات للأسماء

### الأداء
1. ⚡ ضغط الصور قبل الرفع
2. ⚡ استخدم lazy loading للصور
3. ⚡ قلل من ملفات CSS و JavaScript
4. ⚡ استخدم CDN عند الحاجة

### التوافق
1. 📱 اختبر على أجهزة مختلفة
2. 🌐 اختبر على متصفحات مختلفة
3. ♿ تأكد من إمكانية الوصول
4. 🔍 حسّن لمحركات البحث

</div>

---

## 🔄 Updating the Structure | تحديث الهيكل

<div dir="rtl">

### إضافة صفحة جديدة
```bash
# إنشاء ملف HTML جديد
touch pages/new-page.html

# نسخ من قالب موجود
cp index.html pages/new-page.html
```

### إضافة أنماط جديدة
```css
/* في ملف css/style.css */
.new-section {
    /* أنماطك هنا */
}
```

### إضافة وظيفة JavaScript جديدة
```javascript
// في ملف js/main.js أو js/utils.js
function newFunction() {
    // الوظيفة هنا
}
```

</div>

---

## 📚 Additional Resources | موارد إضافية

- [HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [GitHub Pages Guide](https://docs.github.com/en/pages)

---

<div align="center" dir="rtl">

**أي أسئلة؟ افتح issue على GitHub!**

**Questions? Open an issue on GitHub!**

</div>
