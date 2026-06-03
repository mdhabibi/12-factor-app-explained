# The 12-Factor App — Explained for Beginners

A free, interactive, beginner-friendly tutorial on the **[12-Factor App](https://12factor.net/)** methodology — the classic set of principles for building modern web apps and services that are easy to **deploy, scale, and maintain** in the cloud.

Everything lives in a single self-contained HTML file: no build step, no dependencies, no internet required. Just open it in a browser.

> **📖 Read it live:** https://YOUR_USERNAME.github.io/12-factor-app-explained/

---

## Why this exists

Most explanations of the 12 factors assume you already speak "cloud." This one doesn't. Every principle is taught from scratch with:

- 🧠 **Plain-English analogies** (shipping containers, food trucks, taxi ranks, dress rehearsals)
- 🐍 **Concrete Python examples** — a clear ❌ "don't" vs. ✅ "do" for each factor
- 📐 **11 hand-drawn SVG diagrams** that illustrate the tricky ideas
- 📌 **Notes, tips, and "why it matters"** callouts
- 🧩 A **glossary** of 40+ terms, so no jargon goes unexplained
- ☁️ **Modern context** — how Docker, Kubernetes, and CI/CD map onto each factor, plus the "15-factor" extensions

## What's covered

The full methodology, one factor at a time:

| # | Factor | The rule in one line |
|---|--------|----------------------|
| 1 | Codebase | One repo in version control, many deploys from it |
| 2 | Dependencies | Declare every dependency explicitly; isolate them |
| 3 | Config | Keep config (secrets, URLs) in environment variables |
| 4 | Backing services | Treat DBs, queues, caches as swappable attached resources |
| 5 | Build, release, run | Separate the three stages; releases are immutable |
| 6 | Processes | Run stateless, share-nothing processes |
| 7 | Port binding | Be self-contained; export the service on a port |
| 8 | Concurrency | Scale out by running more processes |
| 9 | Disposability | Start fast, shut down gracefully, survive being killed |
| 10 | Dev/prod parity | Keep all environments as similar as possible |
| 11 | Logs | Write events to stdout; let the platform handle them |
| 12 | Admin processes | Run one-off tasks in the same release and environment |

## How to use it

**Option 1 — Read online (easiest):**
Visit the GitHub Pages link above.

**Option 2 — Open locally:**
1. Download or clone this repo.
2. Double-click `index.html` — it opens in any browser.

```bash
git clone https://github.com/YOUR_USERNAME/12-factor-app-explained.git
cd 12-factor-app-explained
# then open index.html in your browser
```

No installation, no server, no internet connection needed.

## Who it's for

Anyone building an application that runs as a service — a web API, a website backend, a microservice. If you can write a small Python script, you can follow along. No prior Kubernetes or Docker knowledge required.

## Contributing

Spotted a typo, an unclear explanation, or have an idea for a better analogy? **Issues and pull requests are welcome.** This is a learning resource — improvements that make it clearer for beginners are especially appreciated.

## License

Released under the [MIT License](LICENSE) — free to use, share, adapt, and build upon.

## Credits & sources

- The methodology was created by **Adam Wiggins** and the engineers at **Heroku** (2011), published at **[12factor.net](https://12factor.net/)**.
- The "beyond 12-factor" extensions reference **Kevin Hoffman's** *Beyond the Twelve-Factor App*.
- Tutorial text, Python examples, and diagrams in this repo were written as an independent, beginner-friendly explanation of that methodology.

---

⭐ If this helped you understand the 12-Factor App, consider starring the repo so other learners can find it.
