
# Time Series Decomposition (synthetic example)
Time series decomposition using seasonal_decompose with visualization in Python

Time series analysis
این پروژه یک مثال ساده از تحلیل سری زمانی با پایتون است.

ما داده های مصنوعی دما را به مدت 6 ماه تولید می کنیم که شامل سه جزء است:

Trend: افزایش تدریجی دما در طول زمان

Seasonality: نوسانات سینوسی مثل تغییرات دمای هفتگی و یا ماهانه

Noise: تغییرات تصادفی و غیر قابل پیش بینی

سپس داده با استفاده از کتابخانه زیر به اجزای اصلی تجزیه و سپس رسم می شود:


from statsmodels.tsa.seasonal import seasonal_decompose
