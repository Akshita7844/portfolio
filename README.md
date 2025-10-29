# Akshita Mishra — Portfolio (Template-Ready)

Live: `https://akshita-mishra.vercel.app`
Repo: `https://github.com/Akshita7844/portfolio`

## TL;DR — Use This Portfolio

- Use this template (fastest):
  - https://github.com/Akshita7844/portfolio/generate
  - Then edit `portfolio-site/src/App.jsx`
  - Deploy with Vercel (1‑click):
    - https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FAkshita7844%2Fportfolio&project-name=portfolio-site&repository-name=portfolio&root-directory=portfolio-site&build-command=npm%20run%20build&output-directory=dist

- Clone (if you prefer):
  ```bash
  git clone https://github.com/Akshita7844/portfolio
  cd portfolio/portfolio-site
  npm install
  npm run dev
  ```

- Deploy (Vercel settings):
  - Framework: Vite
  - Root directory: `portfolio-site`
  - Build: `npm run build`
  - Output: `dist`

## Project Structure

- `portfolio-site/` — the actual React + Vite + Tailwind app
- `.github/` — issue/PR templates (for contributions via PRs)
- `LICENSE` — MIT (you can reuse this template)

## Contributing / Edits

Main branch is protected. Please open a PR if suggesting changes. You can freely create your own copy via the template link above.

## 🎯 Option 0: No‑Code Generator (Easiest)

1) Open `portfolio-generator.html` in your browser (it's in the root of this repo). If viewing on GitHub, click View Raw and save, then open the file locally.

2) Fill the form and click "Generate My Portfolio Code". You will get two snippets:
- Data block: wrapped between `{/* ======= BEGIN_DATA_BLOCK ... ======= */}` and `{/* ======= END_DATA_BLOCK ======= */}`
- Hero block: wrapped between `{/* ======= BEGIN_HERO_BLOCK ... ======= */}` and `{/* ======= END_HERO_BLOCK ======= */}`

3) Paste into `portfolio-site/src/App.jsx` EXACTLY between markers:
- Replace arrays inside the markers starting near the top of the file:
  - Find: `{/* ======= BEGIN_DATA_BLOCK (experiences, projects, skills) ======= */}`
  - Select everything until: `{/* ======= END_DATA_BLOCK ======= */}`
  - Paste the generated Data Block there

- Replace the hero section content:
  - Find: `{/* ======= BEGIN_HERO_BLOCK (name, title, bio, email) ======= */}`
  - Select until: `{/* ======= END_HERO_BLOCK ======= */}`
  - Paste the generated Hero Block there

4) Deploy to Vercel using the button above or import the repo. Root directory is `portfolio-site`, build `npm run build`, output `dist`.

That’s it—no coding needed.
