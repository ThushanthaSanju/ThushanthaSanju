# GitHub Profile README — Companion Guide

---

## 3 Headline Options

1. **"Engineering AI Systems That Ship Beyond the Prototype"**
   — Positions you as someone who bridges research and production.

2. **"From Clinical NLP to Production Microservices"**
   — Shows range: domain-specific AI + real systems engineering.

3. **"Precision in Code. Reliability in Delivery."**
   — Short, punchy, signals craftsmanship and execution.

---

## 3 Tagline Options

1. **"Full-stack engineer building applied AI systems with production-grade reliability."**
   — Clean, professional, covers both sides of your identity.

2. **"I build software and machine learning systems that work outside a Jupyter notebook."**
   — Slightly bold, differentiates from research-only ML people.

3. **"Shipping reliable AI — from transformer pipelines to scalable product systems."**
   — Technical, modern, positions you at the intersection.

---

## Recommended Visual Assets

### Must-Have (already included in both versions)

| Asset | Service/URL | Purpose |
|-------|-------------|---------|
| **Animated Header/Footer** | [capsule-render](https://github.com/kyechan99/capsule-render) | Waving gradient banners at top/bottom |
| **Typing SVG** | [readme-typing-svg](https://github.com/DenverCoder1/readme-typing-svg) | Animated rotating taglines |
| **GitHub Stats Card** | [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) | Stats overview card |
| **Top Languages Card** | [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) | Language breakdown |
| **Streak Stats** | [github-readme-streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats) | Contribution streak |
| **Activity Graph** | [github-readme-activity-graph](https://github.com/Ashutosh00710/github-readme-activity-graph) | Contribution graph visualization |
| **Shields.io Badges** | [shields.io](https://shields.io/) | Tech stack and link badges |
| **Skill Icons** | [skillicons.dev](https://skillicons.dev/) | Dark-themed skill icon rows (V2) |
| **Animated Divider GIF** | Hosted on GitHub user content | Rainbow line dividers |
| **Profile View Counter** | [komarev](https://github.com/antonkomarev/github-profile-views-counter) | View count badge |
| **Coding GIF** | Giphy | Developer animation in About section |

### Optional Enhancements (V2 includes some)

| Asset | Service/URL | Purpose |
|-------|-------------|---------|
| **GitHub Trophies** | [github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy) | Achievement trophy row |
| **Contribution Snake** | [snk](https://github.com/Platane/snk) | Animated snake eating contributions (requires GitHub Action setup) |
| **Dev Quote** | [github-readme-quotes](https://github.com/PiyushSuthar/github-readme-quotes) | Random developer quote |
| **Pinned Repo Cards** | github-readme-stats `/api/pin/` | Visual repo cards |
| **Wakatime Stats** | [github-readme-stats wakatime](https://github.com/anuraghazra/github-readme-stats#wakatime-stats-card) | Coding time breakdown (requires Wakatime setup) |

---

## Customization Guide — What You Need to Replace

### Required Changes

1. **GitHub Username**
   - Search and replace all instances of `ThushanthaSanju` with your exact GitHub username
   - This affects: stats cards, streak stats, activity graph, pinned repos, snake, trophies

2. **Pinned Repo Cards (V2 only)**
   - Replace `ICD-Code-Recommender` and `Stock-Crypto-Prediction` with your actual repository names
   - URL format: `github-readme-stats.vercel.app/api/pin/?username=YOUR_USERNAME&repo=YOUR_REPO_NAME`

3. **Links** (already set correctly in both versions)
   - Portfolio: `https://www.t-sanju.me/`
   - LinkedIn: `https://www.linkedin.com/in/thushantha-sanju-718288129/`
   - Email: `thushanthasanju8@gmail.com`

4. **Coding GIF**
   - The included GIF URL from Giphy should work, but if it breaks, replace with any developer-themed GIF
   - Search Giphy for "coding" or "programming" and use the embed URL

### Optional Setup Steps

5. **Contribution Snake (V2)**
   - Requires a GitHub Actions workflow in your profile repo
   - Create `.github/workflows/snake.yml` in your `ThushanthaSanju/ThushanthaSanju` repo
   - See: https://github.com/Platane/snk for setup instructions
   - If you skip this, remove the snake `<picture>` block from V2

6. **Vercel Deployment for Stats**
   - The default `github-readme-stats.vercel.app` may rate-limit
   - For reliability, fork [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) and deploy your own Vercel instance
   - Then replace `github-readme-stats.vercel.app` with your deployment URL

7. **Color Customization**
   - Primary blue: `58a6ff` (GitHub's link blue) — used throughout
   - Background: `0d1117` (GitHub dark mode background)
   - To change the accent color, search-replace `58a6ff` with your preferred hex color
   - To change the accent for `1f6feb`, replace with your preferred darker blue

### File Placement

- Your GitHub profile README lives in a repo named exactly `ThushanthaSanju/ThushanthaSanju`
- The file must be named `README.md` at the repo root
- Make sure the repo is **public**

---

## Version Comparison

| Feature | V1 (Clean & Premium) | V2 (Bold & Design-Heavy) |
|---------|----------------------|--------------------------|
| Header style | Waving gradient banner with name | Cylinder banner + animated name typing |
| About section | Paragraph + GIF table | YAML code block + GIF + credential badges |
| Tech stack | Shields.io badges grouped | Skill icons (skillicons.dev) + badges |
| Projects | Markdown table cards | Pinned repo cards + detailed table cards |
| Experience | Clean table | ASCII art terminal block |
| Trophies | ❌ | ✅ |
| Contribution snake | ❌ | ✅ (requires Action setup) |
| Dev quotes | ❌ | ✅ |
| Overall feel | Professional & recruiter-ready | Developer showcase & visually maximal |

**Recommendation:** Start with **V1** for immediate deployment — it requires zero extra setup. Upgrade to **V2** elements gradually as you set up the GitHub Actions for the snake animation and fork the stats services.
