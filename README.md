# INDIAN ART — A Journey Through Time

An interactive digital timeline exploring 5,000+ years of Indian artistic heritage. This project is built to fulfill the CO1 assignment requirements (10 Marks) for the Interactive Indian Art Timeline.

## Assignment Requirements Addressed
* **Interactive Timeline:** Horizontal scrolling on desktop, vertical on mobile.
* **Clickable Artifacts:** 12 total artifacts (2 for each tradition).
* **Historical Context & Significance:** Prominently displayed in the artifact modal.
* **6 Traditions Covered:** Indus Valley, Ajanta, Chola, Mughal, Madhubani, and Warli. Madhubani and Warli are correctly classified as "Continuous Traditions / Living Art Forms".

## How to Run Locally

This project uses vanilla HTML, CSS, and JavaScript. No build steps or complex servers are required.

1. **Download/Clone** this repository or folder.
2. **Open `index.html`** directly in any modern web browser (Chrome, Firefox, Safari, Edge).
   * *Optional: If you want to use a local server, you can use VS Code's "Live Server" extension or run `python -m http.server` in the terminal and navigate to `http://localhost:8000`.*

## Images and Assets

**IMPORTANT:** Currently, placeholder images are used with a fallback text ("Authentic Image Pending") to satisfy the strict requirement against using AI-generated representations of real historical artifacts.

Before final submission, you must download authentic images from reliable sources (e.g., National Museum, ASI, MET) and place them in the corresponding `assets/` folders:
* `assets/indus/dancing-girl.jpg`
* `assets/indus/pashupati-seal.jpg`
* `assets/ajanta/padmapani.jpg`
* `assets/ajanta/apsara.jpg`
* `assets/chola/nataraja.jpg`
* `assets/chola/somaskanda.jpg`
* `assets/mughal/jahangir.jpg`
* `assets/mughal/zebra.jpg`
* `assets/madhubani/tree-of-life.jpg`
* `assets/madhubani/kohbar.jpg`
* `assets/warli/tarpa.jpg`
* `assets/warli/wedding.jpg`

## Team Section
Open `index.html` and scroll to the bottom `<footer class="team-section">` to replace "Member 1", "Member 2", etc., with your actual team members' names.

## Technology Stack
* **HTML5:** Semantic structure.
* **CSS3:** Custom styling, variables, flexbox/grid layouts, responsive media queries.
* **Vanilla JavaScript:** Dynamic generation of the timeline from data, modal interactions, smooth scroll filtering. No external libraries were used.
