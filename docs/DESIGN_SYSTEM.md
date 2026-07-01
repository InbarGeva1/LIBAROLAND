
# 🎨 LIBAROLAND Design System

> Version: 1.0
>
> Last Updated: July 2026

---

# Overview

The LIBAROLAND Design System defines the visual language and UI principles for the application.

The goal is to create a premium travel experience inspired by:

- 🇹🇭 Thailand
- 🎵 Tomorrowland
- 🍎 Apple Human Interface Guidelines
- ✈️ Modern Travel Apps
- 🧘 Calm & Minimal Design

The application should feel luxurious, clean, playful, and easy to use.

---

# Design Principles

## 1. Simplicity First

Every screen should be understandable within 3 seconds.

---

## 2. One Primary Action

Each screen should have one obvious primary action.

---

## 3. Less is More

Avoid unnecessary decorations.

Whitespace is part of the design.

---

## 4. Premium Experience

Use subtle animations, clean typography and consistent spacing.

---

## 5. Consistency

Every screen should use the same spacing, colors, typography and components.

---

# Brand

## App Name

**LIBAROLAND**

---

## Subtitle

Libar × Tomorrowland × Thailand 2026

---

## Brand Personality

- Premium
- Tropical
- Friendly
- Calm
- Modern
- Adventurous

---

# Color Palette

## Primary

| Name | Value |
|-------|---------|
| Turquoise | #1FB6B2 |

Used for:

- Primary Buttons
- Active Navigation
- Links
- Interactive Elements

---

## Secondary

| Name | Value |
|-------|---------|
| Ocean Navy | #0D3B66 |

Used for:

- Titles
- Headers
- Icons

---

## Accent

| Name | Value |
|-------|---------|
| Golden Sand | #D9A441 |

Used only for:

- Countdown
- Tomorrowland
- Important Highlights

---

## Background

| Name | Value |
|-------|---------|
| Light Gray | #F8FAFC |

---

## Surface

| Name | Value |
|-------|---------|
| White | #FFFFFF |

---

## Success

#22C55E

---

## Warning

#F59E0B

---

## Error

#EF4444

---

# Typography

## Heading Font

Plus Jakarta Sans

Reason:

- Modern
- Friendly
- Premium

---

## Body Font

Inter

Reason:

- Excellent readability
- Great on mobile

---

# Font Scale

| Style | Size | Weight |
|--------|------|---------|
| H1 | 32 | Bold |
| H2 | 28 | Bold |
| H3 | 24 | SemiBold |
| H4 | 20 | SemiBold |
| Title | 18 | Medium |
| Body | 16 | Regular |
| Small | 14 | Regular |
| Caption | 12 | Medium |

---

# Border Radius

| Component | Radius |
|------------|---------|
| Cards | 24px |
| Buttons | 18px |
| Inputs | 18px |
| Bottom Sheet | 32px |
| Chips | 999px |

---

# Shadows

## Card

```
0 8px 24px rgba(15,23,42,0.08)
```

---

## Floating Card

```
0 20px 60px rgba(15,23,42,0.12)
```

---

# Spacing System

Based on an **8pt Grid**

Allowed spacing values:

```
4
8
16
24
32
40
48
64
80
```

Never use random spacing values.

---

# Layout

## Screen Padding

24px

---

## Card Gap

16px

---

## Section Gap

32px

---

## Maximum Content Width

100%

Mobile First

---

# Icons

Library:

Lucide React

Properties:

- Outline
- Rounded
- 24px
- Stroke Width 2

---

# Buttons

## Primary Button

Background:

Primary Turquoise

Text:

White

Radius:

18px

Height:

56px

Shadow:

Yes

---

## Secondary Button

Background:

White

Border:

1px Gray

Text:

Ocean Navy

---

## Ghost Button

Transparent

No border

---

## Danger Button

Red Background

White Text

---

# Cards

All cards use:

- White background
- Radius 24px
- Soft shadow
- Padding 20px

---

## Dashboard Card

Contains summary information.

---

## Destination Card

Contains:

- Image
- Destination Name
- Country
- Description
- CTA Button

---

## Budget Card

Contains:

- Total Budget
- Remaining
- Progress Bar

---

## Countdown Card

Contains:

- Days Left
- Trip Date

---

## Ticket Card

Contains:

- Airline
- Flight Number
- Date
- QR Code
- Seat

---

## Activity Card

Contains:

- Image
- Activity Name
- Time
- Location
- Notes

---

# Navigation

Bottom Navigation

Maximum:

5 Tabs

Tabs:

- Home
- Planner
- Add
- Translator
- Settings

---

# Motion

Animation Duration

200ms

---

Animation Curve

Ease Out

---

Page Transition

Fade + Slide

---

# Images

Use:

Real photography only.

Avoid:

- Cartoons
- Clipart
- Low Quality Images

---

# Glassmorphism

Allowed only on:

- Floating Cards
- Modals

Avoid using everywhere.

---

# Component Library

Core Components

- Button
- Card
- Header
- Bottom Navigation
- FAB
- Input
- Search Bar
- Badge
- Avatar
- Modal
- Bottom Sheet
- Tabs
- Progress Bar
- Calendar Card

---

# Accessibility

Minimum touch target:

44x44

Minimum font:

14px

Contrast:

WCAG AA

Never rely only on color.

---

# Empty States

Instead of

"No activities"

Use

"Your adventure starts here 🌴"

---

Instead of

"No expenses"

Use

"Time to explore Thailand! 💸"

---

# Loading States

Always use skeleton loaders.

Avoid spinners when possible.

---

# Error Messages

Use friendly language.

Example:

Instead of

Error

Use

Something went wrong.
Let's try again.

---

# Dark Mode

Planned for Version 2.

---

# Responsive Strategy

Primary Target:

iPhone 15 Pro

Secondary:

Android

Tablet support:

Future Release

---

# UI Rules

✅ Consistent spacing

✅ Consistent typography

✅ One primary button per screen

✅ Large touch targets

✅ Simple navigation

❌ No crowded screens

❌ No more than 5 bottom tabs

❌ No unnecessary gradients

❌ No inconsistent colors

---

# Design Checklist

Before implementing any screen:

- [ ] Uses design tokens
- [ ] Uses 8pt spacing
- [ ] Uses shared components
- [ ] Has one primary action
- [ ] Mobile first
- [ ] Accessible
- [ ] Matches Figma
- [ ] Ready for React implementation

---

# Related Documentation

- [README](README.md)
- [PRD](PRD.md)
- [ARCHITECTURE](ARCHITECTURE.md)
- [FEATURES](FEATURES.md)
- [UI_COMPONENTS](UI_COMPONENTS.md)
