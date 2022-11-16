# وبلاگ انجمن

## چطور می تونم پست بنویسم ؟

برای نوشتن پست در وبلاگ انجمن این قدم ها رو دنبال کن:  

1- این ریپو رو فورک کن.  

2- شاخه خودت رو از شاخه‌ی 
`main` 
جدا کن.
شاخه ای که جدا میکنی خیلی خوبه که همچین اسمی داشته باشه:  
`Add-post-id` 
که 
`id` 
در واقع آیدی گیتهاب ات هستش.  

3- اگه اولین بارت هست که برای وبلاگ پست می نویسی، بیو خودت رو
داخل ریپوی مربوط به نویسندگان اضافه کن.  
[ریپوی نویسندگان][]  

4- بعد برای اضافه کردن پست کافیه یه فایل 
`markdown` 
بسازی که اسمش به صورت قراردادی با تاریخ میلادی آغاز و به عنوان
پست ختم میشه. یعنی این مدلی:  
`2022-02-06-post-title.markdown`  
5- محتوای پستی که می نویسی هم این مدلی میشه:  

<pre><code>
---
layout: post
title: "نام پست"
date: 2022-02-06 11:07:38
categories: category
description: "شرح مختصر"
author: amirihusayn
---
محتوای پست در اینجا و بعد از مشخصات قرار می گیرد.
</code></pre>  

یادت هم نره که آیدی گیتهاب ات رو درست بنویسی.

6- در نهایت تغییرات ات رو
`Commit` 
کن و برای ما 
`Pull request`
بفرست.

## در چه موضوعاتی می تونم پست بنویسم ؟

می تونی تجربیات، منابع آموزشی، نقشه راه، خاطرات انجمن و دانشگاه و حتی
خیلی خفن تر
`README.md`
پروژه باحالت رو به اشتراک بذاری.  

[ریپوی نویسندگان]: https://github.com/ceituut/_authors
[_posts repository]: https://github.com/ceituut/_posts