<p align="center"> 	<a href="./readme.md"> 	English 	</a> 	/ 	 <a href="./readme-ru.md"> Русский </a>  /  <a href="./readme-zh-cn.md"> 	简体中文 	</a>  /  <a href="./readme-ar.md"> 	اَلْعَرَبِيَّةُ 	</a>  /  <a href="./readme-fa.md"> 	فارسی 	</a> </p>

<div align="center">

<img src="DragonFruit.OnionFruit/Assets/onionfruit.svg" width="100"/>

# OnionFruit™
با حداقل تلاش به شبکه Tor متصل شوید

</div>

## مرور کلی
OnionFruit™ یک دروازه پروکسی Tor است که Tor را راه‌اندازی کرده و تنظیمات سیستم مناسب را به‌روزرسانی می‌کند تا به طیف وسیعی از برنامه‌ها (به‌ویژه مرورگرها) اجازه دهد از شبکه استفاده کنند و امکانات و سفارشی‌سازی‌های مختلفی را از طریق یک رابط کاربری مدرن و تمیز ارائه می‌دهد.

این یک بازنویسی متن‌باز از نسخه قدیمی OnionFruit™ Connect است که در اواخر سال ۲۰۱۶ منتشر شد (با آخرین طراحی عمده در سال ۲۰۲۰).

## وضعیت
در حال حاضر، برنامه هنوز در حال توسعه است اما در وضعیت قابل استفاده‌ای قرار دارد.
از کاربران خواسته می‌شود که برنامه را دانلود کرده و از آن استفاده کنند (یا به‌صورت همزمان یا به‌عنوان جایگزینی برای نسخه قدیمی) و هر گونه باگی که با آن مواجه می‌شوند را گزارش دهند/بازخورد ارائه دهند.

## اجرای OnionFruit™
> [!WARNING]
> این نسخه پیش‌انتشار OnionFruit™ است و ممکن است شامل باگ‌هایی باشد. لطفاً هر گونه مشکلی که با آن مواجه می‌شوید را گزارش دهید.
> آیا نسخه پایدار را می‌خواهید؟ به [صفحه اطلاعات قدیمی](https://github.com/dragonfruitnetwork/onionfruit/tree/onionfruit-connect-legacy-info) مراجعه کنید.

نسخه‌های OnionFruit™ برای پلتفرم‌های زیر ارائه شده است. برای دانلود آخرین نسخه، روی لینک‌ها کلیک کنید:

- [ویندوز ۱۰+ (x64)](https://github.com/dragonfruitnetwork/onionfruit/releases)

**توجه: install.exe نصب‌کننده نسخه قدیمی OnionFruit™ Connect است.**

## ویژگی‌ها
🌍 انتخاب مکان ورودی/خروجی (با به‌روزرسانی‌های منظم پایگاه داده)  
🌉 پشتیبانی از پل‌: webtunnel/snowflake/meek/conjure/plain(vanilla)/scramblesuit/obfs3/obfs4  
🧱 تنظیم پورت‌های مجاز در فایروال‌های محدودکننده  
🌐 صفحات راه‌اندازی سفارشی  
🛡️ نیازی به مجوزهای مدیر برای نصب و استفاده نیست  
🎮 وضعیت اختیاری Discord  
✨ مبتنی بر طراحی Fluent 2 ویندوز ۱۱  
⚖️ کاملاً متن‌باز

## توسعه
شما به SDK .NET 8 و یک IDE (Visual Studio یا JetBrains Rider توصیه می‌شود) نیاز دارید.
اگر در حال کار بر روی UI هستید، با [Avalonia UI](https://avaloniaui.net/) و [ReactiveUI](https://www.reactiveui.net/) آشنا شوید زیرا در همه جا استفاده می‌شوند.

برای شروع، مخزن را کلون کنید و سپس فایل راه‌حل `DragonFruit.OnionFruit.sln` را باز کنید.

```bash
git clone https://github.com/dragonfruitnetwork/onionfruit
cd onionfruit
```

### ساخت از IDE
برای ساخت پروژه، از توابع ساخت/اجرا/اشکال‌زدایی ارائه شده توسط IDE خود استفاده کنید.

### ساخت از CLI
پروژه را با استفاده از `dotnet run` در ترمینالی که انتخاب می‌کنید بسازید و اجرا کنید:

```bash
dotnet run --project DragonFruit.OnionFruit.Windows
```

اگر قصد دارید بر روی یک ویژگی جدید/تغییر بزرگ کار کنید، توصیه می‌شود یک مشکل جدید باز کنید و بیان کنید که چه چیزی را می‌خواهید تغییر دهید تا ایده‌ای از آنچه باید انجام شود/آیا در محدوده است به دست آورید، زیرا نمی‌خواهیم تلاش را هدر دهیم.

## مجوز
> [!NOTE]
> این به وابستگی‌های استفاده شده توسط OnionFruit (مانند Tor) اعمال نمی‌شود زیرا تحت شرایط مختلفی مجوز دارند.

OnionFruit تحت LGPL-3 مجوز دارد. برای اطلاعات بیشتر به [licence.md](licence.md) مراجعه کنید یا از طریق inbox@dragonfruit.network با ما تماس بگیرید.
```

If you need any further assistance or modifications, feel free to ask!