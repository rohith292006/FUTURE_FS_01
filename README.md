# FUTURE_FS_01
"A fully responsive personal portfolio built with HTML, CSS &amp; JavaScript. Features an interactive Power Core animation, typewriter effect, EmailJS contact form, scroll animations, and SEO optimization. Showcases projects, internships, skills &amp; resume. Built as Task 1 @ Future Interns."

### 🌐 Personal Portfolio Website — S. Rohith

The Personal Portfolio Website is a fully responsive, client-side web application developed using HTML, CSS, and JavaScript that professionally showcases academic background, technical skills, internship experience, and real-world project work. The application is structured as a single-page portfolio with smooth scroll navigation, interactive animations, and a functional contact system — built to meet professional recruiter and client standards.

The interface is carefully crafted with a dark command-center aesthetic, featuring a custom Power Core hero animation, particle constellation background, and section-by-section reveal effects — designed to leave a strong first impression while maintaining clean, readable content presentation.

---

### 🎯 Objectives of the Project

* To design a professional, fully responsive personal portfolio suitable for recruiter and client review.
* To implement an interactive hero section with a canvas-based Power Core animation representing technical skill domains.
* To integrate a functional contact form with real-time email delivery using the EmailJS API.
* To demonstrate advanced JavaScript DOM manipulation, Canvas API usage, and asynchronous event handling.
* To build an SEO-friendly structure using semantic HTML5, meta tags, and Open Graph properties for better search visibility.
* To deliver a complete professional profile including projects, internships, education, certifications, and a downloadable resume.

---

### 🧩 Key Features

* **Interactive Power Core Animation**: A custom Canvas API animation in the hero section featuring dual orbital rings with comet particle trails, clickable skill tags that reveal proficiency cards, and a power surge mode triggered by clicking the core.
* **Typewriter Effect**: Animated role cycling in the hero section smoothly transitions between titles — Data Science Enthusiast, Full-Stack Developer, Problem Solver, and more.
* **Particle Constellation Background**: A floating network of connected particles renders across the full page background, creating a subtle dynamic depth effect.
* **Fully Responsive Layout**: Adapts seamlessly across all screen sizes — desktop, tablet, and mobile — using CSS Flexbox, Grid, and media queries with fluid font scaling via `clamp()`.
* **EmailJS Contact Form**: Visitor messages are delivered directly to the developer's Gmail inbox without any backend server, featuring real-time validation, loading state, and success/error feedback.
* **Resume Download**: The Hire Me button in the navigation opens the standalone resume in a new tab and triggers the browser print dialog for instant PDF export.
* **Scroll Reveal Animations**: All cards and section elements animate into view using the IntersectionObserver API as the visitor scrolls down the page.
* **Active Navigation Highlighting**: The current visible section is automatically detected and its corresponding nav link is highlighted using scroll position tracking.
* **Back to Top Button**: A fixed button appears after scrolling 400px and smoothly returns the visitor to the top of the page.
* **SEO Optimized Structure**: Includes descriptive meta tags, Open Graph tags for LinkedIn and WhatsApp previews, semantic HTML5 elements, and proper heading hierarchy.

---

### 🛠️ Technologies Used

| Technology | Description |
| --- | --- |
| **HTML5** | Semantic page structure, SEO meta tags, Open Graph properties, accessible aria labels, and form input controls. |
| **CSS3** | Custom CSS properties (variables), Flexbox and Grid layouts, keyframe animations, responsive media queries, and backdrop blur effects. |
| **JavaScript (ES6+)** | Canvas API animation engine, DOM manipulation, IntersectionObserver scroll reveals, async/await contact form handling, and typewriter logic. |
| **EmailJS** | Client-side email delivery API that routes contact form submissions directly to Gmail without a backend server. |
| **Canvas API** | Powers the interactive Power Core hero animation including dual orbital rings, comet particle trails, burst effects, and HUD elements. |
| **Google Fonts** | Space Grotesk (headings), Inter (body text), and JetBrains Mono (code elements and labels) loaded via CDN. |

---

### ⚙️ Working Methodology

