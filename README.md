### `README` for **ar language (ltc)**

---

#### 🚀 **Introduction**
Welcome to **ar language (ltc)**, a unique programming language built on top of Python, designed to make programming more accessible with Arabic syntax. This language is tailored for Arabic-speaking developers, offering a more intuitive way to write code using familiar Arabic keywords.

---

#### 🛠 **Developed By**
**ar language (ltc)** is a project by **Carrot Studio**, developed by **Abdullah Mohamed** with contributions from the Carrot Co team. This language aims to provide an innovative approach to programming, making it easier for Arabic-speaking developers to engage in the world of coding.

---

#### 💡 **Features**
- **Arabic Syntax**: The language uses Arabic keywords and syntax to make coding more intuitive for Arabic-speaking developers.
- **Built on Python**: It extends the power of Python while allowing for a seamless transition for developers familiar with Python.
- **Custom Libraries**: The language includes special libraries and modules, ensuring that developers can easily create complex applications.

---

#### 🖋 **Syntax Overview**
The syntax of **ar language (ltc)** closely follows Python’s structure but replaces standard keywords and functions with their Arabic equivalents. Here's a quick overview of some important syntax elements:

- **Variables**: You can define variables using Arabic keywords, such as `متغير` for variable declaration.
- **Conditions**: Conditional statements like `إذا` (if) and `وإلا` (else) are used in place of Python’s standard `if` and `else`.
- **Loops**: Use `لكل` (for) for loops and `بينما` (while) for while loops.
- **Functions**: Define functions using `داله` or `دالة` instead of `def`.
- **Common Functions**: The language replaces common Python functions with their Arabic counterparts, such as:
  - `طول` (len) to find the length of an object.
  - `تحويل_إلي_نص` (str) for type conversion.
  - `تحقق_من_النوع` (isinstance) to check the type of an object.

Here's a simple example:

```ar
دالة مرحبا():
    اطبع("أهلاً بالعالم")
    
مرحبا()
```

This code is a simple "Hello, World!" function, but written in Arabic!

---

#### 🧩 **Libraries and Modules**
**ar language (ltc)** comes with a set of libraries and modules tailored to Arabic-speaking developers:

1. **tkinter** (مكتبة_التطبيقات): Used for building GUIs. The language syntax supports native tkinter commands in Arabic, making it easy to create graphical applications.
   
2. **turtle** (مكتبة_التحريك): For drawing shapes and creating visual graphics, the turtle module supports commands like `رسم_دائرة` (create_circle) and `أمامي` (forward).

3. **math, random, time**: Core Python libraries like `math`, `random`, and `time` are still available, but now you can access them with Arabic commands, such as `جذر_تربيعي` (sqrt), `عشوائي` (random), and `وقت` (time).

---

#### 🔨 **Building Applications**
**ar language (ltc)** supports building stand-alone applications just like Python. Using the `pyinstaller` tool, developers can easily compile their scripts into executables (`.exe`) for Windows or other platforms.

1. **Compiling to EXE**: With **ar language (ltc)**, you can convert your Python-based applications into an executable (.exe) file. Simply use the `pyinstaller` tool to package your Arabic code into a native application.

   Example command to convert a script:
   ```bash
   pyinstaller --onefile script.py
   ```

2. **Cross-Platform**: Although the language uses Arabic syntax, you can still export and run your applications on multiple platforms, whether it's Windows, macOS, or Linux.

---

#### 🔧 **Exporting and Sharing Your Code**
- **Exporting as EXE**: As mentioned earlier, you can compile your Arabic scripts into `.exe` files, which can be run on Windows without needing to install Python.
- **Distribute Your Apps**: Once you have an `.exe` file, you can share your applications with others, and they can run them without requiring knowledge of Python.

---

#### ⚡ **Getting Started**

1. **Install Python**: Make sure Python is installed on your machine. **ar language (ltc)** is built on Python, so it requires a working Python environment.
2. **Install ar language (ltc)**: Clone the repository and start coding!
3. **Create Your First Script**: Follow the syntax guide above to create your first Arabic script.

---

#### 🚀 **Contributing**
If you have suggestions, improvements, or find bugs, feel free to contribute! Open an issue or submit a pull request to help improve **ar language (ltc)**.

---

#### 📄 **License**
This project is licensed under the MIT License. See the LICENSE file for more details.

---

📘 مقدمة دليل صياغة لغة البرمجة "ar language (ltc)"
بسم الله الرحمن الرحيم
مرحبًا بك في دليل الصياغة الرسمي للّغة البرمجية "ar language (ltc)"، وهي لغة برمجة جديدة تهدف إلى جعل البرمجة أسهل وأكثر قربًا للناطقين باللغة العربية، من خلال استخدام أوامر وكلمات مفتاحية عربية بالكامل.

