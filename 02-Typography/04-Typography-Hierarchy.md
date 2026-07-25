# Typography Hierarchy

## Topics Covered

* Visual Hierarchy
* Heading System (H1–H6)
* Display Text
* Body Text
* Caption
* Labels
* Font Size Hierarchy
* Font Weight Hierarchy
* Color Hierarchy
* Spacing Hierarchy
* Building a Scalable Type System

---

## 1. Visual Hierarchy

Visual hierarchy determines the order in which users notice and read information.

Typography creates hierarchy mainly through:

* Size
* Font weight
* Color
* Spacing

Example:

```text
Senior UI/UX Designer      ← Highest importance
Zoho                       ← Secondary information
Chennai · Full-time        ← Supporting information
Posted 2 days ago          ← Metadata
```

The goal is to make the interface easy to scan without forcing users to carefully read every piece of text.

### Key Principle

> Important information should receive more visual emphasis, while supporting information should receive less emphasis.

---

## 2. Heading System (H1–H6)

Headings organize content into different levels of importance.

| Heading | Example Size | Typical Purpose             |
| ------- | -----------: | --------------------------- |
| H1      |         32px | Main page or screen heading |
| H2      |         28px | Major section heading       |
| H3      |         24px | Section heading             |
| H4      |         20px | Subsection heading          |
| H5      |         18px | Smaller subsection          |
| H6      |         16px | Lowest heading level        |

These sizes are examples, not fixed rules.

Different products and design systems can use different sizes.

### Heading Hierarchy

```text
H1
 └── H2
      └── H3
           └── H4
                └── H5
                     └── H6
```

Not every application needs all six heading levels.

A simple mobile application may only require:

```text
Heading / Large
Heading / Medium
Heading / Small
```

### Important: Heading Size vs Text Role

Font size alone does not determine whether something is a heading or body text.

For example:

```text
Account Settings     → 16px Semibold → Small Heading

Manage your account  → 16px Regular  → Body
```

Both use `16px`, but they have different purposes.

A heading introduces or organizes content.

Body text communicates normal readable content.

Therefore:

> Determine the role of the text first, then choose its typography style.

---

## 3. Display Text

Display text is the largest and most visually prominent typography in a design.

It is usually stronger than normal headings.

Example:

```text
Find your
next opportunity.
```

Display text is commonly used for:

* Hero sections
* Landing pages
* Onboarding screens
* Marketing messages
* Large statistics
* Major promotional content

A type system may contain:

```text
Display / Large
Display / Medium
Display / Small
```

Display text should be used selectively. If too many elements use strong typography, the interface loses hierarchy.

---

## 4. Body Text

Body text is used for normal readable content.

Examples include:

* Descriptions
* Paragraphs
* Instructions
* Articles
* Product information
* Job descriptions

Example:

```text
About the Role

We are looking for a product designer who can work
closely with our engineering and product teams.
```

`About the Role` is a heading.

The paragraph below it is body text.

A type system may contain:

| Style         | Example Size |
| ------------- | -----------: |
| Body / Large  |         18px |
| Body / Medium |         16px |
| Body / Small  |         14px |

Body text usually uses Regular font weight because readability is more important than visual emphasis.

---

## 5. Caption

Captions provide small supporting information or metadata.

Examples:

```text
Posted 2 days ago

Updated yesterday

120 applicants

Last active 5 minutes ago
```

Captions are usually:

* Smaller than body text
* Regular weight
* Lower visual emphasis

Example:

```text
Caption → 12px Regular
```

Caption text should still maintain sufficient readability and contrast.

Small text should not automatically mean very light text.

---

## 6. Labels

Labels are functional text used to identify controls, actions, or categories.

### Form Labels

```text
Email Address
[________________]

Password
[________________]
```

### Button Labels

```text
Apply Now
```

### Navigation Labels

```text
Home
Pipeline
Calendar
Profile
```

### Other Examples

Labels are also commonly used in:

* Tabs
* Filters
* Chips
* Input fields
* Buttons
* Navigation
* Menus

### Body vs Label

Body text communicates content.

Labels identify or operate interface elements.

Example:

```text
Email Address                     ← Label

We'll send updates to this email. ← Body
```

---

## 7. Font Size Hierarchy

Different font sizes help communicate different levels of importance.

Example type scale:

```text
Display          40px

Heading Large    32px
Heading Medium   24px
Heading Small    20px

Body Large       18px
Body Medium      16px
Body Small       14px

Caption          12px
```

