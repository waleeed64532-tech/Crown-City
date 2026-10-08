# مشهد مداهمة FBI — QBCore 1.2.0

[تحميل ملف ZIP للنسخة 1.2 مباشرة من GitHub](https://github.com/waleeed64532-tech/Crown-City/raw/refs/heads/fbi-cinematic-download/fbi-cinematic/FBI-Raid-QBCore-v1.2.zip)

إصلاح اختيار الساحة: مسارات أقصر ومنفصلة، حجم فحص مطابق للمركبات، بحث أوسع في الميناء واتجاه بديل. الكاميرات والبوتات والموسيقى تلقائية، والبداية بأمر `/fbiraid`.

1. أوقف الريسورس القديم وفك الضغط.
2. استبدل مجلد `qb-fbi-cinematic` كاملًا داخل `resources/[local]/`، بما فيه `config.lua` وملف `client/site.lua` الجديد.
3. من كونسول السيرفر نفذ `restart qb-fbi-cinematic`.
4. داخل اللعبة افتح الشات واكتب `/fbiraid` وأنت على قدميك خارج المباني.

لا تنقل إعدادات المواقع والمسارات من النسخة القديمة. ظهور `v1.2 Outdoor apron selected` في F8 يؤكد اختيار الموقع. إذا فشل البحث، انسخ أسطر `Site diagnostic` ورسالة `v1.2 No outdoor apron` للتشخيص.

[دليل التركيب الكامل](INSTALL_AR.md) · [سجل الإصلاحات](CHANGELOG_AR.md)

نجحت 27 مجموعة فحص ومحاكاة وفحص JavaScript وأرشيف ZIP. لم يتم تشغيل الحزمة داخل GTA V / FiveM في بيئة التجهيز، لذلك حركة AI وتوافق خريطة سيرفرك يحتاجان تجربة داخل اللعبة.
