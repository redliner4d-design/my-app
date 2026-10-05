# RAVEN Face Studio — Android

این پروژه نسخه اندرویدی برنامه HTML است. برنامه از WebView امن `https://appassets.androidplatform.net/` استفاده می‌کند تا مشکل نیاز به HTTPS/localhost برای دسترسی دوربین در Chrome وجود نداشته باشد.

## ساخت APK
1. Android Studio را نصب کنید.
2. این پوشه را با Open باز کنید.
3. اجازه دهید Gradle وابستگی‌ها را دریافت کند.
4. از Build > Build APK(s) استفاده کنید.
5. APK در `app/build/outputs/apk/debug/app-debug.apk` ساخته می‌شود.

## نکات
- اینترنت برای دریافت MediaPipe Tasks Vision و مدل Face Landmarker در اولین اجرا لازم است.
- برنامه مجوز Camera و در صورت انتخاب ضبط صدا، Microphone را درخواست می‌کند.
- پردازش ویدیو/چهره در WebView انجام می‌شود.
