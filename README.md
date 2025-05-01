# SDF-PP Resume Project

## Project Overview

Hi, my name is **Mark Schaefer**. This project was built using **HTML and CSS**. This project allowed me to gain a better understanding of programming while working on real-world projects, which was both challenging and rewarding.

---

## Layout Decisions

- **Top-level layout** uses **CSS Grid** for control over rows/columns.
- **Nested Flexbox** is used for simple vertical stacks (e.g., inside cards or sections).
- Even single-row layouts often use Grid for better column control.
- **Nested Grids**:
  - Example: In proficiency bars, each label + bar sits in its own grid area.
- Responsive behavior achieved with **media queries**.

---

## Features

### 📸 Profile and Summary
- Professional profile picture.
- A brief bio/summary gives employers an insight into my journey and skills.

### 📊 Proficiency Bars
- Represent my skill levels in various languages and tools.
- Built using empty `div` elements with fixed height and a green background.
- Bar widths vary based on skill proficiency.
- Layout uses **CSS Grid with grid areas** for full layout control and visualization.

### 🏷️ Skill Tags
- Skills selected based on personal tech experience and soft skills.
- Styled as pill-shaped tags with:
  - Light green background  
  - Rounded corners
- Layout handled with **Flexbox** and `flex-wrap` for responsive wrapping and a fluid design.

### 💼 Projects
- Displayed in a **grid layout**: 2 rows × 4 columns.
  - Row 1: Section heading
  - Row 2: Project cards
- Each project card is a **Flexbox container** for simple alignment and spacing.

## 🎓 Education and Experience

- Managed using **nested Grid layout**.
- Required some creative problem solving for different screen views:
  - Elements needed to be carefully aligned into grids.
  - Used media queries to dynamically restructure layout.

---

## 🔗 Footer

- All footer links are **fully functional** and direct users to the intended sections or external profiles.

---

## 📱 Responsiveness

- Layout adjusts using **media queries** for different screen sizes.
- In some cases, used `transform: scale()` to prototype content fit on smaller screens (tablet/ipad).
- The choice to have most layout elements use **fixed pixel values** was to stay true to the Figma design as closley as possible.
- While fixed pixels are not ideal for responsiveness, it allowed for **pixel-perfect accuracy** during development.

---

## 🧱 Code Structure and Design

### HTML
- Semantic tags used to divide the page into meaningful sections:
  - Profile
  - Proficiency Bars
  - Projects
  - Education and tools
  - Experience
  - Footer

### CSS
- **Grid** used for complex multi-column/multi-row layouts.
- **Flexbox** used for one-dimensional or simple responsive stacks.

### Refactoring Thoughts
- Considered refactoring for:
  - **Better maintainability**
  - **Future scalability**
- Thought about switching to **Tailwind CSS**, but stayed with **vanilla CSS** for simple pixel control.

---

## 🚧 Challenges and Reflection

- Biggest challenge: **Staying pixel-perfect** to match the Figma design.
- Realized that tools like **Tailwind CSS** or similar frameworks:
  - Speed up development
  - Make responsiveness simpler
- Writing **media queries for fixed pixel values** was tricky and frustrating.
- Proud of how closely the final result matched the original design.

---

## 🚀 Future Improvements

- **Tailwind CSS**: Refactor for better css/html semantics and better responsive handling.
- **Interactive Features**:
  - Add animations
  - Add interactivity
  - Customize the page to better reflect me as a person/individual.
