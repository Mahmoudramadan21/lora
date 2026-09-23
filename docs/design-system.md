# نظام تصميم Lora

## Lora UI/UX — Design System Guide

> **الهدف من الملف:** توضيح الطريقة التي سنبني بها نظام التصميم الخاص بـLora، وما الذي نحتاجه من فريق الـUI/UX، خطوة بخطوة وبشكل بسيط وواضح.

---

# 01. قبل ما نبدأ

## إحنا بنعمل إيه؟

قبل ما نبدأ في تصميم أي واجهة، محتاجين الأول نبني **نظام تصميم — Design System** يكون هو الأساس لكل شغل الـUI/UX في Lora.

بمعنى أبسط:

بدل ما كل شاشة تتصمم لوحدها، نحدد الأول:

- شكل الألوان.
- شكل الخطوط.
- المسافات.
- أحجام العناصر.
- شكل الـButtons.
- شكل الـInputs.
- شكل الـCards.
- حالات العناصر المختلفة.
- طريقة التعامل مع الـLight وDark.
- طريقة التعامل مع العربي والإنجليزي.
- وطريقة ترتيب الـComponents داخل Figma.

وبعد كده نستخدم النظام ده في باقي التصميم.

---

# 02. ليه بنبدأ بالـDesign System؟

الهدف مش إننا نزود الشغل أو نعقده.

بالعكس، الهدف إن الشغل بعد كده يبقى أسهل.

مثال بسيط:

لو عندنا 20 شاشة وكل شاشة فيها Button مختلف، هيبقى عندنا مشكلة في:

- الشكل.
- الحجم.
- الألوان.
- الـSpacing.
- الـStates.

لكن لو عملنا Button واحد كنظام:

```text
Button
├── Primary
├── Secondary
├── Outline
└── Ghost
```

بعد كده أي مكان يحتاج Button يستخدم نفس النظام.

وده يخلي التصميم:

**أوضح + أسرع + أكثر تناسقًا + أسهل في التنفيذ.**

---

# 03. مهم جدًا: مش مطلوب مننا نكون Experts في كل حاجة

الهدف من الملف ده مش إننا نعمل حاجة معقدة.

إحنا محتاجين نبني النظام **بشكل منظم خطوة بخطوة**.

مش مطلوب إن كل حاجة تكون Perfect من أول مرة.

المهم:

- نفهم إحنا بنعمل إيه.
- نمشي بترتيب.
- ناخد قرارات واضحة.
- نراجع الشغل مع بعض.
- ونبني النظام بالتدريج.

---

# 04. دور فريق الـUI/UX

فريق الـUI/UX هو المسؤول عن القرارات البصرية والتجربة التصميمية.

يعني أنتم اللي هتحددوا مثلًا:

- اللون المناسب.
- الـFont المناسب.
- شكل الـButton.
- شكل الـCard.
- الـSpacing.
- الـRadius.
- شكل الـIcons.
- شكل الـComponents.
- طريقة ظهور الـStates.

أنا هنا مش هحدد لكم:

> استخدموا اللون ده، والـFont ده، والـRadius ده.

لكن هحدد لكم:

> إحنا محتاجين نظام يكون قابل لإعادة الاستخدام، ويدعم Light/Dark وArabic/English، ويكون سهل التنفيذ بعد كده.

يعني:

**الـUI/UX Team يحدد الشكل.**

**الـDesign System يحدد طريقة تنظيم الشكل واستخدامه.**

---

# 05. الصورة الكبيرة

هنمشي بالترتيب ده:

```text
01. اتجاه التصميم
        ↓
02. الأساسيات
        ↓
03. الـDesign Tokens
        ↓
04. Light / Dark + Arabic / English
        ↓
05. نظام الـComponents
        ↓
06. الـCore Components
        ↓
07. الـLora Components
        ↓
08. تنظيم Figma
        ↓
09. التوثيق والتسليم
```

مش محتاجين نحفظ الترتيب.

الفكرة ببساطة:

> **نبني الأساس الأول، وبعد كده نبني العناصر فوقه.**

---

# 06. المرحلة الأولى — اتجاه التصميم

## Design Direction

### الهدف

في البداية نحتاج نحدد:

> **إحنا عاوزين Lora شكلها وإحساسها يبقى عامل إزاي؟**

