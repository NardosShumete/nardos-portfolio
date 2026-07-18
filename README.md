# Nardos Shumete — Personal Portfolio Website

<div align="center">

![Portfolio Banner](https://img.shields.io/badge/Portfolio-Nardos%20Shumete-22D3EE?style=for-the-badge&logo=google-chrome&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)

A premium, modern personal portfolio website for **Nardos Shumete** — Information Technology Student, Cloud Engineering & Cybersecurity Enthusiast at Debre Berhan University.

**[🌐 View Live Portfolio](https://nardosshumete.github.io/nardos-portfolio/)**

</div>

---

## 📋 About

This is a fully responsive, single-file personal portfolio website built with pure HTML, CSS, and Vanilla JavaScript — no frameworks, no dependencies. It showcases my skills in Information Technology, Cloud Engineering, Cybersecurity, Networking, Full-Stack Web Development, and Smart Security Systems.

The design follows a **premium dark-mode aesthetic** inspired by Framer, Vercel, and Awwwards — featuring glassmorphism, smooth animations, and a modern typographic system.

---

## ✨ Features

- 🌑 **Premium Dark Mode** — Dark `#09090B` background with Cyan, Purple & Emerald accent system
- 💎 **Glassmorphism Cards** — Backdrop-filter blur cards throughout
- 🎞️ **Smooth Animations** — Fade-in on scroll, typing effect, floating blobs, card tilt
- ⌨️ **Typing Animation** — Cycles through 5 professional titles
- 📊 **Animated Counters** — Numbers count up when scrolled into view
- 🧭 **Sticky Navigation** — Blur-on-scroll navbar with active section highlighting
- 📱 **Fully Responsive** — Desktop, laptop, tablet, and mobile
- ♿ **Accessible** — ARIA labels, semantic HTML5, keyboard navigation
- ⚡ **Fast Loading** — Pure HTML/CSS/JS, no build step required
- 🔍 **SEO Optimized** — Meta tags, Open Graph, semantic structure
- 📜 **Scroll Progress Bar** — Gradient progress indicator at top
- 🔼 **Back-to-Top Button** — Smooth scroll back to hero
- 🃏 **3D Card Tilt** — Mouse-tracking perspective tilt on project cards

---

## 🗂️ Project Structure

```
nardos-portfolio/
├── index.html                        # Complete single-file website
├── assets/
│   └── resume/
│       └── Nardos_Shumete_Resume.pdf # Place your resume PDF here
├── .gitignore
└── README.md
```

---

## 🧰 Technologies Used

| Layer | Technology |
|---|---|
| Structure | HTML5 (Semantic) |
| Styling | Vanilla CSS3 (Variables, Grid, Flexbox, Animations) |
| Interactivity | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Inter, JetBrains Mono |
| Icons | Font Awesome 6.5 |
| Hosting | GitHub Pages / Netlify / Vercel |

---

## 📁 Sections

| Section | Description |
|---|---|
| **Hero** | Animated headline, typing effect, avatar, floating tags |
| **Stats** | Animated counters for projects, skills, and expertise |
| **Projects** | 4 real-world project cards with GitHub links |
| **About** | Professional bio with code block and interest pills |
| **Skills** | 7 categorized skill groups with hover effects |
| **Experience** | Timeline of education and hands-on experience |
| **Contact** | Social links, email, View & Download Resume |

---

## 🚀 Local Development

No build tools required. Simply open the file in any modern browser:

### Option 1 — Open directly
```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

### Option 2 — Use a local server (recommended)
```bash
# Python 3
python -m http.server 8080

# Node.js (npx)
npx serve .

# VS Code: Install "Live Server" extension, right-click index.html → Open with Live Server
```

Then visit `http://localhost:8080` in your browser.

---

## 📄 Resume Setup

Before deploying, place your resume PDF in the correct location:

```
assets/resume/Nardos_Shumete_Resume.pdf
```

The **View Resume** button opens the PDF in a new browser tab.  
The **Download Resume** button triggers a direct file download.

---

## 🌐 Deployment

### GitHub Pages (Recommended)

1. Push this repository to GitHub.
2. Go to your repository → **Settings** → **Pages**.
3. Under **Source**, select `main` branch and `/ (root)` folder.
4. Click **Save**.
5. Your site will be live at:  
   `https://nardosshumete.github.io/nardos-portfolio/`

> ⏳ GitHub Pages may take 1–3 minutes to go live after the first push.

---

### Netlify

1. Go to [netlify.com](https://netlify.com) and log in.
2. Click **Add new site** → **Import an existing project**.
3. Connect your GitHub account and select `nardos-portfolio`.
4. Build settings:
   - **Build command**: *(leave blank)*
   - **Publish directory**: `.` (root)
5. Click **Deploy site**.

---

### Vercel

1. Go to [vercel.com](https://vercel.com) and log in.
2. Click **Add New → Project**.
3. Import `nardos-portfolio` from GitHub.
4. Framework preset: **Other**
5. Click **Deploy**.

---

## 🔧 Git Commands — Initial Deployment

Run these commands in the `nardos-portfolio` project folder:

```bash
git init
git add .
git commit -m "Initial portfolio website"
git branch -M main
git remote add origin https://github.com/NardosShumete/nardos-portfolio.git
git push -u origin main
```

### Subsequent Updates
```bash
git add .
git commit -m "Update portfolio content"
git push
```

### Add Resume PDF (after copying it to assets/resume/)
```bash
git add assets/resume/Nardos_Shumete_Resume.pdf
git commit -m "Add resume PDF"
git push
```

---

## 🗃️ Featured Projects

| Project | Category | Stack | Repository |
|---|---|---|---|
| Firewall Rule Management Dashboard | Security / Infrastructure | Laravel, PHP, MySQL, JS | [View →](https://github.com/NardosShumete/Firewall-Rule-Management-Dashboard) |
| Inventory Sales System | Business / Full Stack | Laravel, PHP, MySQL, Bootstrap | [View →](https://github.com/NardosShumete/InventorySalesSystem) |
| Personal Finance Tracker | Mobile Application | Android, Kotlin, SQLite | [View →](https://github.com/NardosShumete/Personal-Finance-Tracker) |
| Clinic Management System | Healthcare / TypeScript | TypeScript, Node.js, MySQL | [View →](https://github.com/NardosShumete/clinic-management) |

---

## 📬 Contact

| Platform | Link |
|---|---|
| 📧 Email | [shumetnardos40@gmail.com](mailto:shumetnardos40@gmail.com) |
| 💼 LinkedIn | [linkedin.com/in/nardos-shumete-265729358](https://www.linkedin.com/in/nardos-shumete-265729358) |
| 🐙 GitHub | [github.com/NardosShumete](https://github.com/NardosShumete) |

---

## 📝 License

This portfolio is open source and available under the [MIT License](LICENSE).

Feel free to fork, customize, and use it as a starting point for your own portfolio — just give credit where it's due!

---

<div align="center">

Made with ❤️ by **Nardos Shumete** · © 2026

</div>
