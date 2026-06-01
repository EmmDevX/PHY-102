# ⚡ PHY 102 – Electricity & Magnetism CBT

A browser-based Computer Based Test (CBT) practice app for **PHY 102 (Electricity and Magnetism)** at **Bowen University, Iwo**. Built as a single HTML file — no frameworks, no backend, no installation required.

---

## 🖥️ Preview

> Deep navy dark theme with electric-blue accents, animated progress bar, countdown timer, and a full post-exam review panel.

---

## ✨ Features

- **40 randomised questions** shuffled on every attempt from a larger question bank
- **35-minute countdown timer** with colour-coded warnings (orange at 5 min, red at 1 min)
- **Live progress bar** showing questions answered and percentage completed
- **Instant results** — score, grade (A–F), correct/wrong/skipped breakdown
- **Detailed review panel** — see every question with your answer highlighted and the correct answer revealed
- **Zero dependencies** — pure HTML, CSS, and vanilla JavaScript; works offline after the first load
- **Mobile responsive** — tested on phone and desktop browsers

---

## 📚 Topics Covered

| Topic | Questions |
|---|---|
| Forces in Nature | ✅ |
| Introduction to Electrostatics | ✅ |
| Methods of Charging | ✅ |
| Coulomb's Law | ✅ |
| Superposition Principle | ✅ |
| The Electric Field | ✅ |
| Electric Field & Potential | ✅ |
| Gauss's Law | ✅ |
| Electric Potential & Potential Energy | ✅ |
| Electric Dipoles | ✅ |
| Capacitance | ✅ |
| Parallel Plate Capacitors | ✅ |
| Capacitors in Series & Parallel | ✅ |
| Energy Density & Energy in Electric Fields | ✅ |
| Conductors & Insulators | ✅ |
| Semiconductors | ✅ |
| Direct Current (DC) | ✅ |
| Dielectrics & Effect of Dielectrics | ✅ |
| Transformers (efficiency, power, turns ratio) | ✅ |
| Lenz's Law & Faraday's Law | ✅ |

---






## 🎨 Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, animations, responsive grid) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | [Sora](https://fonts.google.com/specimen/Sora) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts |

---

## 📝 Grading Scale

| Score | Grade | Remark |
|---|---|---|
| 70% – 100% | A | Excellent |
| 60% – 69% | B | Very Good |
| 50% – 59% | C | Good Pass |
| 45% – 49% | D | Pass |
| Below 45% | F | Did Not Pass |

---

## 🔧 Customisation

All questions live in the `QUESTION_BANK` array inside the `<script>` tag of `PHY102_CBT.html`. Each question follows this structure:

```js
{
  t: "Topic Name",          // Topic label shown on the question card
  q: "Question text here?", // The question
  o: ["Option A", "Option B", "Option C", "Option D"], // Four options
  a: 1                       // Index of the correct answer (0-based)
}
```

To change the number of questions or time limit, update these two lines near the top of the script:

```js



## 📄 License

This project is released for educational use. Feel free to fork, modify, and share for non-commercial academic purposes.

---

> Made with ❤️ for Bowen University PHY 102 students.
