DevSec Portfolio
A sleek, modern, and responsive portfolio website template designed for Web Developers and Security Researchers. This project features a dark theme with vibrant orange accents, interactive particle backgrounds, and smooth animations to showcase your skills and projects professionally.

Portfolio PreviewHTML5CSS3JavaScript

🚀 Key Features
Modern Cyberpunk Aesthetic: Dark background with glowing orange elements, perfect for developers and security professionals.
Interactive Particle Background: Dynamic canvas animation that reacts to mouse movements.
Fully Responsive: Optimized layout for mobile, tablet, and desktop screens.
Scroll Reveal Animations: Elements animate smoothly as they enter the viewport.
Dynamic Skill Bars: Animated progress bars to visualize technical expertise.
Terminal Style Hero: Unique command-line interface design in the hero section.
Mobile Navigation: Smooth hamburger menu for smaller screens.
📂 File Structure
The project is organized into separate files for easy maintenance:

portfolio/
├── index.html # Main HTML structure (Layout & Content)
├── style.css # Custom CSS (Styles, Variables, Animations)
├── script.js # JavaScript (Particles, Interactions, Logic)
└── README.md # Documentation

text


## 🛠️ Technologies Used

- **HTML5**: Semantic markup.
- **CSS3**: Flexbox, Grid, CSS Variables, Keyframe Animations.
- **JavaScript (ES6+)**: Canvas API, Intersection Observer API.
- **Tailwind CSS**: Utility-first CSS framework (via CDN).

## ⚙️ How to Use

1. **Download or Clone** the project files to your local machine.
2. Open the project folder in **VS Code**.
3. Install the **Live Server** extension from the VS Code Marketplace (highly recommended).
4. Right-click on `index.html` and select **"Open with Live Server"**.
5. The site will open in your browser with hot-reload enabled.

## ✏️ Customization Guide

### 1. Changing Colors
Open `style.css` and modify the CSS variables inside the `:root` selector:

```css
:root {
    --bg: #08080c;          /* Background Color */
    --accent: #ff6b00;      /* Primary Orange */
    --accent-light: #ff9540;/* Lighter Orange */
    --fg: #ffffff;          /* Text Color */
}
2. Updating Content
Open index.html to change:

Name & Title: Look for the <h1> tag inside the Hero section.
Projects: Find the <!-- Projects Section --> and edit the cards.
Social Links: Update the href attributes in the Footer.
3. Modifying Particle Background
Open script.js and look for the Particle class or initParticles function to change:

Particle Count: Adjust the density calculation.
Particle Color: Change ctx.fillStyle.
Connection Distance: Modify the distance check in connectParticles().
📜 License
This project is open source and available under the MIT License. Feel free to use it for personal or commercial purposes.

Built with ❤️ by AFRA
