# مدیریت ۶۰ اکانت — نسخه قابل نصب

این پوشه یک PWA است. برای اینکه Chrome گزینه Install / Add to Home screen را نشان دهد،
فایل‌ها باید از یک آدرس HTTPS اجرا شوند؛ باز کردن مستقیم index.html از حافظه گوشی کافی نیست.

محتویات:
- index.html
- manifest.webmanifest
- sw.js
- icons/

روش پیشنهادی:
1. کل این پوشه را روی یک سرویس میزبانی HTTPS مثل GitHub Pages یا Netlify قرار بده.
2. آدرس HTTPS/index.html را با Chrome گوشی باز کن.
3. از منوی سه‌نقطه گزینه Install app یا Add to Home screen را بزن.
4. آیکن ساخته می‌شود و بعد با زدن آن، برنامه به‌صورت مستقل باز می‌شود.
