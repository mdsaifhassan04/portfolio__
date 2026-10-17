# 🌟 Personal Portfolio Website - Md Saif Hassan

A modern, responsive, high-performance developer portfolio website for **Md Saif Hassan**, an engineering student at **Bhagalpur College of Engineering (BCE Bhagalpur)** specializing in **Java, Python, and Web Technologies (HTML/CSS/JavaScript)**.

---

## 🚀 Live Preview & Features

- **Dynamic Hero Section**: Typewriter headline effect highlighting engineering student & developer roles.
- **Dark & Light Mode**: Instant theme toggle with local storage memory.
- **Glassmorphism & Micro-animations**: Modern UI cards, floating skill badges, interactive Java syntax window.
- **Technical Skills Showcase**: Visual progress bars and badges for Java, Python, HTML5, CSS3, JavaScript, and CS fundamentals.
- **Featured Projects Grid**: Highlighted projects tailored for Java (OOP / Management Systems), Python (Automation & Scripting), and Web Development.
- **Academic Timeline**: Bhagalpur College of Engineering (BCE) details and key coursework.
- **Interactive Contact Form**: Client-side validation with instant interactive confirmation.
- **Fully Responsive**: Optimized for desktop, tablet, and mobile displays.

---

## 📁 Project Structure

```
portfolio/
├── index.html          # Semantic HTML5 website structure & content
├── css/
│   └── style.css       # Design system, themes (dark/light), animations, responsive CSS
├── js/
│   └── main.js         # Interactivity (typewriter, dark/light theme, contact form, scroll spy)
└── README.md           # Documentation and setup instructions
```

---

## 🛠️ How to Customize

1. **Update Social Links & Email**:
   - In `index.html`, search for `mailto:saifhassan.bce@gmail.com` and replace it with your active email address.
   - Update `https://github.com` and `https://linkedin.com` with your exact profile URLs.

2. **Add Your Resume PDF**:
   - Save your resume file as `resume.pdf` in the root folder or an `assets/` folder.
   - Update the Resume button `href` in `index.html` to point to `resume.pdf`.

3. **Modify or Add Projects**:
   - In the `#projects` section of `index.html`, update project titles, descriptions, and GitHub links with your personal repositories.

---

## 🌐 How to Deploy (Free)

### Option 1: GitHub Pages (Recommended)
1. Initialize a git repository and push to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/portfolio.git
   git push -u origin main
   ```
2. In your GitHub repository, go to **Settings** > **Pages**.
3. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
4. Your website will be live in 1-2 minutes at `https://<your-username>.github.io/portfolio/`.

### Option 2: Netlify / Vercel
- Simply drag and drop the `portfolio` folder onto [Netlify Drop](https://app.netlify.com/drop) or import from GitHub on Vercel for instant SSL hosting.
