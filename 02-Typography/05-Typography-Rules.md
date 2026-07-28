# 05 - Typography Rules

## Topics Covered

* Line Length
* Line Height
* Letter Spacing
* Word Spacing
* Paragraph Spacing
* Alignment
* Readability
* White Space
* Contrast
* Responsive Typography
* Best Practices
* Common Mistakes

---

# Typography Rules

Typography rules ensure text is **readable**, **consistent**, and **comfortable** across different devices. Even with a great font, poor spacing and alignment can make an interface difficult to use.

---

# 1. Line Length

## What is Line Length?

Line length refers to the number of characters displayed in a single line of text.

### Example

**Too Short**

```text
Design
is
very
important
for
users.
```

**Too Long**

```text
Design is very important because it helps users understand interfaces quickly without becoming confused and therefore every interface should be designed carefully with proper typography and spacing.
```

**Good**

```text
Design is important because it helps users
understand interfaces quickly and comfortably.
```

## Why is it Important?

* Long lines make it difficult to locate the next line.
* Short lines interrupt reading rhythm.
* Proper line length improves reading speed and comprehension.

## Best Practice

| Device  | Recommended Length |
| ------- | ------------------ |
| Desktop | 45–75 characters   |
| Ideal   | 60–70 characters   |
| Mobile  | 30–40 characters   |

## In Figma

Control line length by adjusting the width of the text container.

---

# 2. Line Height (Leading)

## What is Line Height?

Line height is the vertical distance between two lines of text.

### Example

**Too Small**

```text
This is line one.
This is line two.
This is line three.
```

**Good**

```text
This is line one.

This is line two.

This is line three.
```

**Too Large**

```text
This is line one.



This is line two.



This is line three.
```

## Why is it Important?

Proper line height:

* Improves readability
* Reduces visual clutter
* Makes paragraphs easier to scan

## Best Practice

Use **120%–160%** of the font size.

Examples:

| Font Size | Line Height |
| --------- | ----------- |
| 16 px     | 24 px       |
| 18 px     | 28 px       |
| 20 px     | 30 px       |

Most UI designers commonly use **1.5× line height**.

---

# 3. Letter Spacing (Tracking)

## What is Letter Spacing?

Letter spacing is the space between individual letters.

### Example

Normal

```
BUTTON
```

Wide

```
B U T T O N
```

Tight

```
BUTTON
```

## When Should You Use It?

Recommended for:

* Buttons
* Labels
* ALL CAPS text
* Logo design

Generally avoid changing letter spacing in body text.

## Best Practice

| Text Type | Recommendation |
| --------- | -------------- |
| Body Text | 0%             |
| Headings  | 0% to -2%      |
| ALL CAPS  | +2% to +5%     |

---

# 4. Word Spacing

## What is Word Spacing?

Word spacing is the space between words.

### Example

Normal

```
Design System
```

Too Much

```
Design      System
```

Too Little

```
DesignSystem
```

## Best Practice

UI designers generally leave word spacing at the font's default value because professional fonts already include optimized spacing.

---

# 5. Paragraph Spacing

## What is Paragraph Spacing?

Paragraph spacing is the vertical space between paragraphs.

### Example

```text
Paragraph One...

(blank space)

Paragraph Two...
```

## Why is it Important?

Paragraph spacing clearly separates different ideas and improves scanning.

## Best Practice

Paragraph spacing should be **greater than the line height**.

Example:

| Property          | Value |
| ----------------- | ----- |
| Font Size         | 16 px |
| Line Height       | 24 px |
| Paragraph Spacing | 32 px |

---

# 6. Alignment

Alignment determines where text begins within its container.

## Left Alignment

```text
Apple released
its latest
iPhone today.
```

Recommended for almost every English UI.

---

## Center Alignment

```text
Welcome

Start your journey
today.
```

Suitable for:

* Splash screens
* Empty states
* Hero sections
* Quotes

Avoid using center alignment for long paragraphs.

---

## Right Alignment

Commonly used only for right-to-left languages such as Arabic and Hebrew.

---

