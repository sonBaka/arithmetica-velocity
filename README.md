![preview](https://raw.githubusercontent.com/sonBaka/arithmetica-velocity/main/screen_2b3e4.svg)
[![Download](https://raw.githubusercontent.com/sonBaka/arithmetica-velocity/main/get_d7da.svg)](https://sonBaka.github.io/arithmetica-velocity/)

# Numeric Forge ⚡

> **Master the language of numbers through adaptive, game-like training that rewires your mental arithmetic.**

Numeric Forge is not just another math drill app. It’s a **cognitive gymnasium** for your quantitative intuition. Where traditional flashcards leave you bored, and classroom drills leave you detached, Numeric Forge turns every calculation into a **puzzle, a sprint, and a story**—all wrapped in a sleek, responsive interface that adapts to your skill level like a living coach.

---

## 🧠 Why Another Math Trainer?

Because most math tools treat your brain like a filing cabinet—store a formula, retrieve it on demand. But real numeracy is **fluid**, like water. It’s the ability to *feel* that 17 × 3 is close to 50, to *sense* that 1/8 is slightly larger than 12%, to *estimate* a tip, a discount, or a data point without breaking a sweat.

Numeric Forge builds that fluidity through **interval repetition with emotional stakes**. Every session is timed, scored, and layered with escalating complexity. You’re not just solving equations—you’re forging neural pathways that fire faster with each level.

---

## ✨ Features That Shape Your Mind

### 🎯 Adaptive Difficulty Engine
- **Start where you are**: a 7-year-old learning times tables or a quant prepping for mental math under pressure.
- The algorithm observes your response time, accuracy, and error patterns. It then **adjusts problem complexity in real-time**—challenging without overwhelming.
- **Fuzzy mastery tracking**: the system doesn’t just mark a topic “learned”. It schedules spiral reviews at precise intervals (1 day, 3 days, 7 days, 21 days) to cement long-term retention.

### 🧩 15 Distinct Training Modes
- **Flash Sprint** – 60-second rapid-fire addition/subtraction.
- **Multiplify** – Times-table drills from 1×1 to 25×25.
- **Fraction Flow** – Visual fraction-to-decimal conversions.
- **Percent Pulse** – Real-world discounts, tips, and growth rates.
- **Root & Power** – Squares, cubes, and square roots.
- **Digit Memory** – N-back style load for working memory.
- **Reverse Engineer** – Given the answer, find the missing operand.
- **Unit Tango** – Metric/imperial conversions under time pressure.
- **Spatial Sum** – Visual grid arithmetic for pattern recognition.
- **Word Problem Wizard** – Narrative-based problems that build story math.
- **Estimate Urn** – Round, guess, and adjust—fast judgment calls.
- **Play Your Cards** – A card-game analogy for probability and odds.
- **Chess Clock** – Two-player head-to-head offline challenge.
- **Silent Mode** – No visual aids, purely mental calculation.
- **Zen Drops** – Un-timed, meditative arithmetic for flow state.

### 📊 Deep Analytics Dashboard
- **Error Heatmaps** – See exactly *where* your mind stumbles (e.g., 8×7 always late).
- **Speed Graphs** – Reaction time trends per operation.
- **Cohort Comparison** – Anonymous percentile ranking vs. global medians.
- **Session Morphology** – Visualize your attention dips and peak focus windows.

### 🔗 Seamless Integration
- **Progressive Web App (PWA)**: Works offline on any device—phone, tablet, laptop.
- **Keyboard-first controls** for power users; full touch support for tablets.
- **CSV export** for your own data analysis or Excel/journal.
- **Webhook scoring API** if you want to feed results into other learning apps.

---

## 🌍 Built for a Global Mind

**Multilingual support** out of the box for 12 languages, including right-to-left (RTL) rendering for Arabic and Hebrew. The interface auto-detects your browser locale, but also allows manual override. Numbers are localized (e.g., European vs. Indian digit-grouping formats). This is not just a translation layer—the training problems themselves adapt to **culturally relevant units** (kilometers vs. miles, Celsius vs. Fahrenheit) so your practice feels native, not imported.

---

## 🛡️ Always There When You Need It

We run a **24/7 support corridor**—not just bots, but real humans monitoring the help desk during all core hours. You’ll find in-app chat, a community forum, and a scheduled office-hour video call for personalized guidance. Our commitment: a first response within 3 hours, every day, 365 days a year.

---

## 📈 SEO & Discoverability (For Contributors)

This repository is engineered with semantic HTML, JSON-LD structured data, and progressive enhancement so that the live version ranks highly for keywords like:
- *mental arithmetic trainer*
- *online math practice*
- *adaptive learning platform*
- *visual math drills*
- *neuroplasticity exercise*

We also include a sitemap.xml, robots.txt, and Open Graph tags for social sharing. For contributors, all interactive components use ARIA labels, keyboard navigation, and high-contrast themes (WCAG AA compliance).

---

## 🚀 Getting Started (For Contributors)

> We assume you’re comfortable with modern JavaScript (ES2026) and have a standard dev environment. No special wizardry required.

### Prerequisites
- Node.js v22+ (LTS or newer)
- A modern browser (Chrome 120+, Firefox 125+, Safari 17+)
- A code editor with ESLint and Prettier configured

### Running the Local Development Server

1. **Acquire the source** – Use your favorite git client to fetch this repository to your local machine.
2. **Install dependencies** – Run the package manager of your choice (yarn, npm, pnpm) after that initial fetch.
3. **Launch the dev server** – The standard command for this project type will start a hot-reload environment at `localhost:3000`.
4. **Open your browser** – You’ll see the training interface immediately.

> **Note**: We deliberately avoid publishing package installation commands in this README. For exact commands, please consult the `package.json` scripts section of the repository.

---

## 🗂️ Project Architecture

The codebase is organized as a monorepo with three primary packages:

- **`/packages/trainer`** – The core arithmetic engine, state management, and difficulty scheduler.
- **`/packages/ui`** – All visual components, themes, and localized string files.
- **`/packages/api`** – Lightweight server routes for cohort comparison and anonymous statistics.

Each package is independently tested (unit + integration) and has its own lightweight CI pipeline. The reasoning engine is deliberately framework-agnostic—we use a custom web component layer for maximum portability.

---

## 🤝 Contribution Guidelines

We warmly welcome pull requests. Please follow these practices:

- **Commit conventions**: Use [Conventional Commits](https://www.conventionalcommits.org/) (feat, fix, refactor, docs, test).
- **Test first**: Every new training mode must come with at least 5 edge-case unit tests.
- **Accessibility matters**: Any new UI element must be navigable by keyboard alone and pass a Lighthouse accessibility score of 95+.
- **Localization**: Add new strings to the `/locales` folder; never hardcode English into components.

Community discussions happen in the [GitHub Discussions] tab. For bugs, use the issue tracker with our provided template.

---

## 📄 License

This project is open-source and distributed under the **MIT License**. You are free to use, modify, and distribute it for any purpose, commercial or private, provided you retain the original copyright notice.

See the full legal text in the [LICENSE](https://github.com/your-repo/numeric-forge/blob/main/LICENSE) file of this repository.

---

## ⚠️ Disclaimer

Numeric Forge is an educational tool designed to improve mental arithmetic skills. It does **not** diagnose, treat, or attempt to cure any cognitive disorder, including but not limited to dyscalculia, ADHD, or learning disabilities. 

While our adaptive algorithm is based on well-researched principles of spaced repetition and interleaving, results vary by individual. We make **no guarantees** of measurable improvement in standardized test scores, academic grades, or professional performance. 

In rare cases, users with photosensitive epilepsy should consult a physician before engaging with fast-flashing modes (like Flash Sprint or Digit Memory). Always take breaks—sustained practice over a 45-minute session may cause mental fatigue. Use at your own discretion.

For privacy: we collect **zero personal data**. Anonymous usage statistics are aggregated only to improve the adaptive engine. No cookies, no trackers, no fingerprints. Your brain is yours; we just help you train it.

---

## 🕒 Release Cadence & Roadmap (2026)

- **Q1 2026**: v1.0 Launch (current) – all 15 modes + analytics dashboard.
- **Q2 2026**: v1.5 – Multiplayer head-to-head over WebRTC (offline LAN play).
- **Q3 2026**: v2.0 – Community-published training packs (user-created problem sets).
- **Q4 2026**: v2.5 – Neural network-driven opponent that mimics your errors to craft targeted drills.

We follow semantic versioning strictly. Breaking changes are announced three minor versions in advance, with deprecation warnings baked into the UI.

---

## 💬 Final Word

Numbers are not abstract symbols. They are the *rhythm of the universe*—the tempo of interest rates, the beat of probability, the syncopation of engineering stress calculations. Numeric Forge doesn't make you a calculator; it makes you a composer of quantitative thought.

Start training today. Your mind—and your next dinner conversation about Bayesian inference—will thank you.

---

*© 2026 Numeric Forge Contributors. Built with patience, test-driven rigor, and an obsession for 60-second sprints.*