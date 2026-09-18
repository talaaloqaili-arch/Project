# Tala Oqaili — Personal Portfolio Website

A fully responsive personal portfolio website built with **pure HTML and CSS**, created as part of the Personal Portfolio Website Project (C7 – Amman, Class B). The site works as a live digital resume that introduces me, highlights my background in Cyber Security, showcases my projects, and gives visitors an easy way to get in touch or download my CV.

🔗 **Live Demo:** _add your hosted link here (GitHub Pages, Netlify, etc.)_

---

## 📖 Project Overview

This portfolio was designed and coded from scratch (no site builders, no CSS frameworks except Font Awesome for icons) to demonstrate core front-end skills: semantic HTML structure, Flexbox-based responsive layout, custom CSS styling, and interactive animations.

The site is organized into five main sections:

1. **Home** – Hero introduction with a circular profile photo, headline, a "Download CV" button, and social media links.
2. **About** – Overview of my education and certifications, presented as info cards:
   - Bachelor's degree in Cyber Security from Al-Albayt University
   - Cyber Bridge Certification (networking, Linux/Windows security, hands-on labs)
   - Data Analysis Certificate (Excel, SAS, R, Python, Power BI)
3. **Projects** – A gallery of my practical work, including the *Security Vulnerabilities Testing* platform.
4. **Contact** – Quick contact details (phone and email) so visitors can reach out directly.
5. **Footer** – Copyright notice and social media icons (LinkedIn, GitHub, X/Twitter).

---

## ✨ Features

- ✅ Fully responsive layout (mobile, tablet, and desktop) using Flexbox and media queries
- ✅ Custom logo and circular profile photo
- ✅ Smooth entrance animations (`fadeInUp`) for the hero section and cards
- ✅ Staggered card animations so content appears one after another
- ✅ Pulsing call-to-action button to draw attention to key actions
- ✅ Hover effects and smooth transitions on cards, buttons, and project thumbnails
- ✅ Downloadable CV button (`Tala_AlOqaily_CV_3.docx`)
- ✅ Social media icons via Font Awesome
- ✅ Clean, semantic HTML structure (`header`, `section`, `footer`)
- ✅ Organized, reusable CSS using custom properties (CSS variables) for colors and spacing

---

## 🛠️ Built With

- **HTML5** – semantic page structure
- **CSS3** – Flexbox, custom properties, `@keyframes` animations, media queries
- **[Font Awesome](https://fontawesome.com/)** – icon library (loaded via CDN)

---

## 📁 Project Structure

```
├── project.html              # Main HTML file (site structure/content)
├── style.css                 # Main stylesheet (layout, colors, animations)
├── logo.png                  # Site logo
├── Talaphoto.jpg              # Profile photo used in the Home section
├── projectvul.jpg             # Screenshot for the Security Vulnerabilities project
├── Tala_AlOqaily_CV_3.docx    # Downloadable CV
└── README.md                  # Project documentation (this file)
```

> **Note:** Rename `project.html` to `index.html` before publishing (e.g., on GitHub Pages), since most static hosts look for `index.html` as the default entry file.

---

## ▶️ How to View / Run the Project

**Option 1 — Open locally:**
1. Download or clone this repository.
2. Make sure `project.html`, `style.css`, and all image/CV files are in the same folder.
3. Double-click `project.html` (or rename it to `index.html`) to open it in your browser.

**Option 2 — Run with a live server:**
1. Open the project folder in VS Code.
2. Install the "Live Server" extension.
3. Right-click `project.html` → **Open with Live Server**.

**Option 3 — View online:**
If hosted (e.g., GitHub Pages), simply visit the live demo link above.

---

## 📌 Notes / Design Decisions

- The color palette is built entirely with CSS custom properties (`--primary`, `--accent`, `--dark`, etc.) defined once in `:root`, making it easy to re-theme the whole site by changing a few variables.
- Animations respect good UX practice by keeping motion subtle (fade/slide-in, gentle pulse) rather than distracting.
- The layout uses Flexbox (`display: flex`) throughout for the header, cards, and content sections, with dedicated media queries at `1023px`, `600px`, and `480px` breakpoints for full responsiveness.

---

## 📬 Contact

- **Phone:** 079 7071717
- **Email:** tala.aloqaili@gmail.com
- **LinkedIn:** [linkedin.com/in/tala-al-oqaili](https://www.linkedin.com/in/tala-al-oqaili-a480272ab/)
- **GitHub:** [github.com/talaaloqaili-arch](https://github.com/talaaloqaili-arch)

---

## 📄 License

This project was created for educational purposes as part of a front-end development course.