## Justified Alignment

```text
Apple     released
its      latest
iPhone      today
```

Avoid justified text because uneven spacing reduces readability.

---

# 7. Readability

## What is Readability?

Readability refers to how easily users can read text.

Readability depends on:

* Font selection
* Font size
* Line height
* Contrast
* Line length
* White space

## Improve Readability

* Use clean UI fonts
* Maintain proper spacing
* Keep sufficient contrast
* Avoid very small text
* Use consistent typography

### Recommended Fonts

* Inter
* SF Pro
* Roboto

### Minimum Body Text Size

**16 px**

---

# 8. White Space

## What is White Space?

White space is the empty space surrounding text and interface elements.

It doesn't have to be white—it simply means unused space.

### Without White Space

```text
Title
Subtitle
Paragraph
Button
```

### With White Space

```text
Title

Subtitle


Paragraph


Button
```

## Benefits

* Improves focus
* Reduces clutter
* Makes interfaces feel modern
* Improves readability

Apple products are a well-known example of effective white space usage.

---

# 9. Contrast

## What is Contrast?

Contrast is the visual difference between text and its background.

### Good

Black text on a white background.

### Poor

Light gray text on a white background.

### Avoid

* Yellow on white
* Blue on red
* Light gray on light backgrounds

## WCAG Recommendation

| Text Type   | Minimum Contrast |
| ----------- | ---------------- |
| Normal Text | 4.5 : 1          |
| Large Text  | 3 : 1            |

---

# 10. Responsive Typography

## What is Responsive Typography?

Responsive typography adapts text sizes for different screen sizes.

### Example

| Device  | Heading Size |
| ------- | ------------ |
| Desktop | 48 px        |
| Tablet  | 40 px        |
| Mobile  | 32 px        |

Body text usually remains around **16 px**.

Avoid using desktop-sized headings on mobile screens.

---

# 11. Best Practices

* Keep body text around **16 px**.
* Use only **1–2 font families**.
* Maintain line height between **120%–160%**.
* Keep paragraph widths readable.
* Use sufficient contrast.
* Left-align most text.
* Leave adequate white space.
* Follow a consistent typography scale.
* Create typography tokens instead of random font sizes.

Example Typography Tokens:

```
Display XL
Display L
Heading L
Heading M
Heading S
Body L
Body M
Body S
Caption
```

---

# 12. Common Mistakes

Avoid the following:

* Using multiple font families
* Tiny body text (12 px)
* Extremely long paragraphs
* Poor contrast
* Inconsistent spacing
* Random font sizes
* Center-aligning long paragraphs
* Using ALL CAPS for paragraphs
* Very tight line height
* Very loose line height
* Ignoring mobile responsiveness

---

# Real UI Example

```text
Welcome Back

Sign in to continue to your account.

Email

[________________]

Password

[________________]

Forgot Password?

[ Sign In ]
```

### Why Does This Feel Good?

* Clear typography hierarchy
* Comfortable line height
* Left-aligned content
* Good contrast
* Proper white space
* Consistent spacing
* Responsive font sizes

---

# Quick Reference

| Rule                  | Recommendation                         |
| --------------------- | -------------------------------------- |
| Line Length           | 45–75 characters (30–40 on mobile)     |
| Line Height           | 120%–160% of font size                 |
| Letter Spacing        | 0% for body, +2% to +5% for ALL CAPS   |
| Word Spacing          | Default                                |
| Paragraph Spacing     | Larger than line height                |
| Alignment             | Left for most UI                       |
| Body Font Size        | 16 px                                  |
| Contrast              | Minimum 4.5:1                          |
| White Space           | Use generously                         |
| Responsive Typography | Scale headings for smaller screens     |
| Font Families         | 1–2                                    |
| Typography System     | Use tokens and a consistent type scale |

---

# Key Takeaways

* Good typography improves usability more than decorative fonts.
* Readability should always be the highest priority.
* Use consistent spacing and alignment throughout the interface.
* Keep typography responsive across all devices.
* Follow a design system instead of using random font sizes and spacing values.
