# 🧩 LIBAROLAND UI Components

Version: 1.0

---

# Philosophy

Every screen in the app should be built from reusable components.

Never duplicate UI.

Every component should solve one problem only.

---

# Component Hierarchy

App

├── Layout

│ ├── Header

│ ├── Bottom Navigation

│ └── Floating Action Button

│

├── Shared Components

│ ├── Button

│ ├── Card

│ ├── Badge

│ ├── Avatar

│ ├── Input

│ ├── Search

│ ├── Modal

│ └── Progress Bar

│

└── Feature Components

Planner Card

Budget Card

Expense Card

Ticket Card

Translator Card

Countdown Card

Weather Card

Packing Item

Destination Card

Activity Card

---

# Button

Purpose

Primary user action.

Variants

- Primary
- Secondary
- Ghost
- Danger

Props

- text
- icon
- loading
- disabled
- onClick

Height

56px

Radius

18px

---

# Card

Purpose

Display grouped information.

Variants

- Default
- Elevated
- Clickable
- Glass

Props

- title
- subtitle
- icon
- children
- onClick

Radius

24px

Padding

20px

---

# Header

Purpose

Top navigation.

Contains

- Screen title
- Subtitle (optional)
- Back button (optional)
- Action button (optional)

---

# Bottom Navigation

Items

🏠 Home

📅 Planner

➕ Quick Add

💬 Translator

⚙ Settings

Maximum tabs

5

---

# Countdown Card

Displays

- Days left
- Departure date

Future

Dynamic countdown

---

# Weather Card

Displays

- Temperature
- Weather icon
- Humidity
- Rain chance

Source

Weather API

---

# Planner Card

Displays

- Day title
- Date
- Island
- Number of activities

Actions

- Edit
- Delete
- Rename
- Reorder

---

# Activity Card

Displays

- Image
- Activity
- Time
- Notes
- Cost

Actions

- Edit
- Delete

Future

Drag & Drop

---

# Destination Card

Displays

- Hero Image
- Name
- Description
- Map Button

---

# Budget Card

Displays

- Budget
- Spent
- Remaining

Includes

Progress Bar

---

# Expense Card

Displays

- Category
- Amount
- Currency
- Date

Future

OCR Receipt Scan

---

# Currency Converter

Displays

THB

ILS

USD

Future

Live Exchange Rate

---

# Ticket Card

Displays

- Airline
- Flight Number
- Seat
- Departure
- QR Code

Actions

Share

Download

---

# Translator Card

Modes

- Voice → Thai
- Voice → Hebrew
- Conversation Mode

Main Component

Large microphone button

Future

Offline translation

---

# Packing Item

Displays

Checkbox

Title

Category

Priority

Actions

Edit

Delete

---

# Quick Action Button

Purpose

Fast access.

Examples

Add Expense

Add Activity

Translate

Add Ticket

---

# Empty State

Every feature should have an Empty State.

Example

Planner

"Let's build your adventure 🌴"

---

# Skeleton Loader

Every page should support loading placeholders.

Avoid spinners whenever possible.

---

# Dialog

Reusable confirmation dialog.

Examples

Delete Activity

Delete Day

Delete Expense

---

# Toast

Short feedback messages.

Examples

"Expense added"

"Trip updated"

"Activity deleted"

---

# Future Components

AI Assistant

Tomorrowland Widget

Flight Tracker

Emergency Contacts

Travel Timeline

Offline Banner

Map Preview

Shared Trip Members

Trip Statistics

Achievements

---

# Component Rules

Every component should:

- Have one responsibility
- Support dark mode (future)
- Be responsive
- Be reusable
- Use Tailwind only
- Be accessible

---

# Folder Structure

src/

components/

ui/

Button

Card

Header

Navigation

Modal

shared/

feature/

planner/

budget/

tickets/

translator/

packing/

home/

---

# Related Documentation

README.md

DESIGN_SYSTEM.md

ARCHITECTURE.md

FEATURES.md
