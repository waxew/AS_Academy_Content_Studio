# راهنمای ساختار محتوا در AS Academy Content Studio

## هدف فایل

این سند استاندارد نگهداری و سازمان‌دهی محتوای آموزشی در Content Studio را تعریف می‌کند.

Content Studio مالک دانش و محتوای خام آموزشی است و خروجی آن برای MainCourse آماده می‌شود.

## ساختار استاندارد

```text
Domain
 └── Subject
      └── Level
           ├── Fundamentals (مبانی)
           ├── Beginner (مقدماتی)
           ├── Advanced (پیشرفته)
           └── Expert (تخصصی)
                └── Chapter
                     └── Lesson
                          ├── Example
                          ├── Exercise
                          ├── Quiz
                          └── Project
```

## قوانین محتوا

- هر موضوع آموزشی باید چهار سطح استاندارد داشته باشد.
- هر Lesson باید هدف آموزشی مشخص داشته باشد.
- شناسه‌های پایدار محتوا نباید بدون Migration تغییر کنند.
- Content Studio فقط مسئول تولید و مدیریت محتوا است.
- Runtime و اجرای محتوا در Core مدیریت می‌شود.

## چرخه تولید محتوا

```text
Content Studio
      ↓
Validation
      ↓
MainCourse Package
      ↓
Core Runtime
      ↓
MainUi Viewer
```

## استاندارد توضیحات

هر فایل محتوا باید مشخص کند:

- هدف آموزشی
- سطح محتوا
- پیش‌نیازها
- خروجی یادگیری
- تمرین و ارزیابی
