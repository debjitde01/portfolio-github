# GitHub Portfolio Deployment Guide for Dr. Debjit De

This portfolio package includes two complementary components tailored specifically to your computational biology and academic profile:
1. **GitHub Profile README** (`portfolio/profile-readme/README.md`) – A styled profile markdown file that displays directly on your GitHub user profile.
2. **GitHub Pages Academic Website** (`portfolio/website/`) – A modern, mobile-responsive personal academic website ready to be hosted for free on GitHub Pages.

---

## 🚀 Part 1: Setting Up Your GitHub Profile README

Your GitHub Profile README appears on the front page of your GitHub account whenever anyone visits your profile (e.g., `github.com/debjitde`).

### Step-by-Step Instructions:
1. Go to [GitHub](https://github.com) and log into your account (`debjitde01`).
2. Click the **`+`** icon in the top right and select **New repository**.
3. In the **Repository name** field, type: `debjitde01`.
   > *GitHub will display a green banner stating: "You found a secret! `debjitde01/debjitde01` is a special repository that you can use to add a `README.md` to your GitHub profile."*
4. Ensure the repository is set to **Public**.
5. Check the box **"Add a README file"**.
6. Click **Create repository**.
7. In the newly created repository, click on `README.md`, click the edit (pencil) icon, and paste the contents of:
   `portfolio/profile-readme/README.md`
   *(Also upload `portfolio/profile-readme/assets/debjit_de.jpg` to the repository's `assets/` folder so your profile photo displays).*
8. Click **Commit changes**.

---

## 🌐 Part 2: Deploying Your Academic Website to GitHub Pages

GitHub Pages provides free, fast HTTPS hosting for your academic website.

### Option A: Hosting as your primary personal website (`debjitde01.github.io`) [Recommended]
1. Go to [GitHub](https://github.com) and create a new repository.
2. Name the repository: `debjitde01.github.io`.
3. Make sure the repository is **Public**.
4. Clone or upload the contents of the `portfolio/website/` folder to the root of this repository:
   - `index.html` (must be in the root)
   - `style.css`
   - `script.js`
   - `assets/debjit_de.jpg`
   - `assets/Dr_Debjit_De_Resume.pdf`
5. Push or commit the files to the `main` branch.
6. Your website will be live within 1–2 minutes at:
   `https://debjitde01.github.io`

### Option B: Hosting inside a subfolder / project repository
If you prefer naming the repository `portfolio`:
1. Create a repository named `portfolio`.
2. Push all files inside `portfolio/website/` to the repository.
3. In GitHub, go to **Settings** > **Pages** (under Code and automation).
4. Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Your website will be live at:
   `https://debjitde01.github.io/portfolio/`

---

## 🎨 Part 3: Personalization & Optional Tweaks

- **Profile Picture:** Your professional photograph is already configured and placed at `assets/debjit_de.jpg` in both the website and the profile README. To change it in the future, simply overwrite `debjit_de.jpg` with a new image.
- **Social & Academic Links:**
  All your verified links are already pre-wired across `README.md` and `index.html`:
  - GitHub: `https://github.com/debjitde01`
  - LinkedIn: `https://www.linkedin.com/in/dr-debjit-de-207732171/?isSelfProfile=true`
  - Email: `de.debjit92@outlook.com`
  - Google Scholar: `https://scholar.google.com/citations?hl=en&user=-j-7-_AAAAAJ&view_op=list_works&gmla=AERr9JGo0k52wnOcxiFRuRNhbO0Ud8AL7P9JXvN9v356zM_AaW01iPIZopL0tyGhWC1b4TxN0V6s43CngreG5NoC`
  - ORCID: add your ORCID ID (e.g. `0000-000x-xxxx-xxxx`).
- **CV Updates:** Whenever you update your CV, simply replace `assets/Dr_Debjit_De_Resume.pdf` with the latest version.

---
<sub>Crafted with care for Dr. Debjit De • Computational Biology & Applied Microbiology</sub>
