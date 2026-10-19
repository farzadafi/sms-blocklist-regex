# sms-blocklist-regex

A simple collection of Regular Expressions (Regex) to block spam and promotional SMS messages.

---

### 1. General Promotional SMS Filter (Keywords & Opt-out)
```regex
.*(لغو\s*[:؛]?\s*[1۱][1۱]|[#＃][1۱][*＊]|[*＊][1۱][#＃]|ستاره\s*یک|اسنپ[‌\s]?پی|دیجی[‌\s]?پی|دیجی[‌\s]?کالا|دیجیکلا|تارا|اوانو|سینما\s*همراه|سلام[‌\s]?پی|dgfy\.link|dgpy\.ir|snpy\.ir|tara360\.org|bslm\.ir|zbl\.io|adtrace\.io|3tr\.in|weurl\.co|jo1n\.ir|jzbe\.ir|cinemahamrah\.ir|کد\s*تخفیف|کدتخفیف|کف\s*خرید|[4۴]\s*قسط|قرعه[‌\s]?کشی|برنده|شمش\s*طلا|وام\s*فوری|IP-Static|شتاب در پرداخت).*
