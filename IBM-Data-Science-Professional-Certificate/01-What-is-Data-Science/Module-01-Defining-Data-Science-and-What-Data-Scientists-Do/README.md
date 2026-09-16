<div dir="rtl">

# What is Data Science? | ما هو علم البيانات؟

## الفكرة الأساسية

**Data Science | علم البيانات**

هو استخدام البيانات لفهم المشكلات، واكتشاف **الأنماط (Patterns)** و**الاستنتاجات المفيدة (Insights)** التي تساعد على اتخاذ قرارات أفضل.

وجود كمية كبيرة من البيانات لا يعني وجود قيمة تلقائيًا؛ القيمة تظهر عندما يتم تحليل هذه البيانات وتحويلها إلى معرفة يمكن الاستفادة منها.

> **Data Science is a process, not an event.**

أي أن علم البيانات ليس خطوة واحدة، بل عملية مترابطة تبدأ بمشكلة أو سؤال وتنتهي بفهم أو قرار.

---

## تسلسل الوحدة

</div>

```text
What is Data Science?
        ↓
Problem / Question
        ↓
Data
        ↓
Analysis
        ↓
Patterns & Relationships
        ↓
Insights
        ↓
Visualization & Storytelling
        ↓
Decision / Action
```

<div dir="rtl">

يبدأ علم البيانات بتحديد المشكلة، ثم جمع البيانات المناسبة وتحليلها للبحث عن الأنماط والعلاقات.

بعد الوصول إلى **Insights**، يتم توصيلها بصورة واضحة حتى يمكن استخدامها في اتخاذ قرار أو حل مشكلة.

---

## 1. Problem or Question | المشكلة أو السؤال

أي مشروع في **Data Science** يبدأ بسؤال واضح:

</div>

> **What problem are we trying to solve?**

<div dir="rtl">

تحديد المشكلة أولًا يساعد على معرفة البيانات المطلوبة بدلًا من جمع بيانات كثيرة دون هدف.

بعد تحديد المشكلة يأتي السؤال:

</div>

> **What data do we need, and where will it come from?**

<div dir="rtl">

أي: ما البيانات التي نحتاجها لحل المشكلة، ومن أين سنحصل عليها؟

---

## 2. Data Scientist | عالم البيانات

**Data Scientist | عالم البيانات**

هو الشخص الذي يستخدم البيانات والأدوات المناسبة لفهم المشكلات، وتحليل البيانات واستخراج **Insights**، ثم توصيل النتائج إلى الأشخاص المعنيين.

يتطلب هذا العمل مجموعة من المهارات، من أهمها:

- **Curiosity:** الفضول وطرح الأسئلة.
- **Analytics:** تحليل البيانات واستخراج المعنى منها.
- **Programming:** استخدام البرمجة والأدوات التقنية.
- **Domain Knowledge:** فهم المجال المرتبط بالمشكلة.
- **Communication:** توصيل النتائج بوضوح.
- **Storytelling:** تحويل النتائج إلى قصة أو رسالة مفهومة.

لا يوجد مسار أكاديمي واحد فقط للوصول إلى مجال **Data Science**.

يمكن أن يأتي علماء البيانات **(Data Scientists)** من خلفيات وتخصصات مختلفة.

---

## 3. Curiosity | الفضول

**Curiosity | الفضول**

الفضول جزء مهم من طريقة التفكير في علم البيانات **(Data Science)**. التحليل لا يعني قبول أول نتيجة تظهر، بل قد يقود إلى سؤال أو **فرضية جديدة (Hypothesis)**.

ظهر ذلك في مثال تحليل شكاوى المواصلات في **Toronto**. لم يظهر في البداية تفسير واضح لارتفاع عدد الشكاوى، مما أدى إلى سؤال جديد:

**هل يمكن أن يكون للطقس علاقة بها؟**

تمت إضافة بيانات الطقس **(Weather Data)** ومقارنتها ببيانات الشكاوى:

</div>

```text
Complaint Data + Weather Data
              ↓
           Analysis
              ↓
        Relationship
              ↓
           Insight
```

<div dir="rtl">

ظهر ارتباط بين بعض الأيام ذات الطقس السيئ أو غير المتوقع وارتفاع عدد الشكاوى.

يوضح المثال كيف يمكن أن يقود الفضول إلى:

</div>

```text
Curiosity
   ↓
New Question
   ↓
Additional Data
   ↓
Relationship
   ↓
Insight
```

