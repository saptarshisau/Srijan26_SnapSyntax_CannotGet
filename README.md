# Srijan26_SnapSyntax_CannotGet

A Zero-JS marvel proving HTML/CSS Turing-completeness. Purely driven by the Checkbox Hack &amp; native pseudo-classes, it features global state management, dynamic theming, layout orchestration, and hash-routed modals—achieving full application logic without a single line of JavaScript. Max performance, pure CSS engineering.

# 🚀 Zero-JS Storyboard: A Pure CSS Application Engine

**Live Demo:** https://srijan26-snap-syntax-cannot-get.vercel.app/

### The Astonishing Idea
This project was engineered to prove a point: modern HTML and CSS rendering engines are powerful enough to handle complex application logic, global state management, and dynamic DOM manipulation **without a single line of JavaScript.** This is not a static webpage. It is a fully interactive, state-driven interface built purely by exploiting advanced CSS cascading rules and pseudo-classes.

### ⚙️ Core Mechanics Exposed

This application bypasses traditional JS event listeners and variables by relying on three core HTML/CSS mechanics:

1. **The Checkbox Hack (`:checked`):** Global state is managed via hidden `<input type="radio">` elements at the top of the DOM tree. When user-facing `<label>` tags are clicked, these hidden inputs change state, acting as immutable global variables.
2. **The General Sibling Combinator (`~`):** Because the state inputs live at the top of the DOM, we use the sibling combinator to pass state changes down the tree. This allows us to instantly swap CSS variable sets (for theming) or grid definitions (for layout shifting) globally.
3. **URL Hash Routing (`:target`):** Full-screen modals are orchestrated by hijacking the browser's native anchor routing. By linking to specific `id` attributes, the CSS `:target` pseudo-class listens to the URL bar and renders the appropriate overlay.

### ✨ Features
* **Dynamic Theming:** Instantaneous switching between Cyberpunk, Light, and Dark modes via CSS variable overrides.
* **Layout Orchestration:** Seamlessly shift the UI between an auto-fitting Grid matrix and a linear List stack.
* **SPA-Style Routing:** A tabbed navigation system that reveals hidden panes without page reloads.
* **Interactive Modals:** Full-screen data overlays summoned purely via CSS.
* **Responsive Design:** Fully mobile-optimized interface with stacking architecture.

### 🛠️ Tech Stack
* **HTML5** (Semantic structuring and input state management)
* **CSS3** (Advanced combinators, CSS Grid, Flexbox, custom properties)
* **JS:** 0 lines. 0 bytes.

### 🚀 Running Locally
Because this project relies purely on native browser tech, no build steps, package managers, or local servers are strictly required. 
1. Clone the repository.
2. Open `index.html` in any modern web browser.