مش محتاجين نحدد كل التفاصيل.

محتاجين فقط نتفق على الاتجاه العام.

---

## 6.1 شخصية Lora

محتاجين نحدد الصفات اللي المفروض المستخدم يحس بيها لما يشوف Lora.

مثلًا:

- راقية.
- نظيفة.
- موثوقة.
- أصلية.
- عصرية.
- هادئة.
- أنيقة.
- سهلة.
- Customer-Centric.

دي مش إجابات نهائية مفروضة.

المطلوب من الفريق هو التفكير:

> إزاي نحول الصفات دي إلى تصميم حقيقي؟

---

## 6.2 الاتجاه البصري

محتاجين نحدد بشكل عام:

- شكل الألوان.
- شكل الخطوط.
- شكل الـCards.
- شكل الـButtons.
- كمية الـWhitespace.
- شكل الـBorders.
- شكل الـShadows.
- شكل الـIcons.
- طريقة استخدام الصور.

مش مطلوب تفاصيل دقيقة في المرحلة دي.

---

## 6.3 الـMoodboard

ممكن نجمع References تساعدنا نفهم الاتجاه.

مثلًا:

- مواقع.
- Designs.
- Components.
- Typography.
- صور.
- Color combinations.

الهدف من الـReferences:

> نفهم الاتجاه.

مش:

> نقلد تصميم موجود.

---

## المطلوب في نهاية المرحلة

نكون وصلنا إلى:

- اتجاه بصري واضح.
- شخصية واضحة للـBrand.
- مجموعة References.
- مبادئ بسيطة نرجع لها أثناء التصميم.

---

# 07. المرحلة الثانية — أساسيات التصميم

## Foundations

بعد ما نحدد الاتجاه العام، نبدأ نحدد الأساسيات اللي هنستخدمها في كل التصميم.

---

# 07.1 الألوان

## Colors

محتاجين نحدد نظام الألوان الخاص بـLora.

يشمل مثلًا:

- ألوان الـBrand.
- ألوان الخلفيات.
- ألوان الـText.
- ألوان الـBorders.
- ألوان الـSurfaces.
- ألوان الحالات.

مثل:

- Success.
- Warning.
- Error.
- Info.

المهم هنا:

> مش لازم يكون عندنا ألوان كتير.

المهم يكون عندنا نظام واضح.

---

# 07.2 الخطوط

## Typography

محتاجين نحدد:

- الـFont.
- أحجام الخطوط.
- الـFont Weights.
- الـLine Heights.
- أحجام الـHeadings.
- أحجام الـBody Text.
- أحجام الـLabels.
- أحجام الـButtons.

ومهم جدًا إننا نجرب الخط مع:

**العربي + الإنجليزي.**

لأن الخط اللي شكله كويس بالإنجليزي مش شرط يكون مناسب للعربي.

---

# 07.3 المسافات

## Spacing

بدل ما كل مرة نختار:

```text
13px
17px
21px
29px
```

نحتاج يكون عندنا نظام للمسافات.

مثلًا:

```text
Small
Medium
Large
XL
```

أو أي نظام مناسب يختاره الفريق.

المهم:

> المسافات تكون منظمة ومتكررة، مش عشوائية.

---

# 07.4 أحجام العناصر

## Sizing

محتاجين نحدد أحجام مناسبة للعناصر.

مثلًا:

```text
Small
Medium
Large
```

وده ممكن يظهر في:

- Buttons.
- Inputs.
- Icons.
- Controls.

---

# 07.5 الـBorder Radius

محتاجين نحدد شكل الـCorners.

مثلًا:

```text
Small
Medium
Large
Full
```

والهدف إن الـUI كله يحس إنه جزء من نفس النظام.

---

# 07.6 الـShadows

محتاجين نحدد طريقة استخدام الـShadows.

مثلًا:

```text
No Shadow
Small
Medium
Large
```

ومش لازم كل Component يبقى عليه Shadow.

المهم نحدد:

> إمتى نستخدمه؟ وإمتى لأ؟

---

# 07.7 الـIcons

محتاجين نحدد:

- نوع الـIcon Style.
- شكل الـIcons.
- أحجام الـIcons.
- الـStroke.
- طريقة استخدامها.

ومهم جدًا إننا نراعي الـRTL.

لأن بعض الـIcons بتتغير حسب الاتجاه.

