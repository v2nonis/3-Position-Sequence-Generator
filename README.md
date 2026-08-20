# 🔢 3-Position Sequence Generator
An interactive, browser-based tool for generating and validating every 3-position
combination line from a set of marked numbers — built for quick reference,
practice, and structural verification of sequences.

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Try_It_Now-2ea44f?style=for-the-badge)](https://vikumnonis.github.io/3-position-sequence-generator/)
[![License](https://img.shields.io/badge/License-Custom_Non--Commercial-blue?style=for-the-badge)](#-license)
[![Platform](https://img.shields.io/badge/Platform-Web_Browser-orange?style=for-the-badge)](#)

---

## 🔗 Try It Live
> **[Open the 3-Position Sequence Generator](https://v2nonis.github.io/3-Position-Sequence-Generator/))**
> *No download, installation, or setup required — works directly in any modern web browser.*

---

## 📋 Overview
Manually working out every valid ordering of a set of numbers is slow and
error-prone. The **3-Position Sequence Generator** gives you an instant,
visual breakdown: mark your numbers, pick a mode, and see every 3-position
line generated and flagged as Valid or Void.

Built as a lightweight reference and practice tool — no setup, no
dependencies, works fully offline once loaded.

---

## ✨ Key Features
- **Two Sequence Modes:** `Straight` for a single fixed-order line, `Combination` for every possible ordering (permutation) of 3+ marked numbers.
- **Instant Validation:** Out-of-range or duplicate numbers are automatically flagged as Void, with a clear reason shown.
- **Combination Matrix:** Generates all `n × (n − 1) × (n − 2)` permutations for boxed numbers, sorted in natural order.
- **Clean, Fast UI:** Tap-to-add number circles or type manually, live pill list, live summary counts (Total / Valid / Void).
- **Zero Dependencies:** Pure client-side HTML/CSS/JS — fully functional offline once loaded.

---

## 🛠️ Usage & Workflow
1. **Launch the App:** Open the [live link](https://v2nonis.github.io/3-Position-Sequence-Generator/) in Chrome, Firefox, Safari, or Edge.
2. **Set Sequence Range:** Choose how many numbers are in play using the +/− stepper.
3. **Choose a Mode:** `Straight` (exact 3-number order) or `Combination` (box 3+ numbers).
4. **Mark Numbers:** Tap the number circles or type into the input box.
5. **Review Lines:** See every generated line below, tagged Valid or Void, with a Total/Valid/Void summary.

---

## 💻 Local Development / Self-Hosting
Since the application runs entirely in the browser, you can host or run it locally with no server runtime needed:

\`\`\`bash
# Clone the repository
git clone https://github.com/vikumnonis/3-position-sequence-generator.git

# Navigate into the project directory
cd 3-position-sequence-generator

# Open index.html directly in your default browser
# (On macOS)
open index.html
# (On Linux)
xdg-open index.html
# (On Windows)
start index.html
\`\`\`
