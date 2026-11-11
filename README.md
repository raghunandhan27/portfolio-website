# 🚀 Raghunandhan P - Personal Developer Portfolio

A modern, high-performance, responsive personal portfolio website built with semantic HTML5, modern Tailwind CSS, and vanilla JavaScript. Features a dark/light theme switcher, animated typewriter hero, categorized interactive project showcase, academic & college experience section, technical skills matrix, and a live demo contact form.

---

## 🌟 Key Features

1. **Modern Developer Aesthetics**: Glassmorphism cards, ambient gradient glow accents, and responsive layout across desktop, tablet, and mobile.
2. **Dark / Light Mode**: Seamless theme toggle with local storage persistence (defaults to sleek dark mode).
3. **Interactive Hero**: Dynamic typewriter effect highlighting your core domains, live status badge, and an interactive code card representation.
4. **College & Education Showcase**:
   - Degree, College name, CGPA/Honors.
   - Core subjects & coursework (DSA, Operating Systems, DBMS, AI & ML).
   - Campus leadership roles (Tech Club Lead, Hackathon Organizer) and awards.
5. **Areas of Interest & Passions**:
   - Technical Interests (Generative AI, Full-Stack Web Development, Cloud & DevOps).
   - Extracurriculars & Hobbies (Competitive coding, gaming, tech reading, photography).
6. **Categorized Project Showcase**:
   - Filter tabs (`All`, `AI / ML`, `Full-Stack`, `Campus & Tools`).
   - Project cards with live demo & GitHub repository links, tech stack tags, and badges.
7. **Interactive Contact Form**:
   - Client-side form handling with demo toast feedback notifications.
   - Direct social & professional profiles (Email, LinkedIn, GitHub, Twitter, LeetCode).

---

## 📂 Project Structure

```
portfolio-website/
├── index.html        # Main semantic markup & content structure
├── style.css         # Custom animations, transitions, and scrollbar styling
├── script.js         # Theme toggle, typewriter, project filters, contact form handler
└── README.md         # Documentation & guide for customizations
```

---

## ⚡ How to Open & Preview

### Option 1: Direct Browser Launch (No installation required)
Simply double-click `index.html` or open it with your browser:
- On Windows: Right-click `index.html` &rarr; **Open with** &rarr; **Google Chrome** (or Edge/Brave/Firefox).

### Option 2: Using Python's Local Server
Run this in PowerShell from the `portfolio-website` directory:
```powershell
python -m http.server 3000
```
Then visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## ✏️ How to Customize Your Details

Open `index.html` in your favorite code editor to personalize your info:

1. **Name & Title**:
   - Search for `Raghunandhan P` in `index.html` to update your display name and meta tags.
2. **College Information**:
   - Look for `<section id="education">`.
   - Update `College of Engineering & Technology` with your university or college name.
   - Update your CGPA, expected graduation year, and specific coursework.
3. **Interests**:
   - Look for `<section id="interests">`.
   - Edit or add your favorite technology domains and hobbies.
4. **Projects**:
   - Look for `<section id="projects">`.
   - Update project titles, descriptions, and replace the demo `href="https://github.com"` links with your actual GitHub repository links.
5. **Resume / CV**:
   - Place your resume PDF in the directory (e.g., `resume.pdf`) and change the resume button `href` to `href="resume.pdf" target="_blank"`.
6. **Social Links**:
   - Replace the placeholder links (`github.com`, `linkedin.com`, `raghunandhan.demo@example.com`) with your actual profiles.

---

## 🌐 Free 1-Click Deployment

- **GitHub Pages**: Push this folder to a GitHub repository, head to **Settings** &rarr; **Pages**, and select `main` branch root. Your site will be live instantly!
- **Netlify / Vercel**: Drag and drop this folder directly into the Netlify or Vercel dashboard for an instant free HTTPS domain.
