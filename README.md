# قیمت لحظه‌ای تقریبا همه چیز! | Gheymat


کتابخانه‌ای برای دریافت قیمت ارزها و طلا و...
اگر به دردت خورد و اگر دوس داشتی برام یه کافی بخر 😁

https://www.coffeebede.com/mrrobat

  

![Downloads](https://static.pepy.tech/personalized-badge/gheymat?period=total&units=international_system&left_color=black&right_color=green&left_text=Downloads)

## آخرین آپدیت
#### در currency این موارد وجود دارد:
- قیمت دلار | USD
- قیمت پوند | GBP
- قیمت یورو | EUR
- قیمت لیر | TRY
- قیمت درهم امارات | AED
- قیمت یوان چین | CNY
- قیمت روپیه هند | INR
- قیمت کرون سوئد | SEK
- قیمت ریال عمان | OMR

#### در crypto این موارد وجود دارد:
- قیمت بیت‌کوین | BTC
- قیمت اتریوم | ETH
- قیمت دوج کوین | DOGE
- قیمت سولانا | SOL
- قیمت ترون | TRON
- قیمت ریپل | RIPP
- قیمت دش | DASH
- قیمت لایت‌کوین | LITE
- قیمت استلار | STELL
- قیمت تون | TON

#### در metal این موارد وجود دارد:
- قیمت طلا 18 عیار | GOLD18
- قیمت طلا 24 عیار | GOLD24
- قیمت طلای دست‌دوم | USED_GOLD
- قیمت سکه امامی | SEKE_EMAM
- قیمت سکه بهار آزادی | SEKE_BAHAR
- قیمت نقره 999 | SILVER
  
## نصب

```bash
pip install gheymat
```
  

## استفاده

```python
from gheymat.currency import USD

dollar_price = USD(toman=True, beauty=False)
print(dollar_price)
```