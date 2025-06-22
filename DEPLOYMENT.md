# دليل نشر غرفة التركيز على GitHub Pages

## خطوات النشر

### 1. إنشاء مستودع جديد على GitHub
1. اذهب إلى [GitHub](https://github.com)
2. انقر على "New repository"
3. اسم المستودع: `focus-room`
4. اجعله عام (Public)
5. أضف وصف: "غرفة تركيز - تطبيق ويب للتركيز والإنتاجية"

### 2. رفع الملفات
```bash
git clone https://github.com/yourusername/focus-room.git
cd focus-room
```

ثم انسخ الملفات التالية إلى المجلد:
- `index.html` (الملف الرئيسي)
- `README.md` (دليل المشروع)
- `package.json` (معلومات المشروع)
- `.gitignore` (ملفات التجاهل)

```bash
git add .
git commit -m "إضافة تطبيق غرفة التركيز"
git push origin main
```

### 3. تفعيل GitHub Pages
1. اذهب إلى إعدادات المستودع (Settings)
2. انتقل إلى قسم "Pages"
3. اختر "Deploy from a branch"
4. اختر branch: `main`
5. اختر folder: `/ (root)`
6. انقر "Save"

### 4. الوصول للموقع
سيكون الموقع متاح على:
`https://yourusername.github.io/focus-room/`

## الملفات المطلوبة

- **index.html**: الملف الرئيسي الذي يحتوي على كامل التطبيق
- **README.md**: وثائق المشروع والاستخدام
- **package.json**: معلومات المشروع والتبعيات
- **.gitignore**: ملفات التجاهل لـ Git

## المميزات التقنية

- تطبيق صفحة واحدة (SPA)
- لا يحتاج خادم
- يعمل بالكامل في المتصفح
- متوافق مع GitHub Pages
- تصميم متجاوب
- دعم كامل للغة العربية

## التخصيص

يمكنك تخصيص:
- الألوان في CSS Variables
- الرسائل التشجيعية
- قائمة الموسيقى
- أوقات البومودورو الافتراضية

## الدعم

للمساعدة أو الإبلاغ عن مشاكل، يرجى إنشاء Issue في المستودع.