---

# 07.8 الـGrid والـLayout

محتاجين نحدد بشكل عام:

- عرض الـContainer.
- الـMargins.
- الـColumns.
- الـGutters.
- طريقة توزيع المحتوى.

الهدف:

> أي شاشة بعد كده تستخدم نفس قواعد الـLayout.

---

# 07.9 الـResponsive

محتاجين نفكر من البداية في:

- Desktop.
- Tablet.
- Mobile.

مش لازم نرسم كل حاجة في كل الأجهزة من البداية.

لكن لازم نحدد:

> العنصر بيتصرف إزاي لما الشاشة تصغر؟

---

# 08. المرحلة الثالثة — Design Tokens

## يعني إيه Design Tokens؟

ببساطة جدًا:

الـDesign Token هو **اسم بنستخدمه لقيمة تصميم معينة**.

بدل ما نقول:

```text
استخدم اللون #XXXXXX
```

نقول:

```text
استخدم لون الـPrimary
```

وده بيساعدنا جدًا بعد كده في الـLight/Dark والـFrontend.

---

# 08.1 Primitive Tokens

دي القيم الأساسية.

مثلًا:

```text
Color
Spacing
Radius
Font Size
Shadow
```

دي تعتبر اللبنات الأساسية للنظام.

---

# 08.2 Semantic Tokens

دي أهم بالنسبة للاستخدام.

بدل ما نقول:

```text
Gray 900
```

نقول:

```text
Text Primary
```

وبدل:

```text
Gray 100
```

نقول:

```text
Background Surface
```

مثلًا:

```text
Background
Text Primary
Text Secondary
Border
Primary
Secondary
Success
Warning
Error
```

الميزة هنا إن نفس الاسم ممكن ياخد قيمة مختلفة في Light وDark.

---

# 08.3 الفكرة ببساطة

نريد الوصول إلى:

```text
القيم الأساسية
      ↓
المعنى
      ↓
الـComponent
```

مثال:

```text
Color
  ↓
Primary
  ↓
Button
```

---

# 09. المرحلة الرابعة — Light / Dark + Arabic / English

دي نقطة أساسية في Lora.

من البداية لازم النظام يكون قادر يدعم:

- Light Theme.
- Dark Theme.
- English.
- Arabic.

---

# 09.1 Light Theme

لازم كل الـComponents الأساسية تكون واضحة في الـLight Mode.

نراجع:

- Background.
- Text.
- Borders.
- Buttons.
- Inputs.
- Cards.
- Dialogs.
- States.

---

# 09.2 Dark Theme

الـDark Mode مش مجرد:

> نغير الخلفية من أبيض لأسود.

لازم نحدد نظام Dark كامل.

مثلًا:

```text
Background
Surface
Text
Border
Primary
Status Colors
```

والـComponents نفسها تفضل هي نفسها.

اللي يتغير هو الـTokens.

---

# 09.3 English — LTR

الإنجليزي هيكون:

**LTR — Left to Right**

ونراجع:

- Navigation.
- Text alignment.
- Icons.
- Forms.
- Breadcrumb.
- Pagination.
- Layout.

---

# 09.4 Arabic — RTL

العربي هيكون:

**RTL — Right to Left**

ومهم جدًا:

> الـRTL مش مجرد إننا نكتب الكلام بالعربي.

لازم نشوف:

- ترتيب العناصر.
- Alignment.
- Navigation.
- Forms.
- Icons.
- Breadcrumb.
- Pagination.
- اتجاه المحتوى.
- الـSpacing.

---

# 09.5 مش هنعمل 4 Designs منفصلة

مش عايزين:

```text
English Design
Arabic Design
Light Design
Dark Design
```

كل واحد منفصل.

عايزين:

```text
Design System واحد

يدعم:

Light / Dark
+
LTR / RTL
```

---

# 09.6 اختبار الـ4 حالات

أي Component أساسي لازم نشوفه في:

| Theme | Direction |
| ----- | --------- |
| Light | LTR       |
| Light | RTL       |
| Dark  | LTR       |
| Dark  | RTL       |

مش لازم كل Component يكون له Design مختلف.

المطلوب إن نفس النظام يشتغل في الحالات المختلفة.

---

# 10. المرحلة الخامسة — نظام الـComponents

## Component System