1. **Page Load**: Fonts and EmailJS SDK load from CDN. The particle canvas initializes across the full viewport. The Power Core canvas sizes itself relative to the available hero space.
2. **Hero Interaction**: The typewriter cycles through role titles. The Power Core animation runs continuously with dual orbital skill tag rings. Clicking the core triggers power surge mode; clicking a skill tag opens a proficiency card overlay.
3. **Scroll Behaviour**: As the visitor scrolls, the IntersectionObserver fires reveal animations on cards and sections entering the viewport. The navbar compresses and active nav links update automatically.
4. **Contact Submission**: The visitor fills in the contact form. JavaScript validates name, email, and message fields in real time. On submission, EmailJS sends the data asynchronously to the developer's inbox and displays success or error feedback without reloading the page.
5. **Resume Download**: Clicking Hire Me opens `resume.html` in a new browser tab and triggers the print dialog after a short delay, allowing the visitor to save a clean PDF copy.
6. **Mobile Behaviour**: On screens below 768px, the navbar collapses to a hamburger menu, the hero stacks vertically with the Power Core resizing below the text, and all multi-column grids collapse to single-column layouts.

---

### 📁 Project Structure

```
FUTURE_FS_01/
│
├── index.html        ← Main portfolio (HTML + CSS + JS — single file)
├── resume.html       ← Standalone HTML resume optimized for PDF print export
└── README.md         ← Project documentation
```

---

### 🚀 Setup & Deployment

**View Locally**
```bash
# Clone the repository
git clone https://github.com/rohith292006/FUTURE_FS_01.git

# Navigate into the folder
cd FUTURE_FS_01

# Open directly in browser
# Double-click index.html OR run a local server:
npx live-server
```

**Deploy on GitHub Pages**
```bash
# Push code to GitHub
git add .
git commit -m "Deploy portfolio — FUTURE_FS_01"
git push origin main

# In GitHub: Settings → Pages → Source: main branch → / (root) → Save
# Live at: https://rohith292006.github.io/FUTURE_FS_01
```

**Configure EmailJS (Contact Form)**
```javascript
// Replace in index.html script section:
emailjs.init('YOUR_PUBLIC_KEY');
emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', templateParams);
```
1. Create a free account at [emailjs.com](https://www.emailjs.com)
2. Add Gmail as an email service → copy **Service ID**
3. Create an email template → copy **Template ID**
4. Copy **Public Key** from Account → General settings

---

### 📂 Projects Showcased

| # | Project | Live Demo | Tech Stack |
| --- | --- | --- | --- |
| 01 | Zero-Knowledge Vault | [Live](https://rohith292006.github.io/zero-knowledge-vault/) | HTML5, CSS3, JavaScript ES6+, Web Crypto API |
| 02 | NeoTask Pro | [Live](https://rohith292006.github.io/To-DO-List/) | HTML5, CSS3, JavaScript, LocalStorage API |
| 03 | TN Govt Marksheet Generator | [Live](https://rohith292006.github.io/Tamil-Nadu-Government-School-Marksheet-Generator/) | HTML5, CSS3, JavaScript ES6+ |
| 04 | Personal Portfolio Website | [Live](https://rohith292006.github.io/FUTURE_FS_01) | HTML5, CSS3, JavaScript ES6+, EmailJS, Canvas API |

---

### ✅ Task Requirements Checklist

* [x] Interactive resume & portfolio sections
* [x] Responsive design — works on mobile & desktop
* [x] Contact form with email notifications via EmailJS
* [x] SEO-friendly structure with meta and Open Graph tags
* [x] Live portfolio website hosted on GitHub Pages
* [x] Public GitHub repository with source code
* [x] README with project details, setup & deployment steps
* [x] Professional enough to present to a recruiter or client

---

### 📌 Applications

* Professional profile for recruiter and client outreach.
* Task 1 submission for the Future Interns Full Stack Web Development track.
* Reference design for building interactive single-page portfolio websites.
* Demonstration of Canvas API animation, EmailJS integration, and responsive CSS architecture.

---

### 👨‍💻 Developer Information

* **Developer:** S. Rohith
* **Track:** Full Stack Web Development — Future Interns (Track Code: FS)
* **Task:** Task 1 — `FUTURE_FS_01`
* **Institution:** SRM Madurai College of Engineering & Technology (SRM MCET)
* **Project Type:** Professional Portfolio / Internship Task Submission
* **Target Environment:** Client-Side Web Browsers (Standalone — No Backend Required)
* **LinkedIn:** [rohith-s-99b914385](https://www.linkedin.com/in/rohith-s-99b914385/)
* **GitHub:** [rohith292006](https://github.com/rohith292006)
* **Email:** rohith20062908@gmail.com

---

*Built as Task 1 @ Future Interns · Full Stack Web Development Track · 2026*
*Still training. Still building. Still leveling up. 🔥*
