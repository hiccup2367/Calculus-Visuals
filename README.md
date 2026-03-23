∫ Calculus Explorer
An interactive, visual calculus learning tool — no install, no login, open in any browser.


<img width="2045" height="1097" alt="Screenshot 2026-03-23 162236" src="https://github.com/user-attachments/assets/4ab4b74b-9b17-48cb-9631-f70d18d69e72" />
<img width="1020" height="1106" alt="Screenshot 2026-03-23 162613" src="https://github.com/user-attachments/assets/752807a6-3ba9-4033-8cbe-a6078f43d4dd" />
<img width="1023" height="1114" alt="Screenshot 2026-03-23 162623" src="https://github.com/user-attachments/assets/b6770693-1cc4-43f2-9a8f-249a138a81d2" />


What Is This?
I taught myself calculus and ran into one of the main problems that makes the field so daunting; calculus is not easy to visualize. When compared to Algebra, which is really just a step down from calculus, we are able to see how the rules work very easily, and it is much easier for people to follow along with algebraic foundations as a result. 
However, since calculus is not like that, people struggle to reach some of the deeper foundations of the field. As a result, it is very easy for them to give up and say "it's too difficult" or "I just can't get this": You can, you just need some help. The goal of this website is to be that help for as many people as possible; I want to ensure that everyone who wants to learn calculus has a tool they can use to see how the properties of functions and the rules of calculus work. 
Every module has a live interactive graph where you drag sliders and watch the math respond in real time. 

### Calculus I
| Module | What You Can Explore |
|---|---|
| **Limits & Continuity** | ε-δ neighborhood bands, left/right limits, holes, jumps, asymptotes |
| **The Derivative** | Secant → tangent animation as h → 0, click-to-place x₀ |
| **Curve Sketching** | f, f′, f″ overlaid simultaneously with critical & inflection points |
| **Optimization** | Closed interval method, automatic critical point detection |
| **Riemann Sums** | Left, Right, Midpoint, Trapezoid — live error vs. exact integral |
| **Definite Integral** | Signed area with positive/negative decomposition |
| **Fund. Theorem of Calculus** | Accumulation function F(x) = ∫ₐˣ f(t) dt building in real time |
 
### Calculus II
| Module | What You Can Explore |
|---|---|
| **Taylor Series** | Polynomial approximation building term by term, KaTeX rendered |
| **Volumes of Revolution** | Disk method with animated cross-sectional ellipse |
| **Series & Convergence** | Partial sum plots for geometric, p-series, harmonic, alternating, telescoping |
 
---
 
## Features
 
- **Click-to-set** — click directly on any graph to place a point instead of using sliders
- **Hover crosshair** — move your mouse over a graph for a real-time tooltip showing f(x), f′(x), and more
- **Animate h → 0** — watch the secant line converge to the tangent automatically
- **KaTeX rendering** — all mathematics displayed in proper typeset notation
- **Shareable URLs** — every slider position and module choice is encoded in the URL; copy a link that restores your exact view
- **Usage stats** — visit counter and module exploration tracker built in
- **Keyboard navigation** — full arrow key support on all sliders
- **Accessible** — ARIA labels throughout, focus-visible outlines on all controls
 
---
 
## Quick Start
 
**Option 1 — Open the live site:**
```
https://hiccup2367.github.io/Calculus-Visuals/calculus-explorer.html
```
 
**Option 2 — Download and run locally:**
1. Download `calculus-explorer.html` from this repo
2. Double-click it — opens in any browser
3. No server, no install, no internet required after first load
 
**Option 3 — Clone the repo:**
```bash
git clone https://github.com/hiccup2367/Calculus-Visuals.git
cd Calculus-Visuals
open calculus-explorer.html         # macOS
# or: start calculus-explorer.html  (Windows)
# or: xdg-open calculus-explorer.html  (Linux)
```
 
---
 
## Tech Stack
 
| Layer | Technology |
|---|---|
| Rendering | HTML5 Canvas API (vanilla JS) |
| Math parsing | [math.js 11.11.0](https://mathjs.org/) |
| LaTeX display | [KaTeX 0.16.9](https://katex.org/) |
| Typography | Google Fonts — Lora, Source Serif 4, JetBrains Mono |
| Analytics | [CounterAPI](https://counterapi.dev/) (anonymous, no personal data) |
| Hosting | GitHub Pages |
| Build step | None |
 
The entire application is **one HTML file, 86 KB**. No framework, no bundler, no node_modules.
 
---
 
## Project Structure
 
```
Calculus-Visuals/
├── calculus-explorer.html   ← the entire application
└── README.md
```
 
The CSS, JavaScript, and HTML all live in a single self-contained file — making it trivially easy to download, share, fork, and deploy anywhere.
 
---
 
## Contributing
 
Contributions are welcome. The codebase is intentionally simple — no build tooling means you can open the file, edit it, and see changes immediately by refreshing the browser.
 
**Good first contributions:**
- Adding a new function option to an existing module's dropdown
- Improving the educational prose in any text section
- Bug fixes in numerical computation edge cases
- Mobile layout improvements
 
**Larger ideas (see [Future Work](#future-work)):**
- Custom function input field (text box instead of dropdown)
- Additional Calc II modules (Related Rates, Integration by Substitution, Polar Coordinates)
- Dark mode toggle
- Progressive Web App / offline support
 
To contribute: fork → edit → open a pull request. No setup required beyond a text editor and a browser.
 
---
 
## Future Work
 
- [ ] Custom function input (type any expression)
- [ ] Mobile-responsive layout
- [ ] Dark mode
- [ ] Related Rates module
- [ ] Integration by Substitution module
- [ ] Polar Coordinates module
- [ ] Arc Length module
- [ ] Guided step-by-step examples per module
- [ ] Quiz mode
- [ ] Offline PWA support
- [ ] Embeddable single-module widget mode
 
---
 
## License
 
MIT — free to use, modify, and distribute. If you use this in a classroom or educational setting, I'd love to hear about it.
 
---
 
## Author
 
**Vyom Krothapalli** — Class of 2027
 
I've always been interested in mathematics. Teaching myself calculus led me to an important realization: while calculus can seem daunting, it's fundamentally the same as algebra — the only real difference is that calculus is much harder to visualize. That's why I built this.
 
📧 [hiccup2367@gmail.com](mailto:hiccup2367@gmail.com)  
🐙 [github.com/hiccup2367](https://github.com/hiccup2367)
 
---
 
*If this helped you understand calculus better, consider starring the repo — it helps other students find it.*