هنا نبدأ نبني العناصر اللي هنستخدمها في التصميم.

لكن قبل ما نبدأ، مهم نفهم فكرة بسيطة.

---

# 10.1 الـComponent الواحد ممكن يكون له Variants

مثلًا الـButton:

```text
Button

Primary
Secondary
Outline
Ghost
```

بدل ما نعمل:

```text
Primary Button
Secondary Button
Outline Button
Ghost Button
```

كعناصر منفصلة.

---

# 10.2 الـComponent ممكن يكون له Sizes

مثل:

```text
Small
Medium
Large
```

حسب احتياج الـComponent.

---

# 10.3 الـComponent له States

مثلًا الـButton ممكن يكون:

```text
Default
Hover
Focus
Disabled
Loading
```

والـInput ممكن يكون:

```text
Default
Focus
Error
Disabled
Success
```

مش لازم كل Component يكون عنده كل الحالات.

المهم:

> نحدد الحالات اللي فعلًا يحتاجها.

---

# 10.4 الـComponent يكون Flexible

ممكن الـComponent يحتوي على:

- Text.
- Icon.
- Optional content.

وممكن يتغير حسب الاستخدام.

الهدف:

> نعمل Component مرن بدل ما نعمل Components كثيرة جدًا.

---

# 11. الفكرة اللي هنمشي عليها مع الـComponents

إحنا هنستفيد من فلسفة **shadcn/ui** في طريقة بناء الـComponents.

مش المقصود إننا نقلد شكله.

المقصود إننا نستخدم نفس الأفكار الأساسية:

- Components قابلة لإعادة الاستخدام.
- Variants.
- Sizes.
- States.
- Composition.
- Properties.
- Tokens.
- Accessibility.

---

# 12. أنواع الـComponents

هنقسم الـComponents لنوعين رئيسيين:

```text
Core Components
        +
Lora Components
```

---

# 12.1 الـCore Components

دي العناصر العامة اللي ممكن نستخدمها في أي مكان.

مثل:

### Actions

- Button.
- Icon Button.
- Link.

### Forms

- Input.
- Textarea.
- Select.
- Checkbox.
- Radio.
- Switch.
- Label.

### Navigation

- Tabs.
- Breadcrumb.
- Pagination.
- Dropdown.

### Feedback

- Alert.
- Toast.
- Skeleton.
- Empty State.
- Error State.

### Overlays

- Dialog.
- Drawer.
- Popover.
- Tooltip.

### Data Display

- Card.
- Badge.
- Avatar.
- Separator.

مش لازم نعمل كل حاجة مرة واحدة.

نبدأ باللي نحتاجه ونبني النظام تدريجيًا.

---

# 13. Lora Components

دي Components مرتبطة بطبيعة Lora كـBeauty & Personal Care E-commerce.

مثل:

- Product Card.
- Product Badge.
- Price.
- Rating.
- Quantity Selector.
- Product Filter.

---

# 13.1 مثال — Product Card

ممكن يحتوي على:

```text
Product Card
├── Image
├── Brand
├── Product Name
├── Price
├── Rating
├── Badge
└── Action
```

لكن الشكل النهائي وطريقة الترتيب يحددها فريق الـUI/UX.

المطلوب مننا فقط إننا نفكر فيه كـ**Reusable Component**.

---

# 13.2 مثال — Price

ممكن يحتاج:

- Current Price.
- Old Price.
- Discount.
- Currency.

والفريق يحدد أفضل طريقة لعرضهم.

---

# 13.3 مثال — Rating

ممكن يحتوي على:

- Stars.
- Rating Value.
- Review Count.

---

# 14. إمتى نعمل Component جديد؟

قبل ما نعمل Component، نسأل:

### السؤال الأول

> هل العنصر ده بيتكرر؟

لو لأ، ممكن ما يحتاجش Component مستقل.

### السؤال الثاني

> هل عنده Variants أو States؟

لو نعم، ممكن يكون Component مناسب.

### السؤال الثالث

> هل هنحتاج نستخدمه في أماكن مختلفة؟

لو نعم، ده سبب قوي لعمل Component.

---

# 15. مهم: ما نعملش Components زيادة عن اللزوم

مش الهدف إن يكون عندنا:

```text
100 Component
```

الهدف إن يكون عندنا:

> Components مفيدة، واضحة، وقابلة لإعادة الاستخدام.

