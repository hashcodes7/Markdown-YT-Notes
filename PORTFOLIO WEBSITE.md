In this tutorial, we will:
- [ ] Build a portfolio website
- [ ] Upload the project to GitHub
- [ ] Deploy the website online on GitHub Pages / Cloudflare Pages

---
# 1- Creating React App command

```bash
npm create vite@latest my-react-app -- --template react
```

---
# 2- Prompt for AI Agent
```
**"I need you to build a modern, sleek, and highly stylish portfolio website for me using React and Vite. My resume details are below.**

**Design & Aesthetic Requirements:**

1. **Theme**: Use a deep dark aesthetic (solid `#0a0a0a` background) with vibrant orange (`#f97316`) as the primary accent color. It should feel extremely premium, similar to high-end engineering or agency portfolios.
2. **Typography & Layout**: Use bold, massive typography (sans-serif like Inter). The Hero section should be center-aligned with an orange-bordered "role pill" at the top, a massive white heading, and a grey descriptive paragraph below.
3. **Navbar**: Create a sticky glassmorphic navbar (`backdrop-filter: blur()`). It should have a logo on the left with an orange icon, centered navigation links, and a solid orange 'Hire Me' button on the right along with a custom dark/light theme toggle switch.
4. **Interactive Background**: Integrate an interactive particle network in the background using `react-tsparticles` and `tsparticles` (make sure versions match to avoid Vite errors). The particles and connecting lines should be orange and react to mouse hovers (e.g., a grab or repulse effect).
5. **Typewriter Effect**: In the Hero section, use `react-simple-typewriter` to dynamically cycle through my core expertise areas (e.g., 'AI Automation Engineer', 'Full Stack Developer', 'LLM & RAG Enthusiast') with an orange cursor.
6. **Icons**: Use `react-icons/fa` for all brand and social icons (GitHub, LinkedIn) to avoid missing export errors.

**Configuration & Deployment Requirements:**

1. Ensure the `package.json` specifies Node.js 24 compatibility (`"engines": { "node": ">=24.0.0" }`).
2. Create a standard GitHub Actions deployment workflow file (`.github/workflows/deploy.yml`) for deploying a Vite app. Specifically, include the environment variable `FORCE_JAVASCRIPT_ACTIONS_TO_NODE24: true` to suppress the GitHub Actions Node 20 deprecation warnings.
3. I am deploying to the root of a custom domain/Cloudflare Pages, so leave the `base` path in `vite.config.js` as the default (do not set it to a subpath to avoid MIME type errors).
```
# 3- Initialize Git

```bash
git init
```

# 📦 Step 4: (If Git never set before) set Git Username and email

```bash
git config --global user.name "your_name"
git config --global user.email "your_email@email.com"
```

---
# 🔗 Step 5: Add GitHub Remote Repository

Replace the link with your repository URL.

```bash
git remote add origin https://github.com/username/portfolio-website.git
```

# 🚀 Step 6: (Terminal Commands) These steps can be done from source control
---

# ➕ Step 6.1 : Add Files

```bash
git add .
```

---

# 💾 Step 6.2 : Commit Code

```bash
git commit -m "Initial Portfolio Website"
```

---
# ☁️ Step 6.3: Push Code to GitHub

```bash
git push -u origin main
```

---

# 🌍 Step 7: Deploy Website

- [ ] Vercel
- [ ] Netlify
- [ ] GitHub Pages
- [ ] Cloudflare Pages

---

# ❤️ Thanks

If this helped you you can go to youtube.com/@hashcodes7 and 
- Like
- Subscribe 
- Share 
Check out github.com/hashcodes7 for more projects and codes for this and upcoming videos

