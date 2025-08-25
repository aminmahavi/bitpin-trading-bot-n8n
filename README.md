# Paper Trading Bot with n8n

این پروژه شامل یک Workflow در n8n برای انجام Paper Trading ارز دیجیتال (BTC/IRT) با استراتژی RSI است.

## ویژگی‌ها
- دریافت داده‌های بازار از Bitpin API
- محاسبه RSI با داده‌های تاریخی
- تولید سیگنال‌های BUY / SELL / HOLD
- اجرای خودکار هر دقیقه با Cron Trigger
- شبیه‌سازی سفارش‌ها به صورت Paper Trading

## نصب و راه‌اندازی
1. کلون پروژه از GitHub
2. نصب Node.js و n8n
3. ایمپورت Workflow در n8n
4. فعال‌سازی PM2 برای اجرای دائمی

## نگارنده
Mohammadamin
