# Lora

## UI/UX Design System

هذا المستودع يحتوي على **Design System** الخاص بـLora، والذي يهدف إلى تنظيم وتوحيد تجربة الـUI/UX للمنتج، وتسهيل تطوير الواجهات بشكل consistent وقابل للتوسع.

الـDesign System هو المرجع الأساسي الذي يجمع القواعد والمكونات والـpatterns المستخدمة في تصميم Lora.

---

## Repository Structure

```text
lora/
│
├── README.md
│
├── docs/
│   ├── design-system.md
│   └── reference-examples.md
│
└── images/
    ├── primitive-colors.png
    ├── semantic-colors.png
    ├── dark-semantic-colors.png
    ├── components.png
    ├── icons.png
    └── typography.png
```

---

## Documentation

### Design System

الملف الأساسي الذي يوضح طريقة بناء وتنظيم الـDesign System، ويغطي:

- Design Direction
- Foundations
- Colors & Tokens
- Typography
- Light / Dark Themes
- Arabic / English
- RTL / LTR
- Core Components
- Lora Components
- Figma Organization
- Accessibility
- Responsive Behavior
- Developer Handoff

**[→ Design System Guide](docs/design-system.md)**

### Reference Examples

أمثلة مرجعية تساعد الفريق على فهم طريقة تنظيم الـDesign System، خصوصًا:

- Primitive Colors
- Semantic Colors
- Dark Theme
- Components
- Icons
- Typography

> الـReferences الموجودة هنا للتوضيح والإلهام فقط، وليست تصميمات أو قرارات نهائية لـLora.

**[→ Reference Examples](docs/reference-examples.md)**

---

## Design System Principles

يعتمد نظام Lora على مجموعة من المبادئ الأساسية:

- **Consistency** — توحيد تجربة المستخدم عبر الواجهات.
- **Reusability** — إعادة استخدام المكونات بدل إنشاء نسخ متكررة.
- **Scalability** — بناء نظام قابل للتوسع مع نمو المشروع.
- **Accessibility** — مراعاة سهولة الاستخدام وإمكانية الوصول.
- **Responsive Design** — دعم مختلف أحجام الشاشات.
- **Localization** — دعم العربية والإنجليزية.
- **RTL / LTR** — دعم اتجاهي الواجهة.
- **Light / Dark** — تصميم النظام مع مراعاة الـThemes من البداية.

---

## Design → Development

الـDesign System مصمم بحيث يكون قابلًا للترجمة بسهولة من التصميم إلى الكود:

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

الهدف هو أن يكون الـDesign واضحًا ومنظمًا بما يكفي بحيث لا يحتاج الـDeveloper إلى تخمين:

- الألوان.
- Typography.
- Spacing.
- Sizes.
- Variants.
- States.
- Responsive Behavior.
- Theme Behavior.

---

## Scope

هذا المستودع يركز على **Design System وUI/UX Documentation** الخاص بـLora.

أما الـFrontend implementation والـapplication code فهي مشاريع منفصلة.

---

## Important Note

> **Reference ≠ Final Design**

الأمثلة الموجودة في `reference-examples.md` لا تمثل الشكل النهائي لـLora، ولا تفرض ألوانًا أو Fonts أو Components معينة.

الهدف منها هو فهم **طريقة التفكير والتنظيم**، ثم بناء النظام النهائي بما يتناسب مع:

- Lora Brand
- Target Audience
- User Experience
- Accessibility
- Technical Requirements
