# Open Iran Travel Data / داده‌های آزاد گردشگری ایران

## English

### What is this?

An open-source dataset of structured travel data for Iran, covering **43 cities**, **31 provinces**, **7 travel regions**, **29 UNESCO World Heritage Sites**, **55 airports**, and **18 iconic points of interest** — all bilingual (English + Farsi).

This data is maintained by the team building [IranTravel.co](https://irantravel.co), an AI-powered travel platform connecting the world to Iran's guest houses, hotels, tour guides, drivers, and local suppliers.

We believe the **data layer** should be open and community-driven, even as the platform itself is commercial. Everyone benefits when Iran's travel information is accurate, structured, and freely available.

### What's included?

| Dataset | Records | Formats | Description |
|---------|---------|---------|-------------|
| **Regions** | 7 | JSON, CSV | Wikivoyage-based travel regions with province mappings and highlights |
| **Provinces** | 31 | JSON, CSV | All 31 provinces with capitals, population, area, coordinates |
| **Cities** | 43 | JSON, CSV | Major cities with population, elevation, airports, climate data, Wikivoyage travel guides |
| **UNESCO Sites** | 29 | JSON, CSV | All Iranian UNESCO World Heritage Sites with coordinates and descriptions |
| **Airports** | 55 | JSON, CSV | Domestic and international airports with IATA codes |
| **Iconic POIs** | 18 | JSON | Must-visit landmarks and attractions |
| **Accommodations** | 34 | JSON, CSV | Hotels, guesthouses, eco-lodges, and hostels with prices, ratings, and descriptions |
| **Tours** | 30 | JSON, CSV | Walking, food, cultural, desert, photography, and multi-day tours with detailed stop-by-stop itineraries |
| **Domestic Flights** | 12 | JSON, CSV | Major domestic flight routes with airlines, prices, and frequencies |
| **Itineraries** | 3 | JSON, CSV | Sample multi-day trip itineraries (Classic Iran, Desert & Stars, Weekend Isfahan) |
| **City Editorial Guides** | 15 | JSON | In-depth city guides with travel tips, food specialties, day trips, photography tips, and cultural notes |
| **Border Crossings** | 31 | JSON, CSV | All land border crossings with Turkey, Armenia, Azerbaijan, Turkmenistan, Afghanistan, Pakistan, and Iraq — includes visa info, vehicle formalities, tips for cyclists/motorcyclists |
| **Damage Assessment** | — | JSON | Framework for tracking March 2026 bombing damage to infrastructure and heritage sites |

All entries include:
- English name + Farsi name (`name` / `name_fa`)
- Geographic coordinates (lat/lng)
- Structured metadata

### How to contribute

We're actively looking for contributors to help with:

1. **Data corrections** — Fix inaccuracies in city populations, coordinates, or descriptions
2. **New cities/POIs** — Add smaller cities, villages, and lesser-known attractions
3. **Transport data** — Bus routes, train schedules, domestic flight connections, border crossings
4. **Accommodation data** — Guest houses, eco-lodges, traditional houses (اقامتگاه بوم‌گردی)
5. **Tour guide directory** — Verified guides with languages spoken, specialties, and regions covered
6. **Visa requirements** — Nationality-based visa rules and entry requirements
7. **Translations** — Improve Farsi descriptions, add Arabic/Turkish/Kurdish translations
8. **Food & culture** — Traditional dishes, festivals, crafts by region

### Who is this for?

- Travel app developers building Iran-related products
- Researchers studying Iranian tourism, geography, or urban planning
- NLP/AI teams needing bilingual Persian-English structured data
- Bloggers and content creators writing about Iran travel
- Tour operators who want structured destination data
- The Iranian diaspora community building tools for Iran's future

### License

This data is released under **CC BY-SA 4.0** — use it freely, give attribution, share improvements back.

### Contact

- Platform: [irantravel.co](https://irantravel.co)
- GitHub: [@kurosh87](https://github.com/kurosh87)

---

## فارسی

### این پروژه چیست؟

مجموعه‌ای متن‌باز از داده‌های ساختاریافته گردشگری ایران، شامل **۴۳ شهر**، **۳۱ استان**، **۷ منطقه گردشگری**، **۲۹ میراث جهانی یونسکو**، **۵۵ فرودگاه** و **۱۸ جاذبه شاخص** — همگی دوزبانه (فارسی + انگلیسی).

این داده‌ها توسط تیم سازنده [IranTravel.co](https://irantravel.co) نگهداری می‌شود — یک پلتفرم گردشگری مبتنی بر هوش مصنوعی که دنیا را به مهمان‌خانه‌ها، هتل‌ها، راهنمایان گردشگری، رانندگان و تأمین‌کنندگان محلی ایران متصل می‌کند.

ما معتقدیم **لایه داده** باید آزاد و مبتنی بر مشارکت جامعه باشد. وقتی اطلاعات گردشگری ایران دقیق، ساختاریافته و آزادانه در دسترس باشد، همه بهره‌مند می‌شوند.

### داده‌های موجود

| مجموعه داده | تعداد | فرمت | توضیح |
|------------|-------|------|-------|
| **مناطق** | ۷ | JSON, CSV | مناطق گردشگری بر اساس ویکی‌سفر |
| **استان‌ها** | ۳۱ | JSON, CSV | تمام استان‌ها با مرکز، جمعیت و مساحت |
| **شهرها** | ۴۳ | JSON, CSV | شهرهای اصلی با جمعیت، ارتفاع، فرودگاه و اقلیم |
| **میراث یونسکو** | ۲۹ | JSON, CSV | تمام آثار ثبت‌شده یونسکو در ایران |
| **فرودگاه‌ها** | ۵۵ | JSON, CSV | فرودگاه‌های داخلی و بین‌المللی |
| **جاذبه‌های شاخص** | ۱۸ | JSON | دیدنی‌های برتر ایران |
| **اقامتگاه‌ها** | ۳۴ | JSON, CSV | هتل‌ها، مهمان‌خانه‌ها، اقامتگاه‌های بوم‌گردی با قیمت و امتیاز |
| **تورها** | ۳۰ | JSON, CSV | تورهای پیاده‌روی، غذا، فرهنگی، صحرایی و عکاسی با جزئیات ایستگاه‌ها |
| **پروازهای داخلی** | ۱۲ | JSON, CSV | مسیرهای پروازی داخلی اصلی |
| **برنامه‌های سفر** | ۳ | JSON, CSV | برنامه‌های سفر نمونه چندروزه |
| **راهنمای شهرها** | ۱۵ | JSON | راهنمای جامع شهرها با نکات سفر، غذا، عکاسی و فرهنگ |
| **گذرگاه‌های مرزی** | ۳۱ | JSON, CSV | تمام گذرگاه‌های زمینی با اطلاعات ویزا، تشریفات خودرو و نکات دوچرخه‌سواران |
| **ارزیابی خسارات** | — | JSON | چارچوب ردیابی خسارات بمباران اسفند ۱۴۰۴ |

### چگونه مشارکت کنیم؟

ما به دنبال مشارکت‌کنندگان هستیم برای:

1. **اصلاح داده‌ها** — تصحیح جمعیت، مختصات یا توضیحات
2. **شهرها و جاذبه‌های جدید** — افزودن شهرهای کوچکتر و جاذبه‌های کمتر شناخته‌شده
3. **داده‌های حمل‌ونقل** — مسیرهای اتوبوس، قطار، پرواز داخلی، گذرگاه‌های مرزی
4. **اقامتگاه‌ها** — مهمان‌خانه‌ها، اقامتگاه‌های بوم‌گردی، خانه‌های سنتی
5. **راهنمایان گردشگری** — فهرست راهنمایان تأییدشده با زبان‌ها و تخصص‌ها
6. **ویزا** — الزامات ویزا بر اساس ملیت
7. **ترجمه** — بهبود توضیحات فارسی، افزودن عربی/ترکی/کردی
8. **غذا و فرهنگ** — غذاهای سنتی، جشنواره‌ها، صنایع دستی

### این داده‌ها برای چه کسانی مفید است؟

- توسعه‌دهندگان اپلیکیشن‌های گردشگری
- پژوهشگران حوزه گردشگری و جغرافیا
- تیم‌های هوش مصنوعی نیازمند داده‌های دوزبانه فارسی-انگلیسی
- وبلاگ‌نویسان و تولیدکنندگان محتوای سفر
- آژانس‌های گردشگری
- جامعه ایرانیان خارج از کشور

### مجوز

این داده‌ها تحت مجوز **CC BY-SA 4.0** منتشر شده‌اند — آزادانه استفاده کنید، منبع را ذکر کنید، بهبودها را به اشتراک بگذارید.