---

# 16. المرحلة السادسة — تنظيم Figma

بعد ما نبدأ بناء الـSystem، لازم ملف Figma نفسه يكون منظم.

ممكن يكون بالشكل التالي:

```text
Lora Design System

01 — Overview

02 — Foundations
    ├── Colors
    ├── Typography
    ├── Spacing
    ├── Radius
    ├── Shadows
    └── Icons

03 — Tokens
    ├── Primitive
    └── Semantic

04 — Themes
    ├── Light
    └── Dark

05 — Core Components
    ├── Actions
    ├── Forms
    ├── Navigation
    ├── Feedback
    └── Overlays

06 — Lora Components
    ├── Product
    ├── Commerce
    └── Other

07 — Documentation
```

ده مجرد Structure مقترح.

الفريق ممكن يحسنه طالما حافظنا على التنظيم.

---

# 17. Figma Variables

مهم نستخدم **Figma Variables** للقيم اللي محتاجين نتحكم فيها مركزيًا.

خصوصًا:

- Colors.
- Spacing.
- Radius.
- Sizes.

والـColors تحديدًا مهمة جدًا مع:

**Light + Dark**

---

# 18. Figma Components

الـComponents القابلة لإعادة الاستخدام لازم تكون فعلًا Components في Figma.

وممكن نستخدم:

- Variants.
- Component Properties.
- Boolean Properties.
- Text Properties.
- Instance Swap.

مش لازم نستخدم كل حاجة في كل Component.

نستخدمها لما تكون مفيدة.

---

# 19. Auto Layout

يفضل استخدام **Auto Layout** كأساس للـComponents.

لأنه يساعدنا في:

- تغيير المحتوى.
- تغيير طول النص.
- Responsive behavior.
- إعادة الاستخدام.
- الحفاظ على الـSpacing.

---

# 20. توثيق الـComponents

مش لازم نكتب Documentation ضخمة.

لكن الـComponents المهمة يفضل يكون واضح فيها:

### اسم الـComponent

مثال:

```text
Button
```

### استخدامه

متى نستخدمه؟

### Variants

ما هي الأنواع الموجودة؟

### States

ما هي الحالات؟

### Sizes

ما هي الأحجام؟

### ملاحظات

هل له سلوك خاص؟

---

# 21. مثال بسيط لتوثيق Component

## Button

### الاستخدام

يستخدم لتنفيذ Action واضح.

### Variants

- Primary.
- Secondary.
- Outline.
- Ghost.

### Sizes

- Small.
- Medium.
- Large.

### States

- Default.
- Hover.
- Focus.
- Disabled.
- Loading.

### ملاحظات

يجب استخدام الـVariant المناسب حسب أهمية الـAction.

---

# 22. الـResponsive Behavior

مش المطلوب إننا نرسم كل Component على كل مقاس شاشة بشكل منفصل.

المطلوب إننا نفهم:

> الـComponent بيتصرف إزاي لما المساحة تتغير؟

مثال:

Button:

```text
Desktop
→ Normal

Mobile
→ ممكن يفضل بنفس الشكل
→ أو يصبح Full Width حسب الاستخدام
```

Product Card:

```text
Desktop
→ Card عادي

Mobile
→ مساحة أقل
→ Text wrapping
→ Image size يتغير
```

المهم إن السلوك يكون واضح.

---

# 23. Accessibility

مش محتاجين ندخل في تفاصيل صعبة.

لكن من البداية نراعي:

- الـText يكون مقروء.
- الـContrast مناسب.
- الـFocus واضح.
- الـButtons سهلة الاستخدام.
- الـTouch Targets مناسبة.
- الـError واضح.
- الـForms لها Labels واضحة.
- الـDisabled State واضح.

---

# 24. Definition of Done

قبل ما نقول إن Component خلص، نراجع:

- [ ] عارفين الـComponent بيستخدم في إيه.
- [ ] الـVariants واضحة.
- [ ] الـStates المطلوبة موجودة.
- [ ] الـSizes موجودة عند الحاجة.
- [ ] الـSpacing متوافق مع النظام.
- [ ] الألوان مبنية على Tokens.
- [ ] شغال في Light.
- [ ] شغال في Dark.
- [ ] اتراجع في LTR.
- [ ] اتراجع في RTL.
- [ ] الـResponsive behavior واضح.
- [ ] الـComponent منظم في Figma.
- [ ] الـAuto Layout مستخدم عند الحاجة.
- [ ] مفيش قيم عشوائية بدون سبب.

