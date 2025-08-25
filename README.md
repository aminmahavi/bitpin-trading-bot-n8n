# 📈 Paper Trading Bot with n8n (RSI Strategy)

این پروژه یک ربات **Paper Trading** برای جفت‌ارز BTC/IRT است که از **n8n** برای اجرای خودکار استراتژی RSI استفاده می‌کند و روی یک VPS لینوکسی 24/7 اجرا می‌شود.

---

## 📌 امکانات
- دریافت داده‌های BTC/IRT به‌صورت زنده از API بیت‌پین
- محاسبه **RSI** با استفاده از داده‌های تاریخی با ذخیره‌سازی در **Static Data**
- تولید سیگنال‌های اتوماتیک: **BUY 🟢** / **SELL 🔴** / **HOLD ⚪**
- اجرای خودکار هر دقیقه با **Cron Trigger**
- ثبت سفارش‌های شبیه‌سازی (**Paper Trading**) بدون ریسک واقعی
- اجرای دائمی با **PM2** حتی پس از ریبوت VPS

---

## ⚙️ نصب و اجرا

### 1. نصب نیازمندی‌ها روی VPS (Ubuntu 20.04/22.04)
```bash
sudo apt update && sudo apt upgrade -y
sudo apt install git nano curl -y
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt install -y nodejs

