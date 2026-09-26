# GameArena (مشروع تعليمي)

مشروع واجهة أمامية (Front-End) تعليمي لبناء صفحة ألعاب حديثة باستخدام **HTML + CSS + Bootstrap + Font Awesome**.

## الهدف من المشروع

- تعلّم بناء صفحة هبوط (Landing Page) كاملة بتصميم احترافي.
- تطبيق مفاهيم الـ Responsive Design على أحجام شاشات مختلفة.
- استخدام مكونات Bootstrap الجاهزة مع تخصيص قوي عبر CSS.

## تشغيل المشروع

1. حمّل المشروع.
2. افتح الملف `index.html` مباشرة في المتصفح.

> لا يحتاج المشروع إلى build tools أو package manager لأنه مشروع static.

## هيكل المشروع

- `index.html`: الهيكل الكامل للصفحة (Navbar, Hero, Games, Team, Contact, Footer).
- `css/style.css`: التخصيصات الأساسية للتصميم، الألوان، الحركات، والتجاوب.
- `css/bootstrap.min.css`: إطار Bootstrap الجاهز.
- `css/all.min.css`: مكتبة Font Awesome للأيقونات.
- `js/bootstrap.bundle.min.js`: JavaScript الخاص بـ Bootstrap (مثل الـ Collapse والـ Carousel).
- `images/`: صور الأقسام المختلفة.
- `fonts/`: الخطوط المحلية المستخدمة داخل التصميم.

## تقسيم المشروع (مع مراجع لكل جزء)

### 1) شريط التنقل (Navbar)

**في المشروع:** روابط تنقل، زر موبايل (toggler)، وأيقونات.

**تحتاج تتعلم:**
- Bootstrap Navbar
- Collapse behavior على الشاشات الصغيرة

**مراجع:**
- https://getbootstrap.com/docs/5.3/components/navbar/
- https://getbootstrap.com/docs/5.3/components/collapse/

---

### 2) قسم Hero (العنوان الرئيسي)

**في المشروع:** عنوان تسويقي، أزرار CTA، وصورة رئيسية مع Badge.

**تحتاج تتعلم:**
- تصميم Hero section
- استخدام Grid System لتقسيم النص والصورة

**مراجع:**
- https://getbootstrap.com/docs/5.3/layout/grid/
- https://developer.mozilla.org/en-US/docs/Web/CSS/background-image
- https://developer.mozilla.org/en-US/docs/Web/CSS/position

---

### 3) قسم الألعاب (Our Games) + Carousel

**في المشروع:** كروت ألعاب داخل Carousel مع تأثيرات Hover مخصّصة.

**تحتاج تتعلم:**
- Bootstrap Carousel
- تأثيرات CSS transitions والتحكم في الطبقات (z-index)

**مراجع:**
- https://getbootstrap.com/docs/5.3/components/carousel/
- https://developer.mozilla.org/en-US/docs/Web/CSS/transition
- https://developer.mozilla.org/en-US/docs/Web/CSS/z-index

---

### 4) قسم What We Do (الخدمات)

**في المشروع:** بطاقات خدمات مع أيقونات وتأثيرات قبل/بعد (`::before`, `::after`).

**تحتاج تتعلم:**
- بطاقات تفاعلية بالـ CSS
- استخدام pseudo-elements في الزخرفة

**مراجع:**
- https://developer.mozilla.org/en-US/docs/Web/CSS/::before
- https://developer.mozilla.org/en-US/docs/Web/CSS/::after
- https://developer.mozilla.org/en-US/docs/Web/CSS/:hover

---

### 5) شريط الشعارات المتحرك (Logo Animation Strip)

**في المشروع:** حركة مستمرة للشعارات يمين/يسار عبر `@keyframes`.

**تحتاج تتعلم:**
- CSS keyframes animations
- فكرة الـ infinite scrolling visual effect

**مراجع:**
- https://developer.mozilla.org/en-US/docs/Web/CSS/@keyframes
- https://developer.mozilla.org/en-US/docs/Web/CSS/animation

---

### 6) قسم الفريق (Our Team)

**في المشروع:** بطاقات أعضاء فريق مع تأثير overlay وgrayscale عند التحويم.

**تحتاج تتعلم:**
- `backdrop-filter` وطبقات overlay
- تحسين عرض الصور داخل البطاقات

**مراجع:**
- https://developer.mozilla.org/en-US/docs/Web/CSS/backdrop-filter
- https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit

---

### 7) قسم التواصل (Contact Us)

**في المشروع:** معلومات تواصل + نموذج إدخال + عناصر form مخصصة.

**تحتاج تتعلم:**
- Bootstrap Forms
- تنسيق حالات focus لعناصر الإدخال

**مراجع:**
- https://getbootstrap.com/docs/5.3/forms/overview/
- https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form
- https://developer.mozilla.org/en-US/docs/Web/CSS/:focus

---

### 8) التذييل (Footer)

**في المشروع:** روابط، أقسام مساعدة، وروابط سياسة وحقوق.

**تحتاج تتعلم:**
- هيكلة footer قابل للتوسع
- تنظيم الروابط في Grid

**مراجع:**
- https://getbootstrap.com/docs/5.3/layout/columns/
- https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/footer

---

### 9) الأيقونات والخطوط

**في المشروع:** استخدام Font Awesome وخطوط محلية عبر `@font-face`.

**تحتاج تتعلم:**
- إدارة أيقونات الويب
- تحميل الخطوط محليًا واستخدامها

**مراجع:**
- https://fontawesome.com/docs/web/setup/host-yourself
- https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face

---

### 10) التوافق مع الشاشات المختلفة (Responsive)

**في المشروع:** Media queries وتدرّج أحجام النصوص والعناصر بين الموبايل والديسكتوب.

**تحتاج تتعلم:**
- Breakpoints في Bootstrap
- كتابة Media Queries فعالة

**مراجع:**
- https://getbootstrap.com/docs/5.3/layout/breakpoints/
- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries

## ملاحظات تعليمية

- المشروع ممتاز للتدرّب على **تحويل تصميم UI إلى صفحة حقيقية**.
- يفضّل تنفيذ كل قسم بشكل منفصل ثم دمج الأقسام تدريجيًا.
- يمكنك البدء بـ HTML أولًا ثم إضافة CSS ثم التأثيرات والحركات.

## تطوير مقترح للمشروع

- ربط نموذج التواصل بمنصة إرسال فعلية (Email API أو Backend).
- إضافة JavaScript مخصص للتفاعلات الإضافية.
- تحسين الأداء عبر ضغط الصور واستخدام lazy loading.
