# 🔢 3-Position Sequence Generator
An interactive, browser-based tool for generating and validating every 3-position
combination line from a set of marked numbers — built for quick reference,
practice, and structural verification of sequences.

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Try_It_Now-2ea44f?style=for-the-badge)](https://v2nonis.github.io/3-Position-Sequence-Generator/)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](#-license)
[![Platform](https://img.shields.io/badge/Platform-Web_Browser-orange?style=for-the-badge)](#)

---

## 🔗 Try It Live
> **[Open the 3-Position Sequence Generator](https://v2nonis.github.io/3-Position-Sequence-Generator/)**
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

```bash
# Clone the repository
git clone https://github.com/v2nonis/3-Position-Sequence-Generator.git

# Navigate into the project directory
cd 3-Position-Sequence-Generator

# Open index.html directly in your default browser
# (On macOS)
open index.html
# (On Linux)
xdg-open index.html
# (On Windows)
start index.html
```

---

## 📄 License

MIT License

Copyright © 2026 Vikum Nonis

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.# (On macOS)
open index.html
# (On Linux)
xdg-open index.html
# (On Windows)
start index.html
\`\`\`
