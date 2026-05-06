# 🎓 BUBT CSE Portal

A responsive, interactive student portal for **Bangladesh University of Business & Technology (BUBT)** — B.Sc. Engineering in Computer Science & Engineering. Built with pure HTML, CSS, and vanilla JavaScript. No frameworks, no dependencies.

---

## ✨ Features

### 💰 Semester Fee Calculator
- Calculates tuition fees based on **৳3,350 per credit hour** using BUBT's official 2025–2026 fee structure
- **Per-semester editable credits** — change credit hours directly on each semester card
- **Global waiver** — apply a waiver to all semesters at once (0%, 20%, 25%, 50%, 75%, 100%, or any custom %)
- **Per-semester waiver override** — individually set a different waiver for any semester
- **Custom waiver %** — type any arbitrary percentage (e.g. 33.5%) for precise calculations
- Full semester breakdown table showing tuition, semester fee, gross total, waiver deduction, and final payable amount
- Summary stats: total payable, gross total, total saved, and total credit hours

### 📊 GPA / CGPA Calculator
- Covers **Fall '25, Spring '26, Summer '26** with pre-filled BUBT CSE course data
- Enter scores out of 100 — grades and grade points auto-calculate using BUBT's grading policy
- **Inline-editable course fields** — edit course code, name, and credit hours directly in the table
- **Add / delete courses** per semester
- **Add / delete semesters** — dynamically create new semester tabs with custom courses
- Live **SGPA** per semester and **CGPA dial** across all semesters
- Animated CGPA progress ring with performance label (Outstanding, Excellent, Very Good, etc.)

### 🎨 Design
- Dark glassmorphism + cyberpunk CSE aesthetic
- Animated particle canvas background with connecting node lines
- Scanline overlay animation
- Fully responsive — works on mobile and desktop
- Space Mono + Syne typography

---

## 📁 Project Structure

```
bubt-cse-portal/
├── index.html       # Semester Fee Calculator
├── grades.html      # GPA / CGPA Calculator
└── README.md
```

---

## 🚀 Getting Started

No build step needed. Just open the files in a browser.

```bash
git clone https://github.com/makhzumbinharun/bubt-cse-portal.git
cd bubt-cse-portal
# Open index.html in your browser
```

Or simply download the ZIP and open `index.html`.

---

## 📐 Fee Formula Reference

| Component | Value |
|---|---|
| Tuition per credit | ৳3,350 |
| Semester fee (1st sem) | ৳14,080 |
| Semester fee (subsequent) | ৳9,850 |
| Waiver applied on | Tuition only |

**Payable = (Credits × ৳3,350 + Semester Fee) − (Credits × ৳3,350 × Waiver%)**

---

## 🔢 BUBT Grading Scale

| Grade | Points | Marks |
|---|---|---|
| A+ | 4.00 | 80 – 100 |
| A  | 3.75 | 75 – 79  |
| A− | 3.50 | 70 – 74  |
| B+ | 3.25 | 65 – 69  |
| B  | 3.00 | 60 – 64  |
| B− | 2.75 | 55 – 59  |
| C+ | 2.50 | 50 – 54  |
| C  | 2.25 | 45 – 49  |
| D  | 2.00 | 40 – 44  |
| F  | 0.00 | 0 – 39   |

**SGPA = Σ(Grade Points × Credits) ÷ Σ(Credits)**  
**CGPA = Σ(Grade Points × Credits across all semesters) ÷ Σ(All Credits)**

---

## 🛠️ Built With

- **HTML5 / CSS3 / Vanilla JavaScript** — zero dependencies
- **Canvas API** — animated particle background
- **Google Fonts** — Space Mono, Syne
- CSS custom properties, grid, and flexbox for layout

---

## 👤 Author

**Makhzum Bin Harun**  
B.Sc. Engg. in CSE — BUBT
GitHub: [@makhzumbinharun](https://github.com/makhzumbinharun)

---

## 📄 License

© 2026 All rights reserved.
