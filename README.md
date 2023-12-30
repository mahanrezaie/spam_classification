# پروژه دسته‌بند اسپم

این پروژه در چهار مرحله اصلی پیاده‌سازی می‌شود: پاکسازی مجموعه داده، تجزیه و تحلیل داده‌های اکتشافی (EDA)، پیش پردازش داده‌ها و ساخت مدل که علاوه بر این، یک برنامه وب برای آزمایش مدل وجود دارد.

## مراحل

### 1. پاک‌سازی مجموعه داده

مجموعه داده یک فرآیند پاک‌سازی را تجربه می‌کند تا با مقادیر گم‌شده مقابله، تکرارها را حذف کند و اطمینان حاصل شود که داده به یک فرمت مناسب برای تحلیل تبدیل شده است.

### 2. تحلیل اکتشافی داده (EDA)

تجزیه و تحلیل داده های اکتشافی برای به دست آوردن بینش در مورد مجموعه داده انجام می شود. این مرحله شامل تجسم و خلاصه کردن داده ها برای شناسایی الگوها و روندهایی است که می تواند مراحل بعدی را مشخص کند.

### 3. پیش‌پردازش داده

پیش‌پردازش داده شامل تبدیل داده خام به یک فرمت مناسب برای آموزش مدل است. این مرحله شامل پیش‌پردازش متن برای پیام‌ها مانند توکن‌بندی و برداشت بردار است.

### 4. ساخت مدل

مدل دسته‌بند اسپم با استفاده از الگوریتم Multinomial Naive Bayes ساخته می‌شود. این مدل بر داده‌های پیش‌پردازش شده برای تشخیص بین پیام‌های اسپم و غیراسپم آموزش می‌بیند.

## برنامه وب برای تست

پروژه شامل یک برنامه وب است که به کاربران این امکان را می‌دهد تا متن پیام‌ها را وارد کنند و تست کنند که آیا به عنوان اسپم دسته‌بندی می‌شوند یا خیر. این برنامه از مدل و بردارساز برای پیش‌بینی‌های زمان واقعی استفاده می‌کند.

## چگونگی استفاده

1. **کلون کردن:**
   ```bash
   git clone https://github.com/mahanrezaie/spam-classifier.git
   cd spam-classifier
2. **نصب پکیج ها:**

برای نصب پکیج‌های مورد نیاز، ابتدا مطمئن شوید که Python نصب شده است. سپس از دستورات زیر استفاده کنید:

```bash
pip install -r requirements.txt

3. **اجرا:**
```bash
streamlit run webapp.py
