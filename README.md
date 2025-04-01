# قالب پورتفولیو شخصی مدرن

قالب HTML پورتفولیو شخصی با طراحی مدرن، انیمیشن‌های جذاب و پشتیبانی کامل از RTL.

## ویژگی‌ها

- 🎨 طراحی مدرن با افکت‌های گلس‌مورفیسم
- 🌓 حالت تاریک/روشن
- 📱 کاملاً ریسپانسیو
- 🌐 پشتیبانی از RTL برای زبان فارسی
- ✨ انیمیشن‌های اسکرول حرفه‌ای
- 🔄 اسلایدرهای تعاملی با Swiper.js
- 💼 بخش نمونه کارها با افکت‌های خلاقانه
- 📊 بخش آمار و دستاوردها
- 📝 فرم تماس کاربرپسند
- 🔍 بهینه‌سازی شده برای SEO

## نحوه استفاده

1. **دانلود فایل‌ها**
   - فایل‌های قالب را دانلود کنید
   - آن‌ها را در هاست خود آپلود کنید یا به صورت لوکال اجرا کنید

2. **شخصی‌سازی محتوا**
   - فایل `index.html` را با یک ویرایشگر متن باز کنید
   - اطلاعات شخصی، مهارت‌ها، پروژه‌ها و سایر بخش‌ها را با اطلاعات خود جایگزین کنید
   - تصاویر موجود در پوشه `assets/img` را با تصاویر خود جایگزین کنید

3. **تغییر رنگ‌ها**
   - برای تغییر رنگ اصلی، مقادیر متغیرهای رنگ را در بخش `tailwind.config` در بالای فایل HTML تغییر دهید
   - رنگ اصلی فعلی `#6366F1` (بنفش) است که می‌توانید آن را به رنگ دلخواه خود تغییر دهید

4. **تنظیمات اسلایدر**
   - برای تغییر تنظیمات اسلایدرها، کد مربوط به Swiper.js را در انتهای فایل HTML ویرایش کنید

## ساختار فایل‌ها

```
portfolio/
├── index.html          # فایل اصلی HTML
├── assets/
│   ├── css/            # فایل‌های CSS
│   │   ├── boxicons/   # آیکون‌های Boxicons
│   │   └── bootstrap-icons/ # آیکون‌های Bootstrap
│   ├── img/            # تصاویر
│   │   └── programming/ # تصاویر پروژه‌ها
│   └── js/             # فایل‌های JavaScript (در صورت نیاز)
└── README.md           # این فایل راهنما
```

## تکنولوژی‌های استفاده شده

- HTML5
- Tailwind CSS
- JavaScript
- Swiper.js
- Boxicons
- Bootstrap Icons

## سازگاری با مرورگرها

این قالب با مرورگرهای مدرن زیر سازگار است:
- Chrome (نسخه 60+)
- Firefox (نسخه 60+)
- Safari (نسخه 12+)
- Edge (نسخه 80+)
- Opera (نسخه 50+)

## پشتیبانی

برای هرگونه سوال یا مشکل، می‌توانید از طریق ایمیل زیر با من در تماس باشید:
example@email.com

## لایسنس

این قالب تحت لایسنس [MIT](https://opensource.org/licenses/MIT) منتشر شده است.
```

## 2. بهبود SEO با اضافه کردن متاتگ‌ها

برای بهبود SEO، متاتگ‌های زیر را به بخش `<head>` در فایل index.html اضافه می‌کنیم (بدون تغییر ساختار موجود):

```html
<!-- متاتگ‌های SEO - اضافه شود به بخش head -->
<meta name="description" content="پورتفولیو شخصی محمد یازرلو - توسعه دهنده فرانت‌اند با تخصص در React و Tailwind CSS">
<meta name="keywords" content="پورتفولیو، طراح وب، توسعه دهنده فرانت‌اند، React، JavaScript، Tailwind CSS">
<meta name="author" content="محمد یازرلو">
<meta name="robots" content="index, follow">

<!-- Open Graph / Facebook -->
<meta property="og:type" content="website">
<meta property="og:url" content="https://www.yourwebsite.com/">
<meta property="og:title" content="محمد یازرلو | توسعه دهنده فرانت‌اند">
<meta property="og:description" content="پورتفولیو شخصی محمد یازرلو - توسعه دهنده فرانت‌اند با تخصص در React و Tailwind CSS">
<meta property="og:image" content="./assets/img/programming/1.jpg">

<!-- Twitter -->
<meta property="twitter:card" content="summary_large_image">
<meta property="twitter:url" content="https://www.yourwebsite.com/">
<meta property="twitter:title" content="محمد یازرلو | توسعه دهنده فرانت‌اند">
<meta property="twitter:description" content="پورتفولیو شخصی محمد یازرلو - توسعه دهنده فرانت‌اند با تخصص در React و Tailwind CSS">
<meta property="twitter:image" content="./assets/img/programming/1.jpg">
```

## 3. اضافه کردن انیمیشن لودینگ صفحه

این کد را در ابتدای بدنه (`<body>`) فایل index.html اضافه می‌کنیم:

```html
<!-- انیمیشن لودینگ صفحه - اضافه شود به ابتدای body -->
<div id="page-loader" class="fixed inset-0 z-[9999] flex items-center justify-center bg-primary dark:bg-light-primary">
  <div class="flex flex-col items-center gap-4">
    <div class="w-16 h-16 border-4 border-accent/20 border-t-accent rounded-full animate-spin"></div>
    <div class="text-xl font-bold text-accent relative">
      <span>محمد یازرلو</span>
      <span class="absolute bottom-0 left-0 w-full h-0.5 bg-accent/50 animate-pulse"></span>
    </div>
  </div>
</div>

<script>
  // اسکریپت برای انیمیشن لودینگ - اضافه شود به انتهای body
  window.addEventListener('load', function() {
    setTimeout(function() {
      const loader = document.getElementById('page-loader');
      loader.style.opacity = '0';
      loader.style.visibility = 'hidden';
      setTimeout(() => {
        loader.remove();
      }, 500);
    }, 800);
  });
</script>

<style>
  /* استایل انیمیشن لودینگ - اضافه شود به بخش style موجود */
  #page-loader {
    transition: opacity 0.5s ease, visibility 0.5s ease;
  }