مش لازم كل Component يحقق كل نقطة حرفيًا.

المقصود إننا نستخدم الـChecklist كـ**Quality Check**.

---

# 25. Developer Handoff

في النهاية، لازم الـDesign System يكون مفهوم للـFrontend Developer.

الهدف:

```text
Figma
  ↓
Design Tokens
  ↓
CSS Variables
  ↓
Tailwind CSS
  ↓
shadcn/ui
  ↓
Next.js
```

يعني لما أبدأ تنفيذ الـFrontend:

ما أكونش محتاج أخمن:

- اللون.
- الحجم.
- الـSpacing.
- الـVariant.
- الـState.
- الـResponsive behavior.

كل ده يكون واضح من الـDesign System.

---

# 26. أهم حاجة في الـHandoff

مش مطلوب من فريق الـUI/UX يعرف يكتب Code.

المطلوب فقط إن التصميم يكون:

**واضح + منظم + قابل للتنفيذ.**

يعني لما أشوف:

```text
Button
Primary
Medium
Disabled
```

أعرف بالضبط الشكل والسلوك المطلوب.

---

# 27. قواعد بسيطة نمشي عليها

## القاعدة الأولى

**نبني النظام قبل ما نكبر في عدد الـScreens.**

---

## القاعدة الثانية

**أي حاجة بتتكرر، نفكر هل تستحق تكون Component.**

---

## القاعدة الثالثة

**أي قيمة تتكرر، نحاول نخليها جزء من النظام.**

مثل:

- Colors.
- Spacing.
- Radius.
- Typography.

---

## القاعدة الرابعة

**Light وDark يكونوا جزء من النظام من البداية.**

مش نخلص Light وبعدها نحاول نضيف Dark.

---

## القاعدة الخامسة

**Arabic وEnglish يكونوا جزء من النظام من البداية.**

مش نخلص English وبعدها نبدأ نصلح RTL.

---

## القاعدة السادسة

**مش لازم كل حاجة تكون معقدة.**

لو Component بسيط، نخليه بسيط.

---

## القاعدة السابعة

**مش لازم نعمل كل Components مرة واحدة.**

نبدأ بالأساسيات، وبعدها نضيف اللي نحتاجه.

---

# 28. الشكل النهائي اللي عاوزين نوصل له

في النهاية نريد:

```text
Lora Design System
│
├── Design Direction
│
├── Foundations
│
├── Tokens
│
├── Light / Dark
│
├── LTR / RTL
│
├── Core Components
│
├── Lora Components
│
├── Figma Organization
│
└── Documentation
```

ويكون النظام:

**واضح**

**متناسق**

**قابل لإعادة الاستخدام**

**سهل التطوير**

**يدعم Light / Dark**

**يدعم Arabic / English**

**يدعم RTL / LTR**

**وقابل للتحويل إلى Frontend بسهولة**

---

# 29. الخلاصة

المطلوب مننا في المرحلة دي مش إننا نطلع بأجمل Screens.

المطلوب إننا نبني **الأساس اللي هيخلي كل الـScreens بعد كده متناسقة وسهلة التصميم والتنفيذ.**

نشتغل بالترتيب:

```text
اتجاه التصميم
      ↓
الأساسيات
      ↓
Tokens
      ↓
Light / Dark
      ↓
Arabic / English
      ↓
Components
      ↓
Figma Organization
      ↓
Documentation
      ↓
Developer Handoff
```

والأهم:

> **إحنا مش بنحاول نعمل نظام ضخم ومعقد.**
>
> **إحنا بنبني نظام بسيط ومنظم، ونكبره تدريجيًا مع المشروع.**

---

# 30. Final Goal

الهدف النهائي إن أي شخص في الفريق يقدر يشوف الـDesign System ويعرف:

> **إيه اللي موجود؟**

> **إمتى أستخدمه؟**

> **أستخدمه إزاي؟**

> **إيه الحالات المختلفة بتاعته؟**

> **وإزاي يفضل متناسق مع باقي Lora؟**

وده هو الأساس اللي هنقدر نبني عليه باقي تجربة Lora بشكل منظم.
