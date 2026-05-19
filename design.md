# 1. Overview

This design system is built to create clean, scalable, and production-ready interfaces with strong usability and restrained visual emphasis.

The overall UI should feel:

- simple
- operational
- product-focused
- reliable
- visually balanced

The primary audience is everyday mobile users who need fast recognition, low cognitive load, and predictable interaction patterns.

Hierarchy should be expressed primarily through spacing, typography, and layout grouping rather than excessive color or decorative effects.

The interface should maintain consistency across all screens while remaining flexible enough for scalable product expansion.

---

# 2. Colors

## 2-1. Primary Color

### Orange (Primary)

Primary Orange is the strongest emphasis color in the system.

Usage:

- Primary CTA
- Active state
- Key interaction highlight
- Important feedback

Rules:

- Do NOT exceed 10~20% usage per screen.
- Avoid decorative or repetitive usage.
- Avoid large filled surfaces.

Primary Scale:

- 100 → #FFFAF9
- 200 → #FFF2ED
- 300 → #FFE4DB
- 400 → #FFCBB8
- 450 → #FF9F7C
- 500 → #FF7949
- 600 → #E86232
- 700 → #D84F1E
- 800 → #BD3B0C
- 900 → #9C2900

---

## 2-2. Secondary Color

### Navy (Secondary)

Usage:

- Secondary emphasis
- Informational UI
- Supporting hierarchy

Restriction:

- Avoid long-form text usage.

Scale:

- 100 → #D0D5DA
- 200 → #A1ABB6
- 300 → #718191
- 400 → #42576D
- 500 → #132D48
- 600 → #091D32

---

## 2-3. Neutral Colors

Neutral Gray should dominate the interface.

Usage:

- Backgrounds
- Containers
- Divider
- Text

Recommended:

- Gray 300~500 → Surface
- Gray 700~800 → Text

Scale:

- 300 → #F7F7F7
- 350 → #F4F4F4
- 400 → #EDEDED
- 450 → #E2E2E2
- 500 → #D2D2D2
- 600 → #AAAAAA
- 700 → #7D7D7D
- 800 → #333333

---

## 2-4. Base Colors

### White

- #FFFFFF

### Black

- #000000

---

## 2-5. Semantic Colors

Semantic colors should consistently communicate system meaning.

### Red

Usage:

- Error
- Alert
- Destructive action
- Failure

### Green

Usage:

- Success
- Completed state

### Blue

Usage:

- Information
- Positive feedback

### Yellow

Usage:

- Caution
- Temporary notice

---

# 3. Typography

## 3-1. Font Family

Primary Font:

- Nanum Square

Typography should prioritize readability and stable hierarchy.

---

## 3-2. Typography Scale

### Headline

H1

- Size: 34
- Line Height: 48
- Weight: ExtraBold

H2

- Size: 22
- Line Height: 30
- Weight: ExtraBold / Bold

H3

- Size: 20
- Line Height: 28
- Weight: ExtraBold / Bold / Regular

H4

- Size: 18
- Line Height: 26
- Weight: ExtraBold / Bold / Regular

---

### Body

B1

- Size: 16
- Line Height: 24
- Weight: ExtraBold / Bold / Regular

B2

- Size: 14
- Line Height: 22
- Weight: ExtraBold / Bold / Regular

B3

- Size: 13
- Line Height: 21
- Weight: ExtraBold / Bold / Regular

---

### Caption

C1

- Size: 12
- Line Height: 20
- Weight: ExtraBold / Bold / Regular

C2

- Size: 11
- Line Height: 19
- Weight: ExtraBold / Bold / Regular

C3

- Size: 10
- Line Height: 18
- Weight: Regular

---

## 3-3. Typography Rules

Hierarchy should primarily be expressed through:

1. size
2. weight
3. spacing
4. color

Avoid:

- excessive bold combinations
- decorative typography
- inconsistent type scaling

---

## 3-4. Multi-line Text

For text longer than one line:

- use dedicated line-height rules
- preserve readability
- avoid tight spacing