</style>
```

## 4. بهبود متاتگ‌های رنگ تم برای موبایل

این کد را به بخش `<head>` اضافه می‌کنیم:

```html
<!-- متاتگ‌های رنگ تم برای موبایل -->
<meta name="theme-color" content="#0F172A" media="(prefers-color-scheme: dark)">
<meta name="theme-color" content="#F8FAFC" media="(prefers-color-scheme: light)">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
```

## 5. بهبود منوی ناوبری با آیکون‌ها (با حفظ ساختار موجود)

این تغییرات را در بخش منوی ناوبری اعمال می‌کنیم:

```html
<!-- منوی ثابت با آیکون‌ها - جایگزین کد فعلی شود -->
<nav class="fixed right-8 top-1/2 -translate-y-1/2 z-50 hidden md:block">
  <div class="flex flex-col gap-4">
    <a href="#home" class="nav-dot" data-section="home">
      <i class='bx bx-home-alt text-xs'></i>
      <span class="nav-label">خانه</span>
    </a>
    <a href="#about" class="nav-dot" data-section="about">
      <i class='bx bx-user text-xs'></i>
      <span class="nav-label">درباره من</span>
    </a>
    <a href="#stats" class="nav-dot" data-section="stats">
      <i class='bx bx-bar-chart-alt-2 text-xs'></i>
      <span class="nav-label">دستاوردها</span>
    </a>
    <a href="#skills" class="nav-dot" data-section="skills">
      <i class='bx bx-code-alt text-xs'></i>
      <span class="nav-label">مهارتها و پروژه ها</span>
    </a>
    <a href="#contact" class="nav-dot" data-section="contact">
      <i class='bx bx-envelope text-xs'></i>
      <span class="nav-label">تماس با ما</span>
    </a>
    <a href="#social" class="nav-dot" data-section="social">
      <i class='bx bx-link text-xs'></i>
      <span class="nav-label">ارتباط با ما</span>
    </a>
  </div>
</nav>
```

استایل‌های مربوطه را به بخش `<style>` موجود اضافه می‌کنیم:

```css
/* استایل‌های منوی ناوبری با آیکون - اضافه شود به بخش style موجود */
.nav-dot {
  position: relative;
  width: 30px;
  height: 30px;
  background: rgba(255, 255, 255, 0.1);
  border-radius: 50%;
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
  color: rgba(255, 255, 255, 0.6);
}

.nav-dot::before {
  content: '';
  position: absolute;
  inset: -4px;
  border-radius: 50%;
  background: rgba(99, 102, 241, 0.2);
  transform: scale(0);
  transition: transform 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

.nav-dot:hover::before {
  transform: scale(1);
}

.nav-dot:hover {
  color: #6366F1;
}

.nav-dot.active {
  background: rgba(99, 102, 241, 0.2);
  color: #6366F1;
  transform: scale(1.2);
}

.nav-dot.active::before {
  transform: scale(1.5);
}

.dark .nav-dot {
  background: rgba(0, 0, 0, 0.1);
  color: rgba(0, 0, 0, 0.6);
}

.dark .nav-dot:hover,
.dark .nav-dot.active {
  color: #4F46E5;
}

.dark .nav-dot.active {
  background: rgba(79, 70, 229, 0.2);
}
```

## 6. ایجاد فایل sitemap.xml برای SEO بهتر

```bash
touch sitemap.xml
```

محتوای فایل sitemap.xml:

```xml:sitemap.xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>https://www.yourwebsite.com/</loc>
    <lastmod>2023-06-01</lastmod>
    <changefreq>monthly</changefreq>
    <priority>1.0</priority>
  </url>
</urlset>
```

## 7. ایجاد فایل robots.txt

```bash
touch robots.txt
```

محتوای فایل robots.txt:

```text:robots.txt
User-agent: *
Allow: /
Sitemap: https://www.yourwebsite.com/sitemap.xml
