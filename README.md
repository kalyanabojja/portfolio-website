# 💼 Bojja Kalyana Prabha — Personal Portfolio Website

A fully responsive personal portfolio website built with **HTML**, **CSS**, and **JavaScript**, showcasing my professional experience, projects, skills, and contact information.

---

## 🌐 Live Demo

🔗 [Add your live URL here](#)

---

## 📸 Preview

> *(Add a screenshot — e.g., `![Portfolio Preview](./image.jpeg)`)*

---

## ✨ Features

- ✅ Fully **responsive design** — mobile, tablet, and desktop friendly
- 🍔 **Hamburger menu** for mobile navigation (`fa-bars` toggle)
- 👤 **About** section with photo, name, title, CV download, and social links
- 💼 **Experience** section with role cards (Software Engineer, Graphic Designer, System Designer, Content Manager)
- 📁 **Projects** section with Live Demo and GitHub links for 3 projects
- 📬 **Contact** section with an email input form
- 🔗 **Footer** with navigation links and copyright
- 🎨 Font Awesome icons for social media and UI elements

---

## 🗂️ Project Structure

```
portfolio/
│
├── index.html          # Main HTML — all sections (About, Experience, Projects, Contact)
├── style.css           # All styles and responsive layout
├── script.js           # JavaScript — mobile menu toggle & interactions
│
├── image.jpeg          # Your profile photo (used in About & Experience)
├── project-1.jpg       # Screenshot for Project 1
├── project-2.jpg       # Screenshot for Project 2
└── project-3.jpg       # Screenshot for Project 3
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Page structure and all sections |
| CSS3 | Styling, Flexbox/Grid, responsiveness |
| JavaScript (ES6) | Mobile nav toggle, interactions |
| [Font Awesome 7](https://fontawesome.com/) | Icons (code, laptop, envelope, GitHub, LinkedIn) |

---

## 📄 Sections Overview

### 👤 About
- Profile photo (`image.jpeg`)
- Name: **Bojja Kalyana Prabha**
- Title: **Software Engineer**
- Buttons: **Download CV** | **Contact**
- Social icons: **GitHub** | **LinkedIn**

### 💼 Experience
Four experience cards:
| Role | Duration |
|------|----------|
| Software Engineer | 5 years |
| Graphic Designer | 2 years |
| System Designer | 2 years |
| Content Manager | 1 year |

### 📁 Projects
Three project cards, each with:
- Project thumbnail image
- Title & description
- **Live Demo** button
- **GitHub Repository** button

### 📬 Contact
- Email input field
- Submit button

---

## ⚙️ Setup & Local Development

### Prerequisites
- Any modern browser (Chrome, Firefox, Edge)
- [VS Code](https://code.visualstudio.com/) *(recommended)*
- [Live Server Extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) *(for hot reload)*

### Steps

**1. Clone the repository**
```bash
git clone https://github.com/your-username/portfolio.git
cd portfolio
```

**2. Add your assets**

Make sure these files exist in the root folder:
```
image.jpeg      ← Your profile photo
project-1.jpg   ← Project 1 screenshot
project-2.jpg   ← Project 2 screenshot
project-3.jpg   ← Project 3 screenshot
style.css       ← Your stylesheet
script.js       ← Your JavaScript file
```

**3. Run locally**

- Open the folder in VS Code
- Right-click `index.html` → **"Open with Live Server"**
- Portfolio opens at `http://127.0.0.1:5500`

Or simply double-click `index.html` to open in your browser.

---

## 🚀 Deployment

### ✅ GitHub Pages (Free)

1. Push all files to a GitHub repository
2. Go to repo → **Settings** → **Pages**
3. Set Source: `main` branch → `/ (root)` → **Save**
4. Live at: `https://your-username.github.io/portfolio/`

### ✅ Netlify (Recommended)

1. Go to [netlify.com](https://www.netlify.com/) → Sign in
2. **Add new site** → **Deploy manually**
3. Drag and drop your entire portfolio folder
4. Instant live URL provided — connect a custom domain anytime

### ✅ Vercel

1. Go to [vercel.com](https://vercel.com/) → Sign in with GitHub
2. **New Project** → Import your repository
3. Click **Deploy** — done!

---

## 🔧 Customization Guide

| What to change | Where |
|---------------|-------|
| Your name & title | `index.html` → About section |
| Profile photo | Replace `image.jpeg` |
| Experience roles & years | `index.html` → Experience section `.grid-card` divs |
| Project titles, descriptions, links | `index.html` → Projects section `.project-card` divs |
| Project images | Replace `project-1.jpg`, `project-2.jpg`, `project-3.jpg` |
| GitHub & LinkedIn URLs | `index.html` → About section `.socials` icons (add `href`) |
| CV download link | `index.html` → About section "Download CV" button |
| Colors & fonts | `style.css` |
| Mobile menu behavior | `script.js` |

---

## ⚠️ Known Issues / To-Do

- [ ] Add `href` URLs to GitHub and LinkedIn social icons
- [ ] Add `href` to "Visit My Github" header button
- [ ] Wire up the Contact form to a backend or [EmailJS](https://www.emailjs.com/)
- [ ] Add `#` anchor links in the footer (currently missing the `#` prefix)
- [ ] Fix typo in HTML: `class-"grid"` → `class="grid"` in Experience section
- [ ] Verify Font Awesome 7 CDN link (v7 may not be publicly released; v6 is stable)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Made with ❤️ by **Bojja Kalyana Prabha**