These values are examples rather than universal rules.

The important principle is consistency.

Avoid randomly choosing font sizes for individual screens.

Instead of:

```text
31px
27px
23px
19px
17px
```

define a consistent type scale and reuse it throughout the product.

---

## 8. Font Weight Hierarchy

Font weight can create hierarchy even when two pieces of text use the same font size.

Common font weights:

| Weight   | Typical Value |
| -------- | ------------: |
| Regular  |           400 |
| Medium   |           500 |
| Semibold |           600 |
| Bold     |           700 |

Example:

```text
Account Settings     → 16px Semibold
Manage your account  → 16px Regular
```

Both elements use the same size, but the heading receives more emphasis through font weight.

Avoid making everything bold.

If too many elements use strong font weights, they begin competing for attention.

---

## 9. Color Hierarchy

Text color can also communicate importance.

A design system may define:

```text
Text / Primary
Text / Secondary
Text / Tertiary
Text / Disabled
Text / Error
Text / Success
```

Example:

```text
Product Designer       → Primary
Zoho                   → Primary / Secondary
Chennai · Full-time    → Secondary
Posted yesterday       → Tertiary
```

Primary text receives stronger contrast.

Supporting information receives lower emphasis.

However, lower emphasis should never make text difficult to read.

---

## 10. Spacing Hierarchy

Spacing helps users understand which pieces of information belong together.

Related elements should generally have smaller spacing.

Separate groups or sections should generally have larger spacing.

Example:

```text
About the Role
↓ 8px
Body description

↓ 24px or 32px

Responsibilities
↓ 8px
Body description
```

This creates two clear groups:

```text
[Heading + Related Content]

[Heading + Related Content]
```

### Spacing Should Not Be Random

Use a predefined spacing system.

Example:

```text
4px
8px
16px
24px
32px
40px
48px
```

Possible usage:

| Relationship              | Typical Spacing |
| ------------------------- | --------------: |
| Very tightly related      |             4px |
| Heading + supporting text |             8px |
| Related elements          |          8–16px |
| Separate groups           |         16–24px |
| Major sections            |        24–32px+ |

These values are guidelines rather than fixed rules.

The important principle is:

> Choose spacing from the design system based on the relationship between elements instead of inventing random values.

---

## 11. Building a Scalable Type System

A scalable type system defines reusable typography styles instead of styling text individually on every screen.

Example:

| Style            | Size | Weight   | Purpose            |
| ---------------- | ---: | -------- | ------------------ |
| Display / Large  | 48px | Semibold | Hero content       |
| Display / Small  | 40px | Semibold | Major emphasis     |
| Heading / Large  | 32px | Semibold | Main heading       |
| Heading / Medium | 24px | Semibold | Section heading    |
| Heading / Small  | 20px | Medium   | Small section      |
| Body / Large     | 18px | Regular  | Large body content |
| Body / Medium    | 16px | Regular  | Default body       |
| Body / Small     | 14px | Regular  | Supporting content |
| Label / Medium   | 14px | Medium   | UI controls        |
| Caption          | 12px | Regular  | Metadata           |

These can be created as reusable text styles in Figma.

Instead of manually applying:

```text
Inter
16px
Regular
24px line height
```

every time, apply:

```text
Body / Medium
```

This improves:

* Consistency
* Scalability
* Maintainability
* Collaboration
* Design-to-development handoff

If the typography system changes later, the reusable styles can be updated instead of manually changing every individual text layer.

---

## Typography Role Mental Model

Before choosing a font size, determine what job the text performs.

```text
Major visual attention
        ↓
     DISPLAY

Page or section title
        ↓
     HEADING

Normal readable content
        ↓
       BODY

UI control or identification
        ↓
      LABEL

Supporting metadata
        ↓
     CAPTION
```

Then use:

```text
Size
+
Weight
+
Color
+
Spacing
```

to establish the appropriate level of visual importance.

---

## Key Principle

Do not identify typography only by its font size.

For example:

```text
16px Semibold → Could be a small heading

16px Regular  → Could be body text

14px Medium   → Could be a label
```

Typography should be selected according to the **purpose and hierarchy of the content**, not simply according to its size.

A strong typography system answers two questions:

1. What job is this text doing?
2. How important is it compared with the surrounding text?

Once those are clear, the appropriate typography style can be selected consistently.
