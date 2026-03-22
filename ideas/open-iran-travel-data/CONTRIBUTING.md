# Contributing / مشارکت

## English

### How to add data

1. Fork this repo
2. Edit or add JSON/CSV files in `data/`
3. Submit a PR with a clear description of what you added or changed

### Data format rules

- All entries MUST have both `name` (English) and `name_fa` (Farsi) fields
- Coordinates must be in decimal degrees (WGS84)
- Include sources for any factual claims
- Use UTF-8 encoding for all files

### Damage Assessment contributions

For the March 2026 damage tracker (`damage-assessment-march-2026.json`):

- Follow the `_entry_template` at the bottom of the file
- Mark entries as `confirmed` only with multiple independent sources
- Include source URLs whenever possible
- Satellite imagery links are especially valuable
- If you are on the ground in Iran and have firsthand information, please share when it is safe to do so

### Tour Guide Directory (coming soon)

We are building an open directory of Iranian tour guides. If you are a guide or know verified guides, we will soon have a template for submissions including:

- Name, languages spoken, regions covered
- Specialties (history, nature, food, photography, etc.)
- Contact method (WhatsApp, Telegram, email)
- Verification status

---

## فارسی

### چگونه داده اضافه کنیم

۱. این مخزن را فورک کنید
۲. فایل‌های JSON/CSV را در پوشه `data/` ویرایش یا اضافه کنید
۳. یک Pull Request با توضیح روشن ارسال کنید

### قوانین فرمت داده

- تمام ورودی‌ها باید هم `name` (انگلیسی) و هم `name_fa` (فارسی) داشته باشند
- مختصات باید به درجه اعشاری (WGS84) باشد
- منبع ادعاهای واقعی را ذکر کنید
- از کدگذاری UTF-8 استفاده کنید

### مشارکت در ارزیابی خسارات

برای ردیاب خسارات اسفند ۱۴۰۴ (`damage-assessment-march-2026.json`):

- از الگوی `_entry_template` در انتهای فایل پیروی کنید
- ورودی‌ها را فقط با چندین منبع مستقل به عنوان `confirmed` علامت بزنید
- لینک منابع را حتماً درج کنید
- تصاویر ماهواره‌ای بسیار ارزشمند هستند
- اگر در ایران هستید و اطلاعات دست اول دارید، لطفاً زمانی که امن است به اشتراک بگذارید

### فهرست راهنمایان گردشگری (به زودی)

ما در حال ساخت فهرست آزاد راهنمایان گردشگری ایران هستیم. اگر راهنما هستید یا راهنمایان تأییدشده‌ای می‌شناسید، به زودی الگویی برای ارسال اطلاعات خواهیم داشت شامل:

- نام، زبان‌ها، مناطق تحت پوشش
- تخصص‌ها (تاریخ، طبیعت، غذا، عکاسی و غیره)
- روش تماس (واتساپ، تلگرام، ایمیل)
- وضعیت تأیید
