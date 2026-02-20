# 🚀 Manisha Portfolio — AI & Python Projects

> A fully responsive, animated personal portfolio website built with **pure HTML, CSS & JavaScript** — showcasing AI/ML projects completed during a hands-on workshop.

---

## 📸 Overview

This single-file portfolio is designed for a B.Sc (Computer Science) student at **Haldia Institute of Management** (2nd Year, 4th Semester). It highlights two end-to-end data science projects, technical skills, workshop milestones, and contact information — all in a sleek dark-themed UI.

---

## ✨ Features

- **Animated particle canvas background** — dynamic floating dots with gradient connection lines
- **Typing animation** — cycles through key interests (EDA, Linear Regression, Colab notebooks, LLMs)
- **Scroll reveal animations** — cards fade in as you scroll using `IntersectionObserver`
- **Sticky glassmorphism navbar** with blur backdrop effect
- **Scroll progress bar** — fixed gradient bar at the top tracking read progress
- **Responsive mobile drawer menu** — hamburger nav for small screens
- **Animated gradient blobs** — ambient background depth effect
- **One-file setup** — no build tools, no dependencies, no frameworks

---

## 🗂️ Sections

| Section | Description |
|---|---|
| **Hero** | Name, tagline, typing effect, quick stats |
| **About** | Who I am, what I'm learning, mentorship |
| **Skills & Tools** | Python, Pandas, Matplotlib, EDA, scikit-learn |
| **Featured Projects** | EDA Dashboard (Titanic) + House Price Prediction |
| **Workshop Timeline** | AI/ML workshop sessions and milestones |
| **Contact** | Links to GitHub, LinkedIn, Instagram + Mentor info |

---

## 🧪 Projects

### 📊 Project 1 — EDA Dashboard (Titanic Dataset)
Exploratory Data Analysis on the classic Titanic dataset.
- Loaded and explored the dataset using **Pandas**
- Handled missing values with mean/mode imputation
- Built visualizations: survival count, gender vs survival, age distribution
- Wrote presentation-ready insights from the patterns found

**Tech:** `Pandas` · `Matplotlib` · `Google Colab`

---

### 🏠 Project 2 — House Price Prediction
First supervised ML model using **Linear Regression**.
- Performed train-test split on structured housing data
- Trained model using **scikit-learn** `LinearRegression`
- Evaluated with **RMSE** and **R² score**
- Visualized Actual vs Predicted values and residual errors

**Tech:** `scikit-learn` · `Pandas` · `Matplotlib` · `Google Colab`

---

## 🛠️ Tech Stack

```
HTML5 · CSS3 (Custom Properties, Grid, Flexbox) · Vanilla JavaScript
Font Awesome 6 (CDN) · Canvas API (particles) · IntersectionObserver API
```

No npm. No build step. Just open `index.html` in a browser.

---

## ⚙️ Setup & Customization

**1. Clone the repo**
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

**2. Open in browser**
```bash
open index.html
# or just double-click the file
```

**3. Personalize your links** — Edit the `LINKS` object at the top of the `<script>` tag:
```js
const LINKS = {
  githubProfile:    "https://github.com/your-username",
  linkedin:         "https://linkedin.com/in/your-profile",
  project1Repo:     "https://github.com/your-username/project-1",
  project2Repo:     "https://github.com/your-username/project-2",
  project1Notebook: "https://colab.research.google.com/...",
  project2Notebook: "https://colab.research.google.com/...",
  email:            "your@email.com"
};
```

**4. Update your name** — Replace `Student Name` in the `<h1>` tag with your actual name.

**5. Quick personalization via URL params** *(optional)*
```
index.html?name=Your+Name&github=https://github.com/your-username
```

---

## 📁 File Structure

```
📦 your-repo-name/
 ┗ 📄 index.html       # Entire site — HTML + CSS + JS in one file
 ┗ 📄 README.md        # This file
```

---

## 📱 Responsive Design

The layout adapts cleanly to all screen sizes:
- **Desktop (>920px):** Full multi-column grid layout with visible nav links
- **Mobile (≤920px):** Single-column stacked layout with hamburger drawer menu

---

## 🎓 Mentorship

Projects built under the guidance of **SK Sahil** (AI Developer & Tutor / Code_ScholarEU), covering ML basics, Google Colab workflow, GitHub version control, and portfolio building.

---

## 📄 License

This project is open for personal and educational use. Feel free to fork and adapt it for your own portfolio.

---

*Built with HTML, CSS & JS · Ready for GitHub Pages*