<div dir="rtl">

---

## 4. Data | جمع البيانات وفهم شكلها

بعد تحديد السؤال والبيانات المطلوبة تبدأ مرحلة التعامل مع **Data**.

البيانات قد تأتي بأشكال مختلفة، وأحد أهم الاختلافات هو طريقة تنظيمها.

### Structured Data | البيانات المنظمة

هي بيانات لها تنظيم واضح، وغالبًا تكون على شكل **صفوف وأعمدة (Rows and Columns)**.

| Student | Study Hours | Grade |
| --- | ---: | ---: |
| A | 5 | 90 |
| B | 3 | 75 |

ويُطلق على البيانات المنظمة في صفوف وأعمدة أيضًا:

**Tabular Data | البيانات الجدولية**

### Unstructured Data | البيانات غير المنظمة

هي بيانات لا تأتي بشكل جدولي منظم، مثل:

- Text
- Emails
- Web Pages
- Audio
- Video

قد تحتاج هذه البيانات إلى معالجة إضافية لاستخراج معلومات يمكن تحليلها.

---

## 5. File Formats | صيغ الملفات

يمكن تخزين البيانات ونقلها باستخدام صيغ مختلفة.

### CSV | Comma-Separated Values

صيغة نصية شائعة لتخزين البيانات الجدولية، وتستخدم الفاصلة `,` للفصل بين القيم.

</div>

```text
Name,Age,Major
Jana,20,Data Science
Sara,21,AI
```

<div dir="rtl">

### TSV | Tab-Separated Values

تشبه **CSV**، لكنها تستخدم **Tab** للفصل بين القيم.

كل من **CSV** و**TSV** يعد مثالًا على **Delimited Text File**، وهو ملف نصي يستخدم رمزًا محددًا يسمى **Delimiter** للفصل بين القيم.

### XLSX

هي صيغة ملفات **Microsoft Excel**.

يمكن أن يحتوي **Workbook** على عدة **Worksheets**، وكل ورقة تحتوي على:

**Rows + Columns + Cells**

### XML | Extensible Markup Language

صيغة تستخدم **Tags** لتنظيم البيانات وتخزينها وتبادلها بين الأنظمة.

</div>

```xml
<student>
    <name>Jana</name>
    <age>20</age>
</student>
```

<div dir="rtl">

### JSON | JavaScript Object Notation

صيغة نصية منظمة تستخدم لتبادل البيانات بين التطبيقات، وتظهر كثيرًا مع **APIs** و**Web Services**.

</div>

```json
{
  "name": "Jana",
  "age": 20
}
```

<div dir="rtl">

### PDF | Portable Document Format

صيغة مصممة لعرض المستندات بصورة متسقة عبر الأجهزة وأنظمة التشغيل المختلفة.

---

## 6. Data Analysis | تحليل البيانات

بعد جمع البيانات وفهمها تبدأ مرحلة **Data Analysis | تحليل البيانات**.

الهدف هو البحث داخل البيانات عن أشياء ذات معنى، مثل:

- **Patterns:** أنماط متكررة في البيانات.
- **Relationships:** علاقات بين المتغيرات.
- **Outliers:** قيم تختلف بشكل ملحوظ عن معظم البيانات.
- **Insights:** معرفة مفيدة يتم استخلاصها من النتائج.

ولتحقيق ذلك يمكن استخدام **Algorithms** و**Models** مختلفة حسب طبيعة المشكلة.

### Algorithm | الخوارزمية

الخوارزمية هي مجموعة من الخطوات والتعليمات المنظمة لحل مشكلة أو تنفيذ مهمة.

</div>

```text
Input → Steps → Output
```

<div dir="rtl">

### Model | النموذج

النموذج هو تمثيل للعلاقات أو الأنماط الموجودة في البيانات، ويمكن استخدامه للتحليل أو التنبؤ.

---

## 7. Regression | الانحدار

**Regression | الانحدار**

هو نموذج إحصائي يستخدم لدراسة العلاقة بين متغير أو أكثر والنتيجة المرتبطة بها.

</div>

> **Regression shows the relationship between predictor variables and a response variable.**

<div dir="rtl">

يمكن فهمه من خلال مثال أجرة سيارة الأجرة:

</div>

```text
Distance + Time
       ↓
      Fare
```

<div dir="rtl">

في هذا المثال:

- **Distance** و**Time** هما **Predictor Variables**، أي المتغيرات المستخدمة لدراسة النتيجة.
- **Fare** هي **Response Variable**، أي المتغير الذي يمثل النتيجة.

من خلال بيانات الرحلات السابقة، يمكن استخدام **Regression** لفهم العلاقة بين المسافة والأجرة، وكذلك بين الوقت والأجرة.

</div>

```text
Regression
    ↓
Understanding Relationships Between Variables
```

<div dir="rtl">

---

## 8. Algorithms and Models | الخوارزميات والنماذج

توجد **Algorithms** و**Models** مختلفة، ويتم اختيار المناسب منها حسب المشكلة.

### Nearest Neighbor

هو أحد خوارزميات تعلم الآلة **(Machine Learning Algorithms)**، ويعتمد على التشابه **(Similarity)** مع حالات موجودة في البيانات للمساعدة في التنبؤ بحالة جديدة.

</div>

```text
New Case
   ↓
Similar Cases
   ↓
Prediction
```

<div dir="rtl">

### Neural Networks | الشبكات العصبية

هي نماذج حاسوبية **(Computational Models)** تستخدم لتعلم **Patterns** من البيانات وإنتاج **Predictions** أو **Outputs**.

ظهر استخدامها في مثال **Algae Blooms**، حيث استُخدمت للمساعدة في التنبؤ بعودة ازدهار الطحالب والاستعداد لمشكلات جودة المياه.

### Recommendation Engine | نظام التوصية

هو برنامج يحلل سلوك المستخدم أو تفضيلاته ليقدم توصيات مخصصة.

يوضح هذا المثال أيضًا أن الحل الفعال لا يحتاج دائمًا إلى أن يكون شديد التعقيد؛ فقد يكون الحل البسيط والمفهوم فعالًا جدًا.

---

## 9. Tools | الأدوات

تختلف الأدوات المستخدمة حسب طبيعة البيانات والمشكلة.

### Python

لغة برمجة واسعة الاستخدام في **Data Science** لمعالجة البيانات وتحليلها وتنفيذ العديد من المهام البرمجية.

### Pandas

مكتبة في **Python** توفر أدوات للعمل مع البيانات، وتستخدم كثيرًا في معالجة البيانات وتحليلها **(Data Manipulation and Analysis)**.

</div>

```text
Python
   ↓
Pandas
   ↓
Load / Manipulate / Analyze Data
```

<div dir="rtl">

### Jupyter Notebook

بيئة عمل تسمح بجمع عدة عناصر في مكان واحد:

</div>

```text
Code + Output + Visualizations + Explanatory Text
```

<div dir="rtl">

وتستخدم لتحليل البيانات، وتجربة الأكواد، ومشاهدة النتائج، وتوثيق خطوات العمل.

### R

لغة برمجة تستخدم في:

</div>

```text
Statistical Computing
        +
Data Analysis
        +
Data Visualization
```

<div dir="rtl">

### Hadoop

إطار عمل مفتوح المصدر **(Open-Source Framework)** مصمم لتخزين ومعالجة مجموعات بيانات كبيرة عبر **Clusters of Computers**.

يسمح بتوزيع تخزين البيانات ومعالجتها على مجموعة من الأجهزة عند التعامل مع كميات كبيرة من البيانات.

---

## 10. من Insight إلى Decision

استخراج **Insight** ليس نهاية عملية علم البيانات. يجب تحويل النتيجة إلى شيء يستطيع الآخرون فهمه والاستفادة منه.

### Data Visualization | تصور البيانات

هو تمثيل البيانات بصريًا باستخدام **Graphs** و**Charts** لتسهيل رؤية **Trends** و**Patterns** والنتائج المهمة.

الهدف ليس مجرد إنشاء رسم، بل جعل الرسالة الموجودة في البيانات أسهل في الفهم.

### Storytelling | سرد النتائج

يعني تقديم نتائج التحليل بطريقة مترابطة توضح:

- ماذا اكتشف التحليل؟
- ماذا تعني النتيجة؟
- لماذا هي مهمة؟

يتم توصيل هذه النتائج إلى **Stakeholders | أصحاب المصلحة**، وهم الأشخاص أو الجهات المعنية بالمشكلة أو القرار.

</div>

```text
Analysis
   ↓
Insight
   ↓
Data Visualization
   ↓
Storytelling
   ↓
Stakeholders
   ↓
Decision / Action
```

<div dir="rtl">

