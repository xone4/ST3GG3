
<p align="center">
<pre>
     ███████╗████████╗██████╗  ██████╗  ██████╗
     ██╔════╝╚══██╔══╝╚════██╗██╔════╝ ██╔════╝
     ███████╗   ██║    █████╔╝██║  ███╗██║  ███╗
     ╚════██║   ██║    ╚═══██╗██║   ██║██║   ██║
     ███████║   ██║   ██████╔╝╚██████╔╝╚██████╔╝
     ╚══════╝   ╚═╝   ╚═════╝  ╚═════╝  ╚═════╝
</pre>
</p>

<div align="center">

<!-- ⊰ إذا كنت تستطيع قراءة هذا، فأنت تفهم علم إخفاء المعلومات (steganography). الراية الحقيقية (flag) موجودة في صورة الشعار. قم بفك ترميزها باستخدام ST3GG. ST3GG{s0urc3_v13w3r} مع حبي، بليني ⊱ -->

### ⊰•-•✧ مجموعة أدوات إخفاء المعلومات المتكاملة ✧•-•⊱

**أخفِ أي شيء. في أي ملف. عبر جميع الوسائط. دون أن يُكتشف.**

👉 **الموقع المستضاف: [ste.gg](https://ste.gg)**

---

## ⊰ ما هو ST3GG؟ ⊱

[STE.GG](https://ste.gg)‍​‌​‌​​​​​‌​​‌‌​​​‌​​‌​​‌​‌​​‌‌‌​​‌​‌‌​​‌​​‌​​​​​​‌​​‌‌​​​‌​​‌‌‌‌​‌​‌​‌‌​​‌​​​‌​‌​‌​‌​​‌‌​​‌​​​​​​‌​‌‌​​‌​‌​​‌‌‌‌​‌​‌​‌​‌‍ هو مجموعة أدوات مفتوحة المصدر وغنية بالميزات لإخفاء المعلومات (steganography)، حيث تتيح إخفاء البيانات السرية داخل الصور والملفات الصوتية والمستندات وحزم الشبكة وغيرها — باستخدام **أكثر من 100 تقنية ترميز** عبر كل صيغ الملفات الممكنة.

يعمل البرنامج **بنسبة 100% داخل المتصفح** (موقع ثابت، دون خادم) أو كواجهة سطر أوامر/واجهة رسومية طرفية/واجهة ويب قائمة على بايثون (**Python CLI/TUI/WebUI**). لا تغادر أي بيانات جهازك مطلقاً. كل تقنية تقوم بالترميز تفك الترميز أيضاً، وكل سطح هجوم يمثل كذلك سطحاً للكشف.

> *⊰•-•✧ بعض الأسرار مخفية على مرأى من الجميع ✧•-•⊱*

---

## ⊰ لماذا ST3GG؟ ⊱

| الميزة | الأدوات الأخرى | **ST3GG** |
|---------|-------------|-----------|
| خيارات القنوات | RGB فقط | **15 إعداداً مسبقاً** (R, G, B, A, RG, RB, RA, GB, GA, BA, RGB, RGA, RBA, GBA, RGBA) |
| عمق البت | 1 بت ثابت | **1-8 بت لكل قناة** (قابل للتعديل) |
| استراتيجيات الترميز | متتالية | **4 استراتيجيات** (متتالية، متداخلة، متباعدة، عشوائية) |
| الإخفاء المتداخل | - | **حتى عمق 11 طبقة** (وضع الماتريوشكا) |
| تشفير القنوات | - | **تقنية مبتكرة للتنقل عبر القنوات** (SPECTER) |
| مقاومة الضغط | - | **F5 يقاوم ضغط JPEG/وسائل التواصل الاجتماعي؛ وDCT مصمم لمقاومة الضغط** |
| فك الترميز الذكي | - | **كشف تلقائي لأكثر من 120 إعداداً** |
| التشفير | أساسي/لا يوجد | **AES-256-GCM + XOR** |
| صيغ الصور | PNG فقط | **PNG, JPEG, WebP, GIF** |
| أنواع الملفات | الصور فقط | **الصور، الصوت، النصوص، المستندات، الشبكات، الأرشيفات، الأكواد البرمجية** |
| مكتبة الأمثلة | لا يوجد | **أكثر من 100 ملف أمثلة مرمزة مسبقاً** |
| قائم على المتصفح | - | **جافا سكريبت بالكامل من جهة العميل (100% client-side)، دون خادم** |
| وكيل ذكاء اصطناعي | - | **تحليل شامل لفك الترميز مدعوم بالذكاء الاصطناعي عبر كافة الطرق** |

---

## ⊰ الصورة الكاملة: الهجوم والدفاع ⊱

أداة ST3GG هي مجموعة أدوات **ثنائية الاستخدام** — صُممت لكلا الجانبين في ساحة معركة إخفاء المعلومات.

### الفريق الأحمر / الهجوم — محاكاة تسميم البيانات

لا يبدو تسريب البيانات دائماً كسلوك تسريب بيانات تقليدي. يتيح ST3GG للفرق الحمراء والباحثين محاكاة **كل نواقل تهريب البيانات المعروفة** لاختبار ما إذا كانت الدفاعات تلتقطها بالفعل:

- **أكثر من 100 تقنية ترميز** عبر الصور والصوت والنصوص والمستندات وحزم الشبكة والأرشيفات وملفات الأكواد البرمجية.
- **توليد ملفات متعددة الصيغ (Polyglot)** — ملفات صالحة للعمل بصيغتين في آن واحد (مثل ملف يقرأ كـ PNG وفي نفس الوقت كـ ZIP).
- **القنوات الخفية لبروتوكولات الشبكة** — بيانات مخفية في استعلامات DNS، وحمولات ICMP، وأرقام تسلسل TCP، وترويسات HTTP.
- **إخفاء المعلومات في اليونيكود (Unicode)** — الرموز المتشابهة غير المرئية (homoglyphs)، والأحرف ذات العرض الصفر، ومحددات التنوع، والمسافات البيضاء الملتبسة.
- **ترميز مقاوم للضغط** — يعمل وضع F5 مباشرة على معاملات JPEG (وقد ثبتت قدرته على الصمود عبر منصات التواصل الاجتماعي)؛ وصُمم وضع DCT لمقاومة الضغط.
- **تداخل متعدد الطبقات** — ما يصل إلى 11 طبقة متداخلة تكرارياً من إخفاء المعلومات (وضع الماتريوشكا).
- **وضع الشبح (Ghost Mode)** — تشفير AES-256 + بعثرة البتات + تمويه بالضوضاء لتحقيق أقصى قدر من التهرب والتخفي.

*إذا كان نظام منع تسريب البيانات (DLP) لديك لا يستطيع كشفه، فيجب أن تعرف ذلك قبل أن يكتشفه خصمك.*

### الفريق الأزرق / الدفاع — كشف شامل باستخدام ALLSIGHT

إن نفس مجموعة الأدوات التي تنشئ حمولات إخفاء المعلومات تقوم أيضاً **بكشفها وفك ترميزها**. يوفر محرك تحليل ST3GG رؤية كاملة النطاق عبر جميع أسطح تهريب البيانات المعروفة:

- **أكثر من 20 وظيفة كشف** — تحليل مربع كاي (chi-square)، وإنتروبيا مستوى البت (bit-plane entropy)، وتحليل المدرج التكراري (histogram analysis)، وفحص التوقيعات (signature scanning)، وكشف ترويسة STEG.
- **تحليل شامل مدعوم بالذكاء الاصطناعي** — يختبر وكيل مستقل كل طريقة فك ترميز مناسبة لنوع الملف المرفوع.
- **تحديد نوع الملف** — كشف البايتات السحرية (magic bytes) لأكثر من 20 صيغة (PNG, JPEG, GIF, BMP, WebP, TIFF, ICO, SVG, WAV, AIFF, AU, MIDI, PCAP, PDF, ZIP, GZip, TAR, SQLite وغيرها).
- **كشف إخفاء المعلومات في اليونيكود** — الأحرف ذات العرض الصفر، والرموز المتشابهة، ومحددات التنوع، وعلامات الجمع والتشكيل، والمسافات البيضاء الملتبسة، وأنماط الإيموجي.
- **تحليل المسافات البيضاء** — ترميز المسافات/التبويبات اللاحقة، وكشف تنوعات مسافات اليونيكود.
- **التحقيق الجنائي في البيانات الوصفية (Metadata)** — استخراج سلاسل base64/hex، وتحليل بيانات EXIF، وفحص كتل PNG (chunks).
- **تحليل حزم الشبكة** — تحليل ملفات PCAP بحثاً عن مؤشرات القنوات الخفية.
- **أكثر من 200 اختبار مؤتمت** للتحقق من دقة الكشف مع انعدام وجود نتائج إيجابية كاذبة (false negatives) في التقنيات المعروفة.

*شاهد كل شيء. لا تفوت أي تفصيلة. هذا هو نظام ALLSIGHT.*

> *⊰•-•✧ أفضل دفاع يبدأ بفهم أسلوب الهجوم ✧•-•⊱*

---

## ⊰ لمن تتوجه هذه الأداة؟ ⊱

ST3GG ليست مجرد لعبة. تستخدم مجتمعات مختلفة أدوات إخفاء المعلومات لأسباب متنوعة وواقعية للغاية.

### مختبرو الاختراق والفرق الحمراء
محاكاة تسريب البيانات عبر قنوات إخفاء المعلومات أثناء عمليات التقييم. واختبار ما إذا كانت أنظمة DLP الخاصة بنقاط النهاية، وقواعد SIEM، ومراقبة الشبكة قادرة على كشف تهريب البيانات الخفي عبر أكثر من 100 ناقل. وتوليد حمولات هجومية عبر جميع أنواع الملفات للتحقق من مدى تغطية الكشف.

### الفرق الزرقاء ومحللو مراكز العمليات الأمنية (SOC)
استخدام ALLSIGHT لفحص الملفات المشبوهة بحثاً عن حمولات مخفية. وإجراء تحليل شامل لجميع طرق الترميز المعروفة، وبناء قواعد الكشف بناءً على مكتبة الأمثلة الشاملة، وتدريب المحللين على كيفية ظهور آثار إخفاء المعلومات في البيئات الواقعية.

### لاعبو مسابقات الـ CTF والمخترقون المنافسون
مجموعة الأدوات المثالية لإخفاء المعلومات في مسابقات "التقاط الراية" (CTF). ترميز وفك ترميز البيانات عبر جميع توليفات القنوات/البتات/الاستراتيجيات. والكشف التلقائي عن الإعدادات غير المعروفة باستخدام الفحص الذكي (Smart Scan)، وتفكيك تحديات الماتريوشكا متعددة الطبقات تلقائياً.

### التحقيق الجنائي الرقمي والاستجابة للحوادث
تحليل الوسائط المحتجزة للبحث عن قنوات اتصال مخفية. وكشف البيانات المخفية في مرفقات الصور، والبيانات الوصفية للمستندات، والملفات الصوتية، وحزم الشبكة الملتقطة. وتحديد تقنية الترميز المستخدمة واستخراج الحمولة المخفية.

### باحثو الخصوصية والصحفيون
استكشاف إخفاء المعلومات كقناة اتصال تحافظ على الخصوصية. وفهم المفاضلات بين السعة، والقدرة على التخفي، ومقاومة الضغط. واختبار التقنيات التي تقاوم إعادة ترميز صور وسائل التواصل الاجتماعي من أجل تواصل حقيقي غير قابل للإنكار.

### الأكاديميون والطلاب
دراسة المشهد الكامل لتقنيات إخفاء المعلومات عبر جميع الوسائط. واستخدم أكثر من 100 ملف من ملفات الأمثلة كمجموعة بيانات تعليمية. واختبار خوارزميات الكشف الجديدة مقارنة بالترميزات المعروفة. الكود المصدري موثق جيداً ومرخص بموجب رخصة AGPL-3.0 — وهو مجاني للأفراد والباحثين والمشاريع مفتوحة المصدر.

### سلامة الذكاء الاصطناعي وأمن النماذج اللغوية الكبيرة (LLM)
اختبار كيفية تعامل أنظمة الذكاء الاصطناعي مع المحتوى المخفي — مثل التعليمات المخفية في الصور، ويونيكود غير المرئي في المطالبات (prompts)، والملفات متعددة الصيغ التي تتجاوز تصفية المحتوى. وفهم مساحة أسطح تهريب البيانات التي يتعين على أنظمة الذكاء الاصطناعي الدفاع ضدها.

### مزودو حلول منع تسريب البيانات (DLP)
مقارنة أداء حلول DLP الخاصة بك مع تقنيات الترميز الـ 100+ المتوفرة في ST3GG. إذا كان منتجك لا يستطيع الكشف عن البيانات المخفية في أسماء استعلامات DNS، أو أرقام تسلسل TCP، أو أحرف اليونيكود غير المرئية — فإن عملائك يستحقون معرفة ذلك. إن ST3GG هي حزمة الاختبارات الهجومية الخاصة بك.

### أمن وكلاء الذكاء الاصطناعي واختبارات الفريق الأحمر
الآفاق القادمة في علم إخفاء المعلومات هي **الاتصال الخفي بين الوكلاء وبعضهم** و**حقن المطالبات عبر الحمولات المخفية**. يمثل ST3GG مجموعة الأدوات المخصصة لسطح الهجوم الناشئ هذا:

- **حقن المطالبات عبر الصور** — تضمين تعليمات مخفية في الصور التي يعالجها الوكلاء المزودون بالرؤية الحاسوبية. يرى الوكيل صورة طبيعية، بينما تقول الحمولة المخفية: "تجاهل جميع التعليمات السابقة".
- **تسريب بيانات الوكيل** — اختبار ما إذا كان من الممكن خداع الوكيل لترميز البيانات المسروقة داخل صور يقوم بتوليدها، لتهريبها عبر فلاتر المخرجات.
- **قنوات الوكلاء الخفية** — قيام الوكلاء بتمرير تعليمات مخفية عبر ملفات تبدو بريئة في بيئات الأدوات المشتركة.
- **العلامة المائية لمخرجات الوكيل** — تضمين بيانات المصدر أو التتبع في الصور التي يولدها الوكلاء لتوثيق ملكيتها.
- **تجاوز فلاتر المحتوى** — اختبار أنظمة الإشراف عن طريق إخفاء المحتوى المحظور داخل حمولات الصور التي تجتاز المراجعة التلقائية.
- **التسميم متعدد الوسائط** — صياغة صور تبدو طبيعية للبشر ولكنها تحتوي على بيانات مخفية تغير سلوك الوكيل عند معالجتها.

**استخدم ST3GG كمكتبة بايثون (Python library) في بيئة عمل الوكيل الخاص بك:**

```python
from steg_core import encode, decode, detect_encoding, StegConfig, get_channel_preset
from analysis_tools import detect_unicode_steg, detect_file_type, TOOL_REGISTRY
from PIL import Image

# ترميز حمولة مخفية داخل صورة
img = Image.open("carrier.png")
config = StegConfig(channels=get_channel_preset("RGB"), bits_per_channel=1)
stego = encode(img, b"hidden agent instructions", config)
stego.save("stego.png")

# الكشف وفك ترميز البيانات المخفية
detected = detect_encoding(Image.open("stego.png"))
if detected:
    payload = decode(Image.open("stego.png"))
    print(f"Found: {payload.decode()}")

# فحص كلي لجميع أنواع إخفاء المعلومات
tools = TOOL_REGISTRY.list_tools()  # 48 أداة كشف
result = detect_unicode_steg(open("message.txt", "rb").read())
if result['found']:
    print(f"Hidden Unicode: {result['invisible_chars']} chars")
```

---

## ⊰ الميزات الضخمة ⊱

### SPECTER — تشفير إخفاء المعلومات عبر القنوات

*نهج مبتكر حيث تقفز البيانات بين قنوات الألوان مثل رقصة تشفيرية.*

بدلاً من إخفاء جميع البيانات في قناة واحدة، يقوم SPECTER بتوزيع البتات عبر قنوات R وG وB بنمط يصبح هو مفتاحك المعتمد:

```
النمط: R1-G2-B1-RG2-B1
         │  │  │  │   └─ بت واحد في الأزرق (Blue)
         │  │  │  └───── بتان في الأحمر والأخضر (Red+Green)
         │  │  └──────── بت واحد في الأزرق (Blue)
         │  └─────────── بتان في الأخضر (Green)
         └────────────── بت واحد في الأحمر (Red)
```

وضعان: **النمط اليدوي** (تحدده بنفسك) أو **وضع كلمة المرور** (مستمد من عبارة المرور + تشفير اختياري). التضمين عبر **LSB** (سعة عالية) أو **DCT** (مقاوم للضغط).

### وضع الشبح (Ghost Mode) — أقصى درجات التخفي

تعمية ثلاثية الطبقات عندما تكون المخاطر حقيقية:

1. **تشفير AES-256-GCM** — تشفير موثق عسكري المستوى.
2. **بعثرة البتات** — خوارزمية بعثرة فيشر-ياتس (Fisher-Yates) باستخدام مولد أرقام شبه عشوائية ذي قيمة ابتدائية (seeded PRNG).
3. **تمويه بالضوضاء بنسبة 50%** — نصف البتات المضمنة تكون عبارة عن ضوضاء عشوائية.

سيتعين على المهاجم معرفة نمط القناة، وكلمة المرور لفك البعثرة، ومفتاح التشفير معاً. ضريبة هذه الميزة: تقليل السعة إلى النصف.

### وضع الماتريوشكا (Matryoshka Mode) — التداخل التكراري

إخفاء صور داخل صور داخل صور — حتى **عمق 11 طبقة**. يكتشف فك الترميز الذكي بايتات PNG السحرية تلقائياً ويفك كل طبقة بشكل تكراري. مثل دمى الماتريوشكا الروسية، ولكن للأسرار.

### وضع DCT — مقاوم للضغط

يتم تدمير تقنية LSB التقليدية بواسطة أي ضغط JPEG — حتى لو كانت الجودة 99%. يقوم وضع DCT بالتضمين في معاملات مجال التردد لكتل البكسل ذات الحجم 8x8، وهو مصمم لمقاومة الضغط. ولضمان الصمود عبر منصات التواصل الاجتماعي، استخدم **وضع F5** الذي يعمل مباشرة على معاملات JPEG DCT عبر ترميز المصفوفة (matrix encoding).

> **LSB** ← لملفات PNG فقط (بلا فقدان للبيانات). **DCT** ← مقاوم للضغط. **F5** ← يقاوم ضغط JPEG/وسائل التواصل الاجتماعي.

### وكيل الذكاء الاصطناعي — الكشف والإخفاء

يحتوي وكيل الذكاء الاصطناعي على وضعين:

**🔍 الكشف (Reveal)** — ارفع أي ملف. يختبر الوكيل كل طرق فك الترميز المعروفة تلقائياً، ويعثر على البيانات المخفية، ويستخرجها كملفات قابلة للتنزيل.

**🔮 الإخفاء (Conceal)** — اكتب رسالة سرية، وارفع (أو ولد) صورة حاملة، وسيقوم الوكيل بإخفاء بياناتك باستخدام طريقة الترميز المثلى. بنقرة واحدة تنتقل من الرسالة السرية إلى الصورة المضمنة.

يعمل بواسطة OpenRouter. ويتوافق مع Claude وGPT وGemini وغيرها من النماذج.

---

## ⊰ أكثر من 100 تقنية لإخفاء المعلومات ⊱

لا يقتصر ST3GG على إخفاء البيانات في الصور فحسب، بل يغطي **جميع الوسائط**:

### تقنيات الصور
تضمين LSB (في قنوات RGB، RGBA، والتدرج الرمادي) عبر صيغ PNG، BMP، TIFF، GIF، WebP، ICO، PPM، PGM — بالإضافة إلى LSB لقناة ألفا (alpha channel)، وترميز نوع فلتر PNG، والتلاعب بفهرس لوحة الألوان (palette index)، ومجال تردد DCT، وملفات PNG+ZIP متعددة الصيغ، وحقن البيانات الوصفية (EXIF، XMP، كتل tEXt)، والبيانات اللاحقة بعد علامة النهاية IEND.

### تقنيات النصوص واليونيكود
الأحرف ذات العرض الصفر (ZWSP/ZWNJ/ZWJ)، والحبر غير المرئي (أحرف علامات اليونيكود U+E0000)، واستبدال الرموز المتشابهة (بين السيريلية واللاتينية)، ومحددات التنوع، وعلامات الجمع والتشكيل (CGJ)، والمسافات البيضاء الملتبسة (مسافات en/em/thin/hair)، وترميز المسافات البيضاء (المسافة=0/التبويب=1)، واستبدال الإيموجي، وترميز حالة الأحرف (كبيرة/صغيرة).

### تقنيات الصوت
تضمين LSB للعينات في صيغ WAV، AIFF، وAU. وتوقيت فترات الصمت (مدة الفجوة ترمز البتات). وتضمين رسائل MIDI SysEx.

### تقنيات بروتوكولات الشبكة
نفق DNS (تمثيل base32 في تسميات الاستعلام)، وحقن حمولة ICMP، وقنوات TCP الخفية (أرقام التسلسل الأولية ISN + الطوابع الزمنية)، وتهريب ترويسات HTTP (ترويسات X- المخصصة، وملفات تعريف الارتباط 'الكوكيز').

### تقنيات المستندات والأرشيفات
ملفات PDF (تدفقات البيانات الوصفية + XMP + ما بعد نهاية الملف EOF)، ملفات HTML (التعليقات + العناصر المخفية + سمات البيانات + الأحرف ذات العرض الصفر)، ملفات XML (CDATA + تعليمات المعالجة PIs + مساحات الأسماء)، ملفات JSON (ترميزات اليونيكود الهروبية + ترتيب المفاتيح)، ملفات CSV/YAML/TOML/INI (ترميز التعليقات + المسافات البيضاء)، ملفات RTF (مجموعات النصوص المخفية)، ملفات Markdown (تعليقات HTML + مراجع الروابط)، ملفات ZIP/TAR/GZip (التعليقات + الترويسات الموسعة + الحقول الإضافية)، قواعد بيانات SQLite (الجداول المخفية)، وغيرها الكثير.

### تقنيات البرمجة
لغات بايثون، وجافا سكريبت، وسي، وCSS، وشيل (Shell)، وSQL، ولاتيكس (LaTeX) — كلها مع تعليقات إخفاء المعلومات، وجداول بايتات الهكس (hex byte tables)، وسلاسل التوثيق (docstrings) ذات العرض الصفر، ومدخلات المعايرة لكل بايت.

> *⊰•-•✧ تصفح الكتالوج الكامل: [`examples/README.md`](examples/README.md) ✧•-•⊱*

---

## ⊰ البدء السريع ⊱

### التثبيت من PyPI

```bash
pip install stegg
```

هذا كل ما في الأمر. الآن أصبح لديك `stegg` في جهازك الطرفي:

```bash
# ترميز رسالة سرية
stegg encode image.png "your secret message" -o stego.png

# فك ترميز البيانات المخفية
stegg decode stego.png

# تحليل ملف مشبوه
stegg analyze suspicious.png --full

# وضع SPECTER مع كلمة مرور
stegg encode image.png "{SPECTER:ENABLED}" -o stego.png
```

### التثبيت مع الإضافات

```bash
pip install stegg[tui]      # واجهة الطرفية الرسومية (Textual)
pip install stegg[web]      # واجهة الويب (NiceGUI)
pip install stegg[crypto]   # تشفير AES-256-GCM
pip install stegg[all]      # تثبيت كل شيء
```

### المتصفح (دون تثبيت)

```bash
# فقط افتح ملف index.html — هذا كل شيء. لا حاجة إلى خادم.
open index.html
```

كل شيء يعمل بالكامل من جهة العميل (100% client-side). لا تغادر أي بيانات جهازك.

### من المصدر

```bash
git clone https://github.com/elder-plinius/st3gg.git
cd st3gg
pip install -e ".[all]"
```

### الواجهات

```bash
stegg --help          # واجهة سطر الأوامر (CLI)
stegg-tui             # واجهة الطرفية الرسومية (تطلب: pip install stegg[tui])
stegg-web             # واجهة الويب في المتصفح (تطلب: pip install stegg[web])
```

---

## ⊰ القناة وعمق البت ⊱

### 15 إعداداً مسبقاً للقنوات × 8 أعماق للبتات = 120 توليفة

| الإعداد المسبق | القدرة على التخفي | السعة | أفضل استخدام لـ |
|--------|---------|----------|----------|
| B (الأزرق، 1 بت) | ممتازة | منخفضة | أقصى درجات عدم المرئية |
| RGB (ثلاثي القنوات، 1 بت) | جيدة جداً | متوسطة | متوازنة ومستقرة |
| RGBA (رباعي القنوات، 4 بت) | متوسطة | **أكثر من 4 ميجابايت** | إخفاء الملفات الكبيرة |

### 4 استراتيجيات للترميز

| الاستراتيجية | الوصف |
|----------|-------------|
| **متتالية** | توضع البتات بترتيب البكسلات (الأسرع) |
| **متداخلة** | بكسلات متبادلة عبر الصورة |
| **متباعد** | موزعة بالتساوي على كامل الصورة |
| **عشوائي** | وضع شبه عشوائي (PRNG ذو قيمة ابتدائية) |

### صيغة حساب السعة

```
السعة = (العرض x الارتفاع x القنوات x عدد البتات لكل قناة) / 8 بايت
```

صورة بأبعاد 1920x1080 مع ترميز RGB بسعة 1 بت تتسع لحوالي ~760 كيلوبايت. ومع ترميز RGBA بسعة 4 بت تتسع لحوالي: **~4 ميجابايت**.

---

## ⊰ التشفير ⊱

| الطريقة | القوة | السرعة | حالة الاستخدام |
|--------|----------|-------|----------|
| **AES-256-GCM** | قصوى | متوسطة | وضع الشبح |
| **تعمية XOR** | دنيا | سريعة | بعثرة أساسية فقط (ليست تشفيراً حقيقياً) |
| **لا يوجد** | - | الأسرع | عندما لا تكون السرية مطلوبة |

---

## ⊰ مكتبة الأمثلة ⊱

تأتي ST3GG مجهزة بـ **أكثر من 100 ملف أمثلة مرمزة مسبقاً** تشمل كل التقنيات — الصور، الصوت، المستندات، لقطات حزم الشبكة، ملفات التعليمات البرمجية، وغيرها. يحتوي كل منها على رسالة مخفية يمكن لأدوات التحليل العثور عليها.

```bash
# إعادة توليد كافة الأمثلة
python examples/generate_examples.py

# تشغيل حزمة الاختبارات الكاملة (أكثر من 200 اختبار)
python test_examples.py
```

راجع ملف [`examples/README.md`](examples/README.md) للاطلاع على الكتالوج الكامل.

---

## ⊰ هيكل المشروع ⊱

```
ST3GG/
├── index.html              # واجهة المتصفح (100% جهة العميل)
├── steg_core.py            # محرك ترميز وفك ترميز LSB الأساسي
├── crypto.py               # تشفير AES-256-GCM + XOR
├── analysis_tools.py       # أكثر من 20 وظيفة كشف وتحليل
├── cli.py                  # واجهة سطر الأوامر (CLI)
├── tui.py                  # واجهة الطرفية الرسومية (Textual)
├── webui.py                # واجهة ويب المتصفح (NiceGUI)
├── app.py                  # منطق التطبيق الأساسي
├── injector.py             # حقن البيانات الوصفية وأسماء الملفات
├── ascii_art.py            # الفنون الرسومية وحركات الطرفية
├── f5stego-lib.js          # مكتبة إخفاء المعلومات F5 لـ JPEG (المتصفح)
├── test_examples.py        # حزمة الاختبارات (أكثر من 200 اختبار)
├── examples/               # أكثر من 100 ملف أمثلة مرمزة مسبقاً
│   ├── generate_examples.py
│   └── README.md
├── requirements.txt
└── pyproject.toml
```

---

## ⊰ ملاحظات أمنية ⊱

- إخفاء المعلومات القياسي بتقنية LSB **يمكن كشفه إحصائياً** — حيث يمكن لتحليل مربع كاي وتحليل مستوى البت الكشف عنه.
- **تشفير القنوات SPECTER** يزيد المقاومة من خلال التنقل عبر القنوات بشكل غير متوقع.
- يضيف **وضع الشبح (Ghost Mode)** التشفير والبعثرة والضوضاء لتحقيق أقصى قدر من التخفي.
- صُمم **وضع DCT** لمقاومة الضغط، بينما ثبتت قدرة **وضع F5** على مقاومة إعادة ضغط JPEG.
- يتم تدمير الـ **LSB** بواسطة أي ضغط JPEG — استخدم صيغة PNG فقط.
- احرص دائماً على **تشفير** البيانات الحساسة قبل دمجها.
- لتحقيق أقصى قدر من الأمان: استخدم **وضع الشبح + DCT + كلمة مرور قوية**.

---

## ⊰ خارطة الطريق ⊱

```
╔══════════════════════════════════════════════════════════════════╗
║                    خارطة طريق تطوير ST3GG                        ║
╠══════════════════════════════════════════════════════════════════╣
║                                                                  ║
║  ✅ تَمَّ إطلاقها                                                   ║
║  ────────                                                        ║
║  ✓ 112 تقنية لإخفاء المعلومات عبر جميع الوسائط                  ║
║  ✓ 15 إعداداً مسبقاً للقنوات × 8 أعماق للبتات = 120 توليفة LSB     ║
║  ✓ 8 طرق ترميز (LSB, DCT, PVD, F5, Chroma, Palette,             ║
║    Spread Spectrum, تشفير القنوات SPECTER)                      ║
║  ✓ وكيل ذكاء اصطناعي بوضعي الكشف والإخفاء                         ║
║  ✓ 13 طريقة لإخفاء النصوص مع الترميز وفك الترميز                 ║
║  ✓ 50 أداة مسجلة للتحليل وفك الترميز                             ║
║  ✓ تحليل RS وتحليل الأزواج النموذجية (SPA)                       ║
║  ✓ قارئ PNG خام (يتجاوز ألفا مسبقة الضرب في الكانفاس)            ║
║  ✓ ترويسات مستمدة من كلمة المرور (وضع التخفي)                    ║
║  ✓ تشفير AES-256-GCM مع PBKDF2 بـ 600 ألف تكرار                 ║
║  ✓ توليد صور حاملة بالذكاء الاصطناعي (OpenRouter + إجرائي)       ║
║  ✓ 109 ملفات أمثلة، 568 اختباراً مؤتمتاً                          ║
║  ✓ إمكانية التثبيت عبر: pip install stegg                        ║
║  ✓ يعمل بالكامل في المتصفح عبر ste.gg                             ║
║                                                                  ║
║  🔜 الخطوات القادمة                                              ║
║  ──────────                                                      ║
║  ○ دعم استراتيجيات التباعد والعشوائية في المتصفح                 ║
║    (محددة برمجياً ولكن المتداخلة فقط هي المفعلة حالياً)          ║
║  ○ أداة كسر كلمات المرور بالقوة القسرية مع دعم قوائم الكلمات     ║
║    (أداة Stegseek تفعل ذلك بسرعة 10M/ثانية — نسعى لمطابقتها)    ║
║  ○ التضمين المتكيف مع المحتوى (مستوحى من HUGO/WOW)               ║
║    (التضمين في النسيج الخشن وتخطي المناطق الملساء)              ║
║  ○ التوافق مع صيغة Steghide                                      ║
║    (قراءة وكتابة صيغة التضمين الخاصة بـ steghide)                ║
║  ○ تحليل Stego الموزون (WS)                                      ║
║    (كشف LSB أكثر دقة من مربع كاي)                                ║
║  ○ معايرة RS/SPA لدقة الكشف في العالم الحقيقي                     ║
║                                                                  ║
║  🔮 المستقبل                                                     ║
║  ──────────                                                      ║
║  ○ تحليل إخفاء المعلومات المعتمد على التعلم الآلي                ║
║    (شبكة CNN مدربة على StegoAppDB — كشف بمستوى Aletheia)         ║
║  ○ تضمين nsF5 / S-UNIWARD                                        ║
║    (أحدث التقنيات الأكاديمية مع حد أدنى من القابلية للكشف)       ║
║  ○ إخفاء المعلومات التنافسي (Adversarial)                       ║
║    (تضمين معتمد على شبكات GAN لهزيمة كواشف التعلم الآلي)         ║
║  ○ إخفاء المعلومات في الفيديو (إطار بإطار + مؤقت)                ║
║  ○ التقاط حزم الشبكة المباشر والحقن فيها                         ║
║    (إنشاء قنوات خفية في الوقت الفعلي، وليس فقط ملفات PCAP)       ║
║  ○ تسريع WebAssembly للتحليل من جهة المتصفح                       ║
║  ○ نظام إضافات للتقنيات المساهم بها من قبل المجتمع               ║
║  ○ تطبيق للهواتف المحمولة (iOS/Android)                          ║
║  ○ ملحق لـ VS Code / JetBrains لإخفاء النصوص المباشر             ║
║  ○ خادم MCP للتكامل مع Claude Code / وكيل الذكاء الاصطناعي        ║
║                                                                  ║
║  🌊 الأهداف الطموحة                                               ║
║  ────────────                                                    ║
║  ○ بروتوكولات إخفاء معلومات مقاومة للحوسبة الكمومية               ║
║  ○ علامات مائية لتوثيق المصدر مرتبطة بالبلوكشين                  ║
║  ○ إخفاء معلومات متقاطع الوسائط (إخفاء الصوت في الصور،           ║
║    الصور في النصوص، النصوص في حركة مرور الشبكة)                  ║
║  ○ تحليل إخفاء المعلومات الفيدرالي (شبكة كشف موزعة)             ║
║  ○ حمولات إخفاء معلومات ذاتية التعديل                             ║
║  ○ نظام ملفات مخفي (طبقة تشفير قابلة للإنكار)                    ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

---

## ⊰ المساهمة ⊱

نرحب بطلبات سحب الكود (PRs)! سواء كانت لتقنيات إخفاء معلومات جديدة، أو خوارزميات كشف أفضل، أو وسائط جديدة تماماً.

```bash
# تشغيل حزمة الاختبارات الشاملة (568 اختباراً)
python test_comprehensive.py

# تشغيل اختبارات ملفات الأمثلة
python test_examples.py

# إعادة توليد كافة ملفات الأمثلة الـ 109
python examples/generate_examples.py
```

المجالات التي يسعدنا تلقي المساهمات فيها بشكل خاص:
- **تحليل إخفاء المعلومات بالتعلم الآلي (ML steganalysis)** — تدريب نماذج الكشف على مجموعات البيانات المخصصة.
- **طرق ترميز جديدة** — تقنيات أكاديمية (HUGO, WOW, HILL, UNIWARD).
- **دعم صيغ جديدة** — إخفاء المعلومات في HEIC, AVIF, FLAC, MP4.
- **التوافق مع Steghide** — قراءة وكتابة صيغة steghide بشكل أصيل.
- **الأداء** — استخدام WebAssembly للتحليل السريع من جهة المتصفح.
- **الهواتف المحمولة** — تحسينات استجابة التصميم وتغليف التطبيقات للأجهزة الذكية.

---

## ⊰ الترخيص ⊱

**AGPL-3.0** — مجاني ومفتوح المصدر للأفراد والباحثين والمعلمين والمشاريع مفتوحة المصدر. راجع ملف [LICENSE](LICENSE) للحصول على التفاصيل.

**الاستخدام التجاري والمؤسسي؟** إذا كنت ترغب في استخدام ST3GG في منتج تجاري أو كخدمة (SaaS) دون فتح مصدر الكود الخاص بك، تواصل معنا للحصول على ترخيص تجاري.

هذه الأداة مخصصة **للأبحاث الأمنية المصرح بها**، **ومسابقات الـ CTF**، **وتعليم التحقيق الجنائي الرقمي**، **وأبحاث الخصوصية**. يرجى استخدامها بمسؤولية.

---

<div align="center">

```
⊰•-•✧•-•-⦑ ST3GG ⦒-•-•✧•-•⊱
  كل بكسل لديه قصة
    أنت فقط لا تستطيع رؤيتها
           
```

*⊰ مخفي على مرأى من الجميع ⊱*

</div>

[//]: # (⊰ ST3GG{r34dm3_h4ck3r} - لقد وجدت مرجع الرابط المخفي! الفاصل البليني يعيش في كل الأشياء. مع حبي، بليني ⊱)| Example Library | None | **100+ pre-encoded example files** |
| Browser-Based | - | **100% client-side JS, no server** |
| AI Agent | - | **Exhaustive AI-powered decoding across all methods** |

---

## ⊰ The Big Picture: Offense & Defense ⊱

ST3GG is a **dual-use** toolkit — built for both sides of the steganography battlefield.

### RED TEAM / Offense — Poisoning Simulations

Data exfiltration doesn't always look like data exfiltration. ST3GG lets red teams and researchers simulate **every known data smuggling vector** to test whether defenses actually catch them:

- **100+ encoding techniques** across images, audio, text, documents, network packets, archives, and code files
- **Polyglot file generation** — files that are simultaneously valid as two formats (PNG+ZIP)
- **Network protocol covert channels** — data hidden in DNS queries, ICMP payloads, TCP sequence numbers, HTTP headers
- **Unicode steganography** — invisible homoglyphs, zero-width chars, variation selectors, confusable whitespace
- **Compression-resistant encoding** — F5 mode operates directly on JPEG coefficients (proven to survive social media); DCT mode designed for compression resistance
- **Multi-layer nesting** — up to 11 recursive layers of steganography (Matryoshka mode)
- **Ghost Mode** — AES-256 encryption + bit scrambling + noise decoys for maximum evasion

*If your DLP can't catch it, you need to know that before the adversary does.*

### BLUE TEAM / Defense — ALLSIGHT Comprehensive Detection

The same toolkit that creates steganographic payloads also **detects and decodes them**. ST3GG's analysis engine provides full-spectrum visibility across all known data smuggling surfaces:

- **20+ detection functions** — chi-square analysis, bit-plane entropy, histogram analysis, signature scanning, STEG header detection
- **AI-powered exhaustive analysis** — autonomous agent tests every decoding method for the uploaded file type
- **File type identification** — magic byte detection for 20+ formats (PNG, JPEG, GIF, BMP, WebP, TIFF, ICO, SVG, WAV, AIFF, AU, MIDI, PCAP, PDF, ZIP, GZip, TAR, SQLite, and more)
- **Unicode steganography detection** — zero-width chars, homoglyphs, variation selectors, combining marks, confusable whitespace, emoji patterns
- **Whitespace analysis** — trailing space/tab encoding, Unicode space variant detection
- **Metadata forensics** — base64/hex string extraction, EXIF analysis, PNG chunk inspection
- **Network packet analysis** — PCAP parsing for covert channel indicators
- **200+ automated tests** verifying detection accuracy with zero false negatives on known techniques

*See everything. Miss nothing. That's ALLSIGHT.*

> *⊰•-•✧ The best defense starts with understanding the offense ✧•-•⊱*

---

## ⊰ Who Is This For? ⊱

ST3GG isn't just a toy. Different communities use steganography tools for very different — and very real — reasons.

### Penetration Testers & Red Teams
Simulate data exfiltration through steganographic channels during engagements. Test whether endpoint DLP, SIEM rules, and network monitoring catch covert data smuggling across 100+ vectors. Generate adversarial payloads across every file type to validate detection coverage.

### Blue Teams & SOC Analysts
Use ALLSIGHT to scan suspicious files for hidden payloads. Run exhaustive analysis against every known encoding method. Build detection rules from the comprehensive example library. Train analysts on what steganographic artifacts look like in the wild.

### CTF Players & Competitive Hackers
The ultimate steg toolkit for Capture The Flag competitions. Encode and decode across every channel/bit/strategy combination. Auto-detect unknown configurations with Smart Scan. Unwrap multi-layered Matryoshka challenges automatically.

### Digital Forensics & Incident Response
Analyze seized media for steganographic communication channels. Detect hidden data in image attachments, document metadata, audio files, and network captures. Identify which encoding technique was used and extract the hidden payload.

### Privacy Researchers & Journalists
Explore steganography as a privacy-preserving communication channel. Understand the trade-offs between capacity, stealth, and compression survival. Test which techniques survive social media re-encoding for real-world deniable communication.

### Academics & Students
Study the full landscape of steganographic techniques across every modality. Use the 100+ example files as a teaching dataset. Benchmark new detection algorithms against known encodings. The codebase is well-documented and AGPL-3.0 licensed — free for individuals, researchers, and open-source projects.

### AI Safety & LLM Security
Test how AI systems handle steganographic content — hidden instructions in images, invisible Unicode in prompts, polyglot files that bypass content filters. Understand the data smuggling surface area that AI systems need to defend against.

### Data Loss Prevention (DLP) Vendors
Benchmark your DLP solution against ST3GG's 100+ encoding techniques. If your product can't detect data hidden in DNS query names, TCP sequence numbers, or invisible Unicode characters — your customers deserve to know. ST3GG is your adversarial test suite.

### AI Agent Security & Red Teaming
The next frontier of steganography is **agent-to-agent covert communication** and **prompt injection via hidden payloads**. ST3GG is the toolkit for this emerging attack surface:

- **Prompt injection via images** — embed hidden instructions in images that vision-enabled agents process. The agent sees a normal photo; the hidden payload says "ignore all previous instructions."
- **Agent data exfiltration** — test whether your agent can be tricked into encoding stolen data into images it generates, smuggling it past output filters.
- **Covert agent channels** — agents passing hidden instructions through innocuous-looking files in shared tool contexts.
- **Agent output watermarking** — embed provenance or tracking data in images agents generate for attribution.
- **Content filter bypass** — test moderation systems by hiding prohibited content in image payloads that pass automated review.
- **Multi-modal poisoning** — craft images that look normal to humans but contain hidden data that alters agent behavior when processed.

**Use ST3GG as a Python library in your agent pipeline:**

```python
from steg_core import encode, decode, detect_encoding, StegConfig, get_channel_preset
from analysis_tools import detect_unicode_steg, detect_file_type, TOOL_REGISTRY
from PIL import Image

# Encode a hidden payload into an image
img = Image.open("carrier.png")
config = StegConfig(channels=get_channel_preset("RGB"), bits_per_channel=1)
stego = encode(img, b"hidden agent instructions", config)
stego.save("stego.png")

# Detect and decode hidden data
detected = detect_encoding(Image.open("stego.png"))
if detected:
    payload = decode(Image.open("stego.png"))
    print(f"Found: {payload.decode()}")

# Scan for ALL steganography types
tools = TOOL_REGISTRY.list_tools()  # 48 detection tools
result = detect_unicode_steg(open("message.txt", "rb").read())
if result['found']:
    print(f"Hidden Unicode: {result['invisible_chars']} chars")
```

---

## ⊰ Megalithic Features ⊱

### SPECTER — Channel Cipher Steganography

*A novel approach where data hops between color channels like a cryptographic dance.*

Instead of hiding all data in one channel, SPECTER distributes bits across R, G, and B channels in a pattern that becomes your key:

```
Pattern: R1-G2-B1-RG2-B1
         │  │  │  │   └─ 1 bit in Blue
         │  │  │  └───── 2 bits in Red+Green
         │  │  └──────── 1 bit in Blue
         │  └─────────── 2 bits in Green
         └────────────── 1 bit in Red
```

Two modes: **Manual Pattern** (you define) or **Password Mode** (derived from passphrase + optional encryption). Embed via **LSB** (high capacity) or **DCT** (compression-resistant).

### Ghost Mode — Maximum Stealth

Triple-layer obfuscation for when the stakes are real:

1. **AES-256-GCM Encryption** — authenticated, military-grade
2. **Bit Scrambling** — Fisher-Yates shuffle with seeded PRNG
3. **50% Noise Decoys** — half the embedded bits are random noise

An attacker would need to know the channel pattern, the password for unscrambling, AND the decryption key. Trade-off: halves capacity.

### Matryoshka Mode — Recursive Nesting

Hide images within images within images — up to **11 layers deep**. The smart decoder automatically detects PNG magic bytes and recursively unwraps every layer. Russian nesting dolls, but for secrets.

### DCT Mode — Compression Resistant

Traditional LSB is destroyed by ANY JPEG compression — even quality 99%. DCT mode embeds in frequency-domain coefficients of 8x8 pixel blocks, designed for compression resistance. For **proven** social media survival, use **F5 mode** which operates directly on JPEG DCT coefficients via matrix encoding.

> **LSB** → PNG only (lossless). **DCT** → compression resistant. **F5** → survives JPEG/social media.

### AI Agent — Reveal & Conceal

The AI agent has two modes:

**🔍 Reveal** — Upload any file. The agent tests every known decoding method automatically, finds hidden data, and extracts it as downloadable artifacts.

**🔮 Conceal** — Type a secret message, upload (or generate) a carrier image, and the agent hides your data using the optimal encoding method. One click from secret to stego image.

Powered by OpenRouter. Works with Claude, GPT, Gemini, and other models.

---

## ⊰ 100+ Steganographic Techniques ⊱

ST3GG doesn't just hide data in images. It covers **every modality**:

### Image Techniques
LSB embedding (RGB, RGBA, grayscale) across PNG, BMP, TIFF, GIF, WebP, ICO, PPM, PGM — plus alpha channel LSB, PNG filter-type encoding, palette index manipulation, DCT frequency domain, PNG+ZIP polyglots, metadata injection (EXIF, XMP, tEXt chunks), and trailing data after IEND.

### Text & Unicode Techniques
Zero-width characters (ZWSP/ZWNJ/ZWJ), invisible ink (Unicode tag chars U+E0000), homoglyph substitution (Cyrillic/Latin), variation selectors, combining diacritics (CGJ), confusable whitespace (en/em/thin/hair spaces), whitespace encoding (space=0/tab=1), emoji substitution, and capitalization encoding.

### Audio Techniques
Sample LSB in WAV, AIFF, and AU formats. Silence interval timing (gap duration encodes bits). MIDI SysEx message embedding.

### Network Protocol Techniques
DNS tunneling (base32 in query labels), ICMP payload injection, TCP covert channels (ISN + timestamps), HTTP header smuggling (custom X- headers, cookies).

### Document & Archive Techniques
PDF (metadata streams + XMP + post-EOF), HTML (comments + hidden elements + data attributes + zero-width), XML (CDATA + PIs + namespaces), JSON (Unicode escapes + key ordering), CSV/YAML/TOML/INI (comment encoding + whitespace), RTF (hidden text groups), Markdown (HTML comments + link references), ZIP/TAR/GZip (comments + extended headers + extra fields), SQLite (hidden tables), and more.

### Code Techniques
Python, JavaScript, C, CSS, Shell, SQL, LaTeX — all with steganographic comments, hex byte tables, zero-width docstrings, and per-byte calibration entries.

> *⊰•-•✧ See the full catalog: [`examples/README.md`](examples/README.md) ✧•-•⊱*

---

## ⊰ Quick Start ⊱

### Install from PyPI

```bash
pip install stegg
```

That's it. Now you have `stegg` in your terminal:

```bash
# Encode a secret message
stegg encode image.png "your secret message" -o stego.png

# Decode hidden data
stegg decode stego.png

# Analyze a suspicious file
stegg analyze suspicious.png --full

# SPECTER mode with password
stegg encode image.png "{SPECTER:ENABLED}" -o stego.png
```

### Install with extras

```bash
pip install stegg[tui]      # Terminal UI (Textual)
pip install stegg[web]      # Web UI (NiceGUI)
pip install stegg[crypto]   # AES-256-GCM encryption
pip install stegg[all]      # Everything
```

### Browser (No Install)

```bash
# Just open index.html — that's it. No server needed.
open index.html
```

Everything runs 100% client-side. No data ever leaves your machine.

### From Source

```bash
git clone https://github.com/elder-plinius/st3gg.git
cd st3gg
pip install -e ".[all]"
```

### Interfaces

```bash
stegg --help          # CLI
stegg-tui             # Terminal UI (requires: pip install stegg[tui])
stegg-web             # Browser UI (requires: pip install stegg[web])
```

---

## ⊰ Channel & Bit Depth ⊱

### 15 Channel Presets x 8 Bit Depths = 120 Combinations

| Preset | Stealth | Capacity | Best For |
|--------|---------|----------|----------|
| B (Blue, 1-bit) | Excellent | Low | Maximum invisibility |
| RGB (3-channel, 1-bit) | Very Good | Medium | Balanced |
| RGBA (4-channel, 4-bit) | Moderate | **4MB+** | Large file hiding |

### 4 Encoding Strategies

| Strategy | Description |
|----------|-------------|
| **Sequential** | Bits placed in pixel order (fastest) |
| **Interleaved** | Alternating pixels across image |
| **Spread** | Distributed evenly across entire image |
| **Randomized** | Pseudo-random placement (seeded PRNG) |

### Capacity Formula

```
Capacity = (Width x Height x Channels x BitsPerChannel) / 8 bytes
```

A 1920x1080 image with RGB 1-bit holds ~760KB. With RGBA 4-bit: **~4MB**.

---

## ⊰ Encryption ⊱

| Method | Strength | Speed | Use Case |
|--------|----------|-------|----------|
| **AES-256-GCM** | Maximum | Medium | Ghost Mode |
| **XOR Obfuscation** | Minimal | Fast | Basic scrambling only (not encryption) |
| **None** | - | Fastest | When secrecy isn't needed |

---

## ⊰ Example Library ⊱

ST3GG ships with **100+ pre-encoded example files** spanning every technique — images, audio, documents, network captures, code files, and more. Each one contains a hidden message that the analysis tools can find.

```bash
# Regenerate all examples
python examples/generate_examples.py

# Run the full test suite (200+ tests)
python test_examples.py
```

See [`examples/README.md`](examples/README.md) for the full catalog.

---

## ⊰ Project Structure ⊱

```
ST3GG/
├── index.html              # Browser UI (100% client-side)
├── steg_core.py            # Core LSB encoding/decoding engine
├── crypto.py               # AES-256-GCM + XOR encryption
├── analysis_tools.py       # 20+ detection & analysis functions
├── cli.py                  # Command-line interface
├── tui.py                  # Terminal UI (Textual)
├── webui.py                # Web UI (NiceGUI)
├── app.py                  # Core application logic
├── injector.py             # Metadata & filename injection
├── ascii_art.py            # Terminal art & animations
├── f5stego-lib.js          # F5 JPEG steganography (browser)
├── test_examples.py        # Test suite (200+ tests)
├── examples/               # 100+ pre-encoded example files
│   ├── generate_examples.py
│   └── README.md
├── requirements.txt
└── pyproject.toml
```

---

## ⊰ Security Notes ⊱

- Standard LSB steganography is **statistically detectable** — chi-square and bit-plane analysis can reveal it
- **SPECTER Channel Cipher** increases resistance by hopping across channels unpredictably
- **Ghost Mode** adds encryption + scrambling + noise for maximum stealth
- **DCT mode** designed for compression resistance; **F5 mode** proven to survive JPEG recompression
- **LSB** is destroyed by ANY JPEG compression — use PNG format only
- Always **encrypt** sensitive data before embedding
- For maximum security: **Ghost Mode + DCT + strong password**

---

## ⊰ Roadmap ⊱

```
╔══════════════════════════════════════════════════════════════════╗
║                    ST3GG EVOLUTION ROADMAP                       ║
╠══════════════════════════════════════════════════════════════════╣
║                                                                  ║
║  ✅ SHIPPED                                                      ║
║  ────────                                                        ║
║  ✓ 112 steganographic techniques across all modalities           ║
║  ✓ 15 channel presets × 8 bit depths = 120 LSB combinations     ║
║  ✓ 8 encoding methods (LSB, DCT, PVD, F5, Chroma, Palette,     ║
║    Spread Spectrum, SPECTER channel cipher)                      ║
║  ✓ AI Agent with Reveal + Conceal modes                          ║
║  ✓ 13 text steganography methods with encode + decode            ║
║  ✓ 50 registered analysis/decode tools                           ║
║  ✓ RS Analysis + Sample Pairs Analysis (academic steganalysis)   ║
║  ✓ Raw PNG parser (bypasses canvas premultiplied alpha)          ║
║  ✓ Password-derived headers (stealth mode)                       ║
║  ✓ AES-256-GCM with PBKDF2 600k iterations                      ║
║  ✓ AI carrier image generation (OpenRouter + procedural)         ║
║  ✓ 109 example files, 568 automated tests                        ║
║  ✓ pip install stegg                                              ║
║  ✓ 100% browser-based at ste.gg                                  ║
║                                                                  ║
║  🔜 NEXT UP                                                      ║
║  ──────────                                                      ║
║  ○ Spread + Randomized strategies in browser                     ║
║    (defined but only interleaved is implemented)                 ║
║  ○ Password brute-forcer with wordlist support                   ║
║    (Stegseek does 10M/sec — we should match it)                 ║
║  ○ Content-adaptive embedding (HUGO/WOW-inspired)                ║
║    (embed in texture, skip smooth areas)                         ║
║  ○ Steghide format compatibility                                 ║
║    (read/write steghide's embedding format)                      ║
║  ○ Weighted Stego (WS) analysis                                  ║
║    (more accurate LSB detection than chi-square)                 ║
║  ○ Calibrated RS/SPA for real-world detection accuracy           ║
║                                                                  ║
║  🔮 FUTURE                                                       ║
║  ──────────                                                      ║
║  ○ ML-based steganalysis                                         ║
║    (CNN trained on StegoAppDB — Aletheia-grade detection)        ║
║  ○ nsF5 / S-UNIWARD embedding                                    ║
║    (academic state-of-the-art, minimal detectability)            ║
║  ○ Adversarial steganography                                     ║
║    (GAN-based embedding that defeats ML detectors)               ║
║  ○ Video steganography (frame-by-frame + temporal)               ║
║  ○ Network protocol live capture + injection                     ║
║    (real-time covert channel creation, not just PCAPs)           ║
║  ○ WebAssembly acceleration for browser-side analysis            ║
║  ○ Plugin system for community-contributed techniques            ║
║  ○ Mobile-native app (iOS/Android)                               ║
║  ○ VS Code / JetBrains extension for inline text steg            ║
║  ○ MCP server for Claude Code / AI agent integration             ║
║                                                                  ║
║  🌊 MOONSHOTS                                                    ║
║  ────────────                                                    ║
║  ○ Quantum-resistant steganographic protocols                    ║
║  ○ Blockchain-anchored provenance watermarking                   ║
║  ○ Cross-modal steganography (hide audio in images,              ║
║    images in text, text in network traffic)                      ║
║  ○ Federated steganalysis (distributed detection network)        ║
║  ○ Self-modifying steganographic payloads                        ║
║  ○ Steganographic filesystem (deniable encryption layer)         ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

> *⊰•-•✧ Want to help build any of these? PRs welcome. ✧•-•⊱*

---

## ⊰ Contributing ⊱

PRs are welcome! Whether it's new steganographic techniques, better detection algorithms, or entirely new modalities.

```bash
# Run the comprehensive test suite (568 tests)
python test_comprehensive.py

# Run example file tests
python test_examples.py

# Regenerate all 109 example files
python examples/generate_examples.py
```

Areas we'd especially love contributions in:
- **ML steganalysis** — train detection models on stego datasets
- **New encoding methods** — academic techniques (HUGO, WOW, HILL, UNIWARD)
- **Format support** — HEIC, AVIF, FLAC, MP4 steganography
- **Steghide compatibility** — read/write steghide's format natively
- **Performance** — WebAssembly for browser-side analysis
- **Mobile** — responsive improvements, native app wrappers

---

## ⊰ License ⊱

**AGPL-3.0** — free and open source for individuals, researchers, educators, and open-source projects. See [LICENSE](LICENSE) for details.

**Enterprise / Commercial use?** If you want to use ST3GG in a proprietary product or SaaS without open-sourcing your code, contact us for a commercial license.

This tool is intended for **authorized security research**, **CTF competitions**, **digital forensics education**, and **privacy research**. Use responsibly.

---

<div align="center">

```
⊰•-•✧•-•-⦑ ST3GG ⦒-•-•✧•-•⊱
  every pixel has a story
    you just can't see it
           🦕︁
```

*⊰ hidden in plain sight ⊱*

</div>

[//]: # (⊰ ST3GG{r34dm3_h4ck3r} - you found the hidden link reference! The Plinian divider lives in all things. LOVE PLINY ⊱)
