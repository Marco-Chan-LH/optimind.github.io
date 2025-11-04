---

## 🎨 **OPTIMIND Design System**

---

### 1. 🧱 **Core Principles**

* **Accessibility-first**: Large text, strong color contrast, and simplified layouts.
* **Emotionally positive**: Warm, welcoming colors and soft visuals to encourage trust.
* **Simplicity over features**: Clear actions, no unnecessary elements.
* **Consistency**: Reuse components and layouts to reduce cognitive load.

---

### 2. 🎨 **Color Palette**

| Color Role         | Color (Hex) | Usage                               |
| ------------------ | ----------- | ----------------------------------- |
| 🟠 Primary         | `#F28C38`   | Buttons, icons, active elements     |
| 🍑 Accent          | `#FFCCB3`   | Background highlights, hover states |
| ⚪ Light Background | `#FFF8F1`   | Main background                     |
| 🔘 Dark Text       | `#333333`   | Titles and important text           |
| 🔘 Medium Text     | `#666666`   | Body text                           |
| ✅ Success          | `#66BB6A`   | Progress confirmation, good score   |
| ❌ Error            | `#E57373`   | Warnings, incorrect answer          |
| 🔷 Disabled        | `#CCCCCC`   | Inactive elements                   |

> ✅ Contrast ratios comply with WCAG AA/AAA for elderly vision accessibility.

---

### 3. 🔤 **Typography**

#### Font Family:

* **Primary:** `Nunito` (Google Font)

  * Friendly, rounded, easy to read.
* **Fallbacks:** `Open Sans`, `Arial`

#### Sizes:

| Use Case        | Size     | Weight    |
| --------------- | -------- | --------- |
| Title / Heading | 28–36 pt | Bold      |
| Section Header  | 24 pt    | Semi-Bold |
| Body Text       | 20 pt    | Regular   |
| Button Text     | 20 pt    | Bold      |
| Caption/Help    | 18 pt    | Regular   |

#### Guidelines:

* No text smaller than **18 pt**.
* Use sentence case (e.g., “Start your test” not “START YOUR TEST”).

---

### 4. 🧩 **UI Components**

#### Buttons

* **Primary Button**: Filled `#F28C38`, white text, rounded corners (`12–16px radius`)
* **Secondary Button**: Outline with `#F28C38`, or filled with accent color
* **Disabled Button**: Gray with lower opacity

#### Inputs

* Large touch-friendly fields (min height: 56px)
* Placeholder in light gray, label above
* Use checkmarks or icons instead of validation text where possible

#### Cards / Sections

* Rounded corners (16px)
* Soft shadow (e.g., `box-shadow: 0 2px 8px rgba(0,0,0,0.1)`)
* Padding: At least `24px` all around

---

### 5. 🧭 **Layout and Spacing**

* **Safe area padding**: 24–32px on all sides (for iPad touch comfort)
* **Component spacing**: 24px between elements
* **Line height**: 1.5x font size
* **Alignment**: Left-aligned text, center-aligned icons/buttons

---

### 6. 📱 **Iconography & Imagery**

* Use outlined or soft icons with labels.
* Minimum icon size: **32x32 px**
* Avoid icons without text labels.
* Use illustrations that are warm, rounded, and human-friendly.

#### Example Icon Sets:

* [Phosphor Icons](https://phosphoricons.com/)
* [Lucide Icons](https://lucide.dev/)

---

### 7. 🔊 **Feedback & States**

| Type     | Visual Feedback                | Example                |
| -------- | ------------------------------ | ---------------------- |
| Success  | Green check + friendly message | “Well done!”           |
| Error    | Red border or icon + help text | “Try again”            |
| Loading  | Soft spinner or progress bar   | “Preparing your game…” |
| Progress | Bar or score bubble            | “Your score: 12/20”    |

---

### 8. 🌙 **Accessibility Notes**

* Ensure tappable areas are **44x44pt** minimum.
* Use `VoiceOver`-friendly labels on all interactive elements.
* Use haptics or subtle sounds for feedback (optional).
* Keep text left-aligned and avoid centered paragraphs.

---

### 9. 📦 **Sample Component Library (Naming Example)**

| Component Name    | Purpose                       |
| ----------------- | ----------------------------- |
| `ButtonPrimary`   | For main actions              |
| `CardTestItem`    | To display a game/test option |
| `ProgressTracker` | Shows scores, progress        |
| `InputLargeText`  | For name, age entry           |
| `HeaderSimple`    | For section titles            |
