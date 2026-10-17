# Fixed Income Mastery 📈

> **Understand bonds, yields, duration, and the rates complex.**  
> An interactive educational platform covering institutional fixed income, sales & trading, debt capital markets (DCM), and quantitative structuring.

---

## 🏛️ Overview

**Fixed Income Mastery** provides mathematically rigorous, highly interactive standalone educational modules designed for finance students (MSc / MBA), CFA candidates (Levels 1 & 2), and candidates preparing for investment banking S&T and structuring interviews.

### ✨ Key Features
- **Zero build steps:** Standalone single-file HTML modules with inline CSS and JavaScript.
- **Classic Parchment Design:** Elegant, respectful financial design aesthetic with animated yield curve sine wave backgrounds.
- **KaTeX Math:** High-fidelity LaTeX mathematical derivations for pricing formulas, derivations, and models.
- **Interactive Canvas Visualizers:** Custom HTML5 Canvas charts with crosshair hover HUDs, dynamic fulcrums, and sensitivity sliders.
- **Interview Flashcards:** 10 curated interview Q&A flashcards per module with actionable desk tips.
- **Scenario Stress Testing:** Real-world trading desk what-if simulators for yield curve shocks, butterfly twists, and futures hedging.

---

## 📚 Curriculum & Modules

| # | Module | Status | Highlights |
|---|--------|--------|------------|
| **01** | [Bond Basics](01_Bond_Basics.html) | ✅ Built | Cash flow anatomy, day-count conventions (ACT/ACT, 30/360, ACT/360), accrued interest, clean vs dirty price, price-yield curves |
| **02** | [Yield Measures](02_Yield_Measures.html) | ✅ Built | Current Yield, YTM, YTC, Yield to Worst (YTW), BEY vs EAY, Spot Curves vs Par Yields, Implied Forward Rates, Recursive Bootstrapping |
| **03** | [Term Structure](03_Term_Structure.html) | ✅ Built | Curve shapes, recession inversion signal, Pure Expectations, Liquidity Preference, Nelson-Siegel model fitting, PCA dynamics (Level, Slope, Curvature) |
| **04** | [Duration & Convexity](04_Duration_Convexity.html) | ✅ Built | Macaulay fulcrum balance, Modified duration tangent line, Effective duration for options/MBS, second-order convexity adjustment, Redington immunization |
| **05** | [Interest Rate Risk](05_Interest_Rate_Risk.html) | ✅ Built | DV01 and Swap PV01, Key Rate Durations (KRD), CME Treasury futures hedging, Cheapest-to-Deliver (CTD) conversion factors, scenario stress testing |
| **06** | Swaps | ⏳ Next | IRS fixed vs floating mechanics, swap pricing, swap spreads, OIS discounting, basis swaps |
| **07** | Credit & Spreads | ⏳ Planned | Credit risk, ratings, default probability, Z-spread, OAS, CDS mechanics |
| **08** | Inflation & Real Rates | ⏳ Planned | TIPS, breakeven inflation rates, inflation swaps, indexation lag |
| **09** | Structured Products | ⏳ Planned | Callable/putable bonds, MBS prepayment modeling, pass-throughs, CMO tranches |
| **10** | Interview Cheatsheet | ⏳ Planned | 100+ master flashcards, mental math heuristics, market conventions quick reference |

---

## 🚀 Getting Started

No installation, Node.js, or build tools required.

### Local Viewing
Clone the repository and open `index.html` in any modern web browser:

```bash
git clone https://github.com/<your-username>/fixed-income-mastery.git
cd fixed-income-mastery
# Open index.html in your browser
```

### GitHub Pages Deployment
1. Go to your repository on GitHub: `Settings` > `Pages`.
2. Under **Branch**, select `main` and root `/`.
3. Click **Save** to publish directly.

---

## 🛠️ Technology Stack
- **Structure:** Semantic HTML5
- **Styling:** Custom Vanilla CSS with CSS custom properties (parchment palette)
- **Math Rendering:** [KaTeX](https://katex.org/) (0.16.9)
- **Graphics:** HTML5 Canvas API (interactive HUDs, custom responsive charts)
- **Typography:** Inter & JetBrains Mono (via Google Fonts)

---

## 📄 License
MIT License. Created for MSc Financial Markets & Investments (FMI) education.
