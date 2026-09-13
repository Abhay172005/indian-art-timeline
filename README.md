# Indian Art — A Journey Through Time

An interactive, digital museum experience exploring 5,000 years of Indian artistic heritage. From the ancient seals of the Indus Valley to the living traditions of Madhubani and Warli, this project curates significant artifacts into an elegant chronological timeline.

## Features
* **Premium Digital Museum Aesthetic:** A dark-themed, gold-accented UI designed for deep immersion.
* **Vertical Chronological Timeline:** A seamless, segmented timeline spine that visually connects eras.
* **Interactive Artifact Modals:** Click on any artifact card to open a detailed modal containing:
  * High-resolution imagery
  * Historical Context & Significance
  * Material & Technique
  * Cultural Importance
* **Dynamic Filtering:** Navigate directly to specific eras (Indus Valley, Ajanta, Chola, Mughal, Madhubani, Warli) using the sticky top navigation bar.
* **Fully Responsive:** Adapts beautifully to desktop, tablet, and mobile screens.

## Project Structure
The project relies on a lightweight, vanilla tech stack with zero dependencies:
* `index.html` - Semantic structure, navigation, and modal skeleton.
* `style.css` - Custom design system, CSS variables, grid/flexbox layouts, and UI animations.
* `data.js` - Centralized JSON-like data store containing all artifact metadata, historical information, and image curation.
* `script.js` - Vanilla JavaScript handling dynamic DOM generation, IntersectionObserver scroll events, and modal state management.
* `assets/` - Curated, historically accurate, high-resolution artifact images sourced from reputable institutions (e.g., National Museum, ASI, LACMA, Freer Gallery).

## How to Run Locally
No build steps, frameworks, or complex servers are required.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Abhay172005/indian-art-timeline.git
   ```
2. **Open the project:**
   Simply open `index.html` directly in any modern web browser (Chrome, Firefox, Safari, Edge).
   *(Optional: Use VS Code's "Live Server" extension for a better development experience).*

## Data & Sourcing
All historical information in this project is drawn from reputable academic institutions and government sources. The artifact images are verified public domain or Creative Commons (CC) licensed assets carefully sourced for educational purposes. 

## License
This project is open-source and available for educational use.
