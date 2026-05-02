
## ✨ Features

### 🔢 Algebra & Number Theory (`algebra.html`)
- **Modular Arithmetic:** Large powers & modular inverse (`BigInt`)
- **Fractions:** Add, subtract, multiply, divide with automatic simplification
- **Combinatorics:** Combinations `C(n,k)` & Permutations `A(n,k)`
- **Prime Generator:** Sieve of Eratosthenes (up to 100,000)
- **Pythagorean Triples:** Primitive triples sorted by `c`
- **Base Converter:** Convert between bases 2–16 (supports `0-9`, `A-F`)
- **Number Theory:** Prime factorization, divisor count `d(n)`, divisor sum `σ(n)`, Euler's totient `φ(n)`

### 📐 Trigonometry (`algebra.html`)
- **Exact Values:** Every 15° across all 4 quadrants
- **Fundamental Identities:** Pythagorean, reciprocal, quotient
- **Angle Formulas:** Sum/Difference, Double/Triple/Half-angle
- **Quadrant Signs & Reduction:** Clear sign tables & reduction-to-Q1 rules
- All formulas beautifully rendered with MathJax

### 📈 Mathematical Analysis (`analiza.html`)
- **Derivatives Table:** Complete with domains & differentiability conditions
- **Integrals Table:** 12 essential primitives with constants of integration
- **Interactive Plotter:** Native Canvas API, zero external libraries, smooth rendering
- **Inverse & Hyperbolic Functions:** Definitions, domains, derivatives
- **Series & Advanced:** Taylor/Maclaurin expansions, Leibniz rule, higher-order derivatives

## 🧭 Navigation
The project is modularly designed for seamless switching:
- `index.html` → Direct links to `algebra.html` and `analiza.html`
- `algebra.html` & `analiza.html` → Top navigation bar to return to `index.html` or switch modules
*(Navigation code is pre-integrated. No extra setup required.)*

## 🌍 Translations
The internal translation system was removed for maximum stability and speed. All interfaces are natively in **Romanian**.  
For other languages, simply use your browser's built-in translation:
- **Chrome/Edge:** Right-click → `Translate to English` (or any language)
- **Firefox:** Right-click → `Translate Page` (enable in settings)
MathJax formulas (`\(\frac{a}{b}\)`, `\(\int f(x)dx\)`, etc.) remain **universal** and are completely unaffected by page translation.

## 🚀 Deployment (Free Hosting)
1. Create a **public repository** on GitHub
2. Upload the 3 HTML files to the repository root
3. Go to `Settings → Pages → Source: Deploy from a branch → Branch: main → /(root) → Save`
4. Wait ~60 seconds. Your site will be live at `https://USERNAME.github.io/REPO/`
5. Future updates: Just `git push` or use GitHub's `Upload files`. Auto-rebuilds on every commit.

## 🛠️ Tech Stack
- **HTML5 / CSS3 / Vanilla JavaScript (ES6+)**
- **MathJax 3 (CDN)** for professional LaTeX rendering
- **HTML5 Canvas API** for interactive graphing
- **BigInt API** for arbitrary-precision arithmetic
- **Optimized Algorithms:** Sieve, Euclidean GCD, Trial Division, Binary Exponentiation
- **Zero dependencies, zero server, zero ads, fully offline-capable**

## 📜 License
Distributed under the **MIT License**. Feel free to use, modify, and distribute for educational or commercial purposes, with attribution to the original author.

---
✨ *Built for speed, precision, and mathematical clarity. Optimized for students, educators, and math enthusiasts.*
https://exceliorxtreme.github.io/simplemathtool/