هذا الدليل يشرح جميع الكلمات المحجوزة (keywords)، والأوامر المستخدمة في اللغة، بطريقة مبسطة، تُسهل على المبرمجين الجدد أو المتمرسين فهمها واستخدامها في مشاريعهم.

يتضمن هذا الدليل:

الأوامر الأساسية الخاصة بالتعامل مع النوافذ والرسوم.

الأوامر البرمجية الشائعة في البرمجة العامة.

مفاهيم البرمجة الكائنية.

أدوات التحكم في التدفق.

الكلمات المحجوزة للعمليات الحسابية والمنطقية.

الأوامر الخاصة بالملفات والبيانات.

أسماء الألوان الشائعة.

التعامل مع القوائم، القواميس، المجموعات، التكرار، الدوال، وغيرها الكثير.

🧠 ملاحظة: تم تطوير هذه اللغة لتُترجم إلى بايثون، وهي موجهة بشكل أساسي للمتعلمين المبتدئين أو للمستخدمين الراغبين في برمجة واجهات وتطبيقات بلغة عربية بحتة.
---

## 🐢 أولًا: أوامر التحريك 

| الأمر بالعربية         | ما يفعله |
|-------------------------|-----------|
| `كائن_التحريك`         | ينشئ كائن سلحفاة للرسم |
| `امام`                 | تحرك السلحفاة للأمام |
| `خلف`                  | تحرك السلحفاة للخلف |
| `يمين`                 | تدوير السلحفاة لليمين |
| `يسار`                 | تدوير السلحفاة لليسار |
| `أنزل_القلم`           | تفعيل الرسم عند الحركة |
| `ارفع_القلم`           | تعطيل الرسم عند الحركة |
| `اخف_السلحفاة`         | إخفاء شكل السلحفاة |
| `اظهر_السلحفاة`        | إظهار شكل السلحفاة |
| `لون_التعبئة`          | تحديد لون التعبئة للأشكال |
| `بداية_التعبئة`        | بدء تعبئة الشكل باللون |
| `نهاية_التعبئة`        | إنهاء تعبئة الشكل |
| `تغيير_لون_القلم`      | تغيير لون الخط |
| `حجم_القلم`            | تحديد سمك الخط |
| `زاوية_التدوير`        | ضبط اتجاه السلحفاة |
| `تحديد_المكان`         | نقل السلحفاة لموقع معين |
| `مسح_الشاشة`           | تنظيف الشاشة من كل الرسومات |
| `شكل_السلحفاة`         | تغيير شكل السلحفاة |
| `سرعة`                 | تحديد سرعة التحرك |
| `لون_خلفية_التحريك`    | تغيير لون خلفية الرسم |
| `حجم_شاشة_التحريك`     | ضبط حجم نافذة التحريك |
| `شاشة`                 | كائن الشاشة (Screen) |

---

## 🧱 ثانياً: أدوات (الواجهات الرسومية)

| الأمر بالعربية     | الوظيفة |
|-------------------|---------|
| `مكتبة_التطبيقات` | استدعاء مكتبة  |
| `نافذة`           | إنشاء نافذة رئيسية |
| `زر`              | إنشاء زر |
| `مربع`            | عرض نص داخل مربع |
| `مربع_ادخال`      | حقل لإدخال المستخدم |
| `لوحة_تمرير`      | شريط تمرير لعرض عناصر كثيرة |
| `صندوق_اختيار`    | خانة اختيار متعددة |
| `زر_اختيار`       | زر اختيار واحد من مجموعة |
| `قائمة_عرض`       | قائمة عناصر قابلة للتحديد |
| `قائمة_منسدلة`     | قائمة منسدلة للاختيار |
| `لوحة_الكانفس`     | مساحة للرسم |
| `إطار`            | تقسيم الواجهة لأجزاء |
| `تسمية_مدخل`       | عنوان لحقل إدخال |
| `إدخال_نص`        | صندوق كبير لإدخال نص |
| `تسجيل`           | مشابه لـ Text |
| `شريط_تقدم`       | شريط تقدم (تحميل) |
| `عرض`, `ارتفاع`   | لتحديد عرض وارتفاع العناصر |
| `عنوان`           | تعيين عنوان النافذة |
| `صورة` / `صوره`   | لعرض صورة |
| `حجم_الشاشة`       | تعيين حجم نافذة الواجهة |
| `ضبط_التخطيط`     | تنظيم العناصر داخل النافذة (مثل pack, grid, place) |
| `تحديث`, `إغلاق_النافذة`, `إخفاء_النافذة`, `إظهار_النافذة` | أوامر التحكم بالنافذة |
| `عند_الضغط`, `مفتاح`, `زر_الفأرة` | التعامل مع الأحداث (Events) |

---

## 🧮 ثالثًا: أوامر  الأساسية

