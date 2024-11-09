<p align="center"> 	<a href="./readme.md"> 	English 	</a> 	/ 	 <a href="./readme-ru.md"> Русский </a>  /  <a href="./readme-zh-cn.md"> 	简体中文 	</a>  /  <a href="./readme-ar.md"> 	اَلْعَرَبِيَّةُ 	</a>  /  <a href="./readme-fa.md"> 	فارسی 	</a> </p>

<div align="center">

<img src="DragonFruit.OnionFruit/Assets/onionfruit.svg" width="100"/>

# OnionFruit™
اتصل بشبكة Tor بأقل جهد ممكن

</div>

## نظرة عامة
OnionFruit™ هو بوابة وكيل Tor تقوم بتهيئة Tor وتحديث إعدادات النظام المناسبة للسماح لمجموعة واسعة من التطبيقات باستخدام الشبكة (بشكل أساسي المتصفحات) مع مجموعة من التخصيصات والميزات من خلال واجهة نظيفة وعصرية.

هذا هو إعادة كتابة مفتوحة المصدر للإصدار القديم من OnionFruit™ Connect، الذي تم نشره في أواخر عام 2016 (مع آخر إعادة تصميم رئيسية في عام 2020).

## الحالة
حاليًا، البرنامج لا يزال قيد التطوير ولكنه في حالة قابلة للاستخدام.
يتم تشجيع المستخدمين على تنزيل البرنامج واستخدامه (إما جنبًا إلى جنب أو كبديل للإصدار القديم) والإبلاغ عن أي أخطاء يواجهونها/تقديم ملاحظات.

## تشغيل OnionFruit™
> [!تحذير]
> هذه نسخة ما قبل الإصدار من OnionFruit™ وقد تحتوي على أخطاء. يرجى الإبلاغ عن أي مشاكل تواجهها.
> هل تريد النسخة المستقرة؟ تحقق من [صفحة المعلومات القديمة](https://github.com/dragonfruitnetwork/onionfruit/tree/onionfruit-connect-legacy-info).

تتوفر إصدارات OnionFruit™ للمنصات أدناه. انقر على الروابط لتنزيل أحدث إصدار:

- [Windows 10+ (x64)](https://github.com/dragonfruitnetwork/onionfruit/releases)

**ملاحظة: install.exe هو المثبت للإصدار القديم من OnionFruit™ Connect.**

## الميزات
🌍 اختيار موقع الدخول/الخروج (مع تحديثات قاعدة بيانات منتظمة)  
🌉 دعم الجسور webtunnel/snowflake/meek/conjure/plain(vanilla)/scramblesuit/obfs3/obfs4  
🧱 تعيين المنافذ المسموح بها على جدران الحماية التقييدية  
🌐 صفحات بدء مخصصة  
🛡️ لا حاجة لامتيازات المسؤول للتثبيت والاستخدام  
🎮 حالة Discord اختيارية  
✨ مستند إلى تصميم Fluent 2 في Windows 11  
⚖️ مفتوح المصدر بالكامل

## التطوير
ستحتاج إلى .NET 8 SDK و IDE (يوصى باستخدام Visual Studio أو JetBrains Rider).
إذا كنت تعمل على واجهة المستخدم، فت familiarize yourself with [Avalonia UI](https://avaloniaui.net/) و [ReactiveUI](https://www.reactiveui.net/) حيث يتم استخدامها في كل مكان.

للبدء، قم باستنساخ المستودع ثم افتح ملف الحل `DragonFruit.OnionFruit.sln`.

```bash
git clone https://github.com/dragonfruitnetwork/onionfruit
cd onionfruit
```

### البناء من IDE
لبناء المشروع، استخدم وظائف البناء/التشغيل/التصحيح المقدمة من IDE الخاص بك.

### البناء من CLI
قم ببناء وتشغيل المشروع باستخدام `dotnet run` في محطة اختيارك:

```bash
dotnet run --project DragonFruit.OnionFruit.Windows
```

إذا كنت تنوي العمل على ميزة جديدة/تغيير كبير، يُوصى بفتح قضية جديدة توضح ما ترغب في تغييره للحصول على فكرة عما يجب القيام به/ما إذا كان في النطاق، حيث لا نريد إضاعة الجهد.

## الترخيص
> [!ملاحظة]
> لا ينطبق هذا على التبعيات المستخدمة من قبل OnionFruit (مثل Tor) حيث أنها مرخصة بموجب شروط مختلفة.

OnionFruit مرخص بموجب LGPL-3. راجع [licence.md](licence.md) أو تواصل عبر inbox@dragonfruit.network لمزيد من المعلومات.
```

إذا كان لديك أي نصوص أخرى تحتاج إلى ترجمتها، فلا تتردد في إخباري!