بهذه الخطوة تتحول نتائج التحليل إلى معرفة يمكن استخدامها فعليًا.

---

## أهم المصطلحات | Key Terms

| Term | المعنى | الفكرة باختصار |
| --- | --- | --- |
| Data Science | علم البيانات | استخدام البيانات لفهم المشكلات واستخراج Insights |
| Data Scientist | عالم البيانات | يستخدم البيانات والأدوات المناسبة لحل المشكلات |
| Insight | استنتاج مفيد | معرفة ذات معنى مستخرجة من البيانات |
| Pattern | نمط | سلوك أو ترتيب متكرر في البيانات |
| Relationship | علاقة | ارتباط بين متغيرات في البيانات |
| Curiosity | الفضول | طرح أسئلة تقود إلى استكشاف البيانات |
| Structured Data | بيانات منظمة | بيانات منظمة غالبًا في Rows وColumns |
| Unstructured Data | بيانات غير منظمة | بيانات مثل Text وAudio وVideo |
| Tabular Data | بيانات جدولية | بيانات منظمة في Rows وColumns |
| Algorithm | خوارزمية | خطوات منظمة لحل مشكلة أو تنفيذ مهمة |
| Model | نموذج | تمثيل للعلاقات أو الأنماط في البيانات |
| Outlier | قيمة شاذة | قيمة تختلف بشكل ملحوظ عن معظم البيانات |
| Regression | الانحدار | نموذج إحصائي لدراسة العلاقات بين المتغيرات |
| Predictor Variable | متغير متنبئ | متغير يستخدم لدراسة أو توقع النتيجة |
| Response Variable | متغير الاستجابة | المتغير الذي يمثل النتيجة |
| Data Visualization | تصور البيانات | عرض البيانات بصريًا لتسهيل فهمها |
| Storytelling | سرد النتائج | توصيل نتائج التحليل بصورة مترابطة ومفهومة |
| Stakeholder | صاحب مصلحة | شخص أو جهة معنية بالنتائج أو القرار |

---

## قصة الوحدة | The Unit Story

بدأت الوحدة بالسؤال الأساسي:

</div>

> **What is Data Science?**

<div dir="rtl">

وعرفنا أن **Data Science** هو استخدام البيانات لفهم المشكلات واكتشاف **Patterns** و**Insights** يمكن أن تساعد على اتخاذ قرارات أفضل.

لكن حتى يتم تطبيق علم البيانات فعليًا، نحتاج إلى **Data Scientist**. يبدأ عمله من **Problem or Question**، ويستخدم **Curiosity** لطرح الأسئلة وتحديد ما الذي يحاول فهمه أو حله.

بعدها يأتي السؤال:

</div>

> **What data do we need, and where will it come from?**

<div dir="rtl">

فيتم جمع البيانات المناسبة، والتي قد تكون **Structured Data** منظمة في صفوف وأعمدة، أو **Unstructured Data** مثل النصوص والصوت والفيديو.

وقد تكون البيانات محفوظة بصيغ مختلفة مثل **CSV وXLSX وXML وJSON**.

بعد توفر البيانات، تبدأ مرحلة **Analysis** باستخدام الأدوات والأساليب المناسبة. يمكن استخدام **Python** و**Pandas** للعمل مع البيانات، واستخدام **Models** أو **Algorithms** حسب طبيعة المشكلة، مثل **Regression** لدراسة العلاقات بين المتغيرات.

الهدف من التحليل هو الوصول إلى:

</div>

```text
Patterns + Relationships
          ↓
       Insights
```

<div dir="rtl">

لكن الوصول إلى **Insight** لا يمثل نهاية العمل.

يحتاج **Data Scientist** إلى توصيل ما اكتشفه بطريقة يستطيع الآخرون فهمها، وهنا يأتي دور **Data Visualization** و**Storytelling**.

تصل النتائج بعد ذلك إلى **Stakeholders**، ويمكن استخدامها لدعم **Decision or Action**.

وبذلك ترتبط أفكار الوحدة كلها في رحلة واحدة:

</div>

```text
Problem / Question
        ↓
Curiosity
        ↓
Collect the Right Data
        ↓
Structured / Unstructured Data
        ↓
Tools + Analysis + Algorithms
        ↓
Patterns & Relationships
        ↓
Insights
        ↓
Data Visualization + Storytelling
        ↓
Stakeholders
        ↓
Decision / Action
```
