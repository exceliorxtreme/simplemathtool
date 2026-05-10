https://exceliorxtreme.github.io/simplemathtool/

## https://exceliorxtreme.github.io/math-hub/ 
## varianta următoare -reconstruit in module js pentru extindere cu noi funcțiuonalități
## ✨ Funcționalități
### 🔢 Algebră & Teoria Numerelor (`algebra.html`)
- Exponențiere modulară & invers modular (`BigInt`)
- Operații cu fracții (adunare, scădere, înmulțire, împărțire)
- Combinări `C(n,k)` & Aranjamente `A(n,k)`
- Generator de numere prime (Sieve of Eratosthenes)
- Triplete pitagorice primitive ordonate după `c`
- Conversie baze de numerație (2–16)
- Descompunere în factori primi, numărul & suma divizorilor, indicatorul lui Euler `φ(n)`

### 📐 Trigonometrie (`algebra.html`)
- Valori exacte din 15° în 15° pe toate cele 4 cadrane
- Formule fundamentale, de sumă/diferență, unghi dublu/triplu/jumătate
- Reducere la cadranul I & tabel de semne
- Toate formulele redate tipărit cu MathJax

### 📈 Analiză Matematică (`analiza.html`)
- Tabel complet de derivate cu domenii & condiții de derivabilitate
- Tabel de integrale nedefinite
- Plotter interactiv de funcții (Canvas nativ, zero librării)
- Funcții trigonometrice inverse & hiperbolice + derivatele lor
- Serii Taylor/Maclaurin, regula lui Leibniz, derivate de ordin superior

## 🧭 Navigare Între Pagini
Proiectul este conceput modular. Pentru a trece ușor de la o secțiune la alta, fiecare pagină conține un meniu de navigare în partea superioară:
- `index.html` → linkuri către `algebra.html` și `analiza.html`
- `algebra.html` & `analiza.html` → linkuri de revenire la `index.html` și comutare rapidă între module

*(Codul de navigare este deja integrat în fișiere. Nu necesită configurare suplimentară.)*

## 🌍 Traduceri
Sistemul intern de traducere a fost eliminat pentru stabilitate și viteză. Toate interfețele sunt în **limba română**. 
Pentru alte limbi, utilizează funcția nativă a browserului:
- **Chrome/Edge:** Click dreapta → `Translate to English` (sau altă limbă)
- **Firefox:** Click dreapta → `Translate Page` (necesită activare din setări)
Formulele MathJax (`\(\frac{a}{b}\)`, `\(\int f(x)dx\)`, etc.) rămân **universale** și nu sunt afectate de traducere.

## 🚀 Instalare & Hosting (Gratuit)
1. Creează un repository public pe GitHub
2. Încarcă cele 3 fișiere HTML în rădăcina repo-ului
3. Mergi la `Settings → Pages → Source: Deploy from a branch → Branch: main → /(root) → Save`
4. După ~60 secunde, site-ul va fi live la `https://USERNAME.github.io/REPO/`
5. Actualizările viitoare se fac prin `git push` sau `Upload files`. GitHub regenerază automat site-ul.

## 🛠️ Tehnologii Utilizate
- HTML5 / CSS3 / Vanilla JavaScript (ES6+)
- MathJax 3 (CDN) pentru randare LaTeX
- HTML5 Canvas API pentru grafice interactive
- BigInt API pentru aritmetică de precizie arbitrară
- Algoritmi optimizați: Sieve, Euclid, Trial Division, Binary Exponentiation
- Zero dependențe externe, zero server, zero reclame

## 📜 Licență
Distribuit sub **MIT License**. Poți folosi, modifica și distribui codul în scop educațional sau comercial, cu menționarea autorului original.

---
✨ *Construit pentru rapiditate, precizie și claritate matematică. Optimizat pentru studenți, profesori și pasionați.*