Recommended:

- 18pt → line-height 26
- 16pt → line-height 24
- 14pt → line-height 22

---

# 4. Layout & Spacing

## 4-1. Viewport Margin

Use 16px horizontal padding as the default viewport margin.

Rules:

- Primary layouts should align within the 16px safe area.
- Avoid layouts touching the screen edge directly.
- Maintain consistent horizontal rhythm across screens.

---

## 4-2. 4 Point Grid System

All layout spacing follows a flexible 4 Point Grid System.

Base Units:

- 4
- 8
- 12
- 16
- 20
- 24
- 32
- 40
- 48

Use multiples of 4 for:

- margin
- padding
- gap
- component height

Recommended:

- Small spacing → 4~8
- Standard spacing → 12~16
- Section spacing → 24~32
- Large grouping → 40+

Avoid:

- arbitrary spacing values
- inconsistent spacing combinations
- overly dense layouts

---

## 4-3. Spacing First

Hierarchy should primarily rely on spacing.

Use:

- generous whitespace
- grouped sections
- stable vertical rhythm

Avoid:

- excessive dividers
- crowded layouts

---

## 4-4. Component Density

Maintain a medium-density layout.

Rules:

- preserve touch accessibility
- maintain fast visual scanning
- avoid overly compact interfaces

---

# 5. Elevation & Depth

Depth should remain subtle and restrained.

## Principles

Use elevation only when necessary:

- modal
- floating action
- bottom sheet
- drag interaction
- layered surface

Avoid excessive shadows or dramatic depth.

---

## Shadow Rules

Use soft and low-contrast shadows.

Recommended:

- small blur radius
- low opacity
- minimal layering

Avoid:

- hard shadows
- colorful shadows
- large floating effects

---

## Layering

Use predictable layering hierarchy.

Recommended:

- Base Surface
- Raised Surface
- Floating Surface
- Modal / Overlay

Avoid:

- excessive z-index stacking
- overlapping visual noise

---

# 6. Shapes

## 6-1. Radius System

Corner radius should scale proportionally with component size.

### Radius Tokens

- Radius 0 → 0
- Radius 1 → 1~2px
- Radius 2 → 4px
- Radius 3 → 6px
- Radius 4 → 8px
- Radius 5 → 10px
- Radius 6 → 12px

---

## 6-2. Radius Usage

### Small Components

- tag
- chip
- badge

Recommended:

- radius 4~6

### Medium Components

- button
- input
- list item

Recommended:

- radius 8

### Large Components

- card
- modal
- container

Recommended:

- radius 10~12

Avoid:

- random radius usage
- inconsistent shape language

---

# 7. Components

## 7-1. Buttons

Buttons should feel:

- clear
- stable
- easy to scan

Rules:

- Primary button uses Orange 500
- Maintain strong text readability
- Use consistent padding and height
- Avoid excessive shadow usage

States:

- Enabled
- Disabled
- Hover
- Focused
- Pressed

---

## 7-2. Cards

Cards should prioritize:

- content grouping
- readability
- stable spacing

Rules:

- Use soft radius
- Use neutral surfaces
- Avoid excessive borders or shadows

---

## 7-3. Inputs

Inputs should:

- clearly communicate interaction state
- preserve readability
- maintain accessibility

Rules:

- Clear focus state
- Stable spacing
- Visible placeholder contrast

---

## 7-4. Lists

Lists should maintain:

- predictable spacing
- readable grouping
- fast scanning

Avoid:

- dense item stacking
- inconsistent alignment

---

# 8. Do's and Don'ts

## Do

- Use spacing as the primary hierarchy tool
- Maintain restrained visual emphasis
- Use consistent typography scale
- Use neutral surfaces as the default
- Maintain accessibility and readability
- Keep layouts scalable and predictable

---

## Don't

- Overuse primary color
- Use decorative gradients excessively
- Use inconsistent spacing or radius values
- Create overly dense interfaces
- Use excessive shadows or floating effects
- Rely only on color to communicate meaning