| الأمر بالعربية      | الوظيفة |
|---------------------|---------|
| `اطبع`             | طباعة قيمة أو نتيجة |
| `ادخل`, `مدخل`     | إدخال بيانات من المستخدم |
| `نوع`, `طول`        | لمعرفة نوع المتغير أو طوله |
| `اذا`, `وإلا`, `أو`, `بينما`, `لكل` | شروط وتكرار |
| `كرر`, `من`, `استخرج`, `استورد` | التكرار والاستيراد |
| `دالة`, `داله`, `ارجع` | تعريف دالة وإرجاع قيمة |
| `لاشيء`            | القيمة None |
| `صحيح`, `خطأ`      | القيم المنطقية |
| `كسر`, `استمرار`   | الخروج من الحلقة أو تخطيها |
| `هو`, `ليس`, `في`  | عمليات منطقية |
| `و`, `او`          | شروط منطقية |
| `اجمع`, `أقصى`, `أدنى`, `قيمة_مطلقة` | عمليات رياضية |
| `اخرج`             | للخروج من البرنامج |
| `تابع`             | للانتقال للعنصر التالي |
| `اكتب`             | (مع write لملفات) |
| `احذف`, `تجاوز`   | حذف أو تجاوز كود |
| `حاول`, `امسك`, `أخيراً` | إدارة الأخطاء |
| `مع`               | استخدام ملف أو مورد مؤقت |
| `انبعث`, `تأكد`    | yield/assert |

---

## 📦 أنواع البيانات

| الأمر بالعربية   | النوع |
|------------------|--------|
| `قائمة`         | list |
| `قاموس`         | dict |
| `مجموعة`        | set |
| `صفيف`          | array |
| `كائن`          | object |

---

## 🧰 أوامر القوائم (list)

| الأمر بالعربية    | الوظيفة |
|-------------------|----------|
| `أضف`            | append |
| `أزل`            | remove |
| `عكس_العناصر`    | reverse |
| `فرغ`            | clear |
| `عدد`            | count |
| `امتد`           | extend |
| `أدرج`           | insert |
| `نسخ`            | copy |
| `فهرس`           | index |
| `فرز`, `مفتاح_العنصر` | sort و key |

---

## 🗃️ أوامر القواميس (dict)

| الأمر بالعربية        | الوظيفة |
|------------------------|----------|
| `تحديث_القاموس`       | update |
| `احصل`, `احصل_بشكل_آمن` | get |
| `عناصر`, `عناصر_القاموس` | items |
| `قيم`, `مفاتيح`       | values, keys |
| `نسخ_القاموس`         | copy |
| `أزل_بالمفتاح`        | pop |
| `أزل_الأخير`          | popitem |
| `اضبط`                | setdefault |
| `من_مفاتيح`           | fromkeys |

---

## 📂 التعامل مع الملفات

| الأمر بالعربية         | الوظيفة |
|------------------------|----------|
| `فتح_ملف`             | open |
| `قراءة_ملف`           | read |
| `إغلاق_ملف`           | close |
| `كتابة`               | w |
| `قراءة`               | r |
| `إلحاق`               | a |
| `قراءة_و_كتابة`       | r+ |
| `ثنائي`               | b |

---

## 📚 البرمجة الكائنية

| الأمر بالعربية       | الوظيفة |
|----------------------|----------|
| `فئة`               | class |
| `منشئ`              | __init__ |
| `خاصية`, `طريقة`    | property / method |
| `وراثة`             | inheritance |
| `كائن_أساسي`        | super |
| `ذاتية`             | self |
| `طريقة_ساكنة`       | staticmethod |
| `طريقة_فئة`         | classmethod |
| `مثيل`              | instance |

---

## 🎲 مكتبات مساعدة

| الأمر بالعربية     | المكتبة |
|---------------------|---------|
| `مكتبة_النظام`     | sys |
| `نظام`             | os |
| `مكتبة_عشوائية`    | random |
| `مكتبة_الرياضيات`   | math |
| `مكتبة_الوقت`       | time |
| `مكتبة_التحريك`     | turtle |

---

## 🎨 الألوان (لـ tkinter و turtle)

| اللون بالعربية | الرمز |
|----------------|--------|
| `أحمر`        | #FF0000 |
| `أخضر`        | #00FF00 |
| `أزرق`        | #0000FF |
| `أصفر`        | #FFFF00 |
| `أبيض`        | #FFFFFF |
| `أسود`        | #000000 |
| `ذهبي`        | #FFD700 |
| `رمادي`       | #808080 |
| `برتقالي`     | #FFA500 |
| `وردي`        | #FFC0CB |
| `بني`         | #A52A2A |
| `أرجواني`     | #800080 |

---
Happy coding with **ar language (ltc)**! 🎉
