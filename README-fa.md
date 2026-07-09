# پیش‌بینی قیمت طلا

یک پروژه یادگیری ماشین برای پیش‌بینی قیمت طلا (GLD) با استفاده از داده‌های مالی تاریخی و الگوریتم Random Forest.

![Gold Price Prediction](https://via.placeholder.com/800x400?text=پیش‌بینی+قیمت+طلا)

## 📋 توضیح پروژه

این پروژه رابطه بین قیمت طلا و سایر شاخص‌های مالی (اس‌اندپی ۵۰۰، نفت خام، نقره و نرخ یورو به دلار) را تحلیل کرده و مدلی با دقت بسیار بالا می‌سازد.

امتیاز R² مدل: ۰٫۹۸۹۶ (دقت بسیار عالی!)

## ✨ ویژگی‌ها

- تحلیل اکتشافی داده (EDA)
- تحلیل همبستگی و نقشه حرارتی
- visualization داده‌ها (توزیع قیمت و مقایسه واقعی با پیش‌بینی)
- مدل یادگیری ماشین (Random Forest Regressor)
- تقسیم داده به train/test

## 📊 مجموعه داده

- فایل: gld_price_data.csv
- دوره زمانی: ۲۰۰۸ تا ۲۰۱۸
- ستون‌ها:
  - Date
  - SPX (شاخص S&P 500)
  - GLD (قیمت طلا) ← متغیر هدف
  - USO (نفت خام)
  - SLV (نقره)
  - EUR/USD

## 🛠️ تکنولوژی‌های استفاده شده

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 🚀 نحوه اجرا

1. مخزن را کلون کنید:
   ```bash
   git clone https://github.com/rezamousavi9/gold-price-prediction.git
   cd gold-price-prediction
