# 📚 Biblioverse — Your Personal Literary Universe

> Discover, track, and celebrate every book in your reading journey.

---

## What is Biblioverse?

Biblioverse is an open-source personal book management app that transforms the way you experience reading. Whether you're a casual reader or a devoted bibliophile, Biblioverse gives you a beautiful, organized space to catalog your library, track your progress, discover new titles, and reflect on the stories that have shaped you.

This project is **community-driven** — built in the open, by readers, for readers. Everyone is welcome to contribute, no matter your experience level.

---

## 🗺️ Project Philosophy & Tech Roadmap

Biblioverse is intentionally starting simple. We believe great software grows organically, and we want contributors at every skill level to feel at home.

### Phase 1 — Foundation (Current) 🟢
> Plain HTML, CSS, and vanilla JavaScript. No build tools, no dependencies. Just open `index.html` in your browser and go.

```
biblioverse/
├── index.html       # App shell & markup
├── style.css        # All styling
└── app.js           # Core logic (search, shelf management, local storage)
```

**Anyone can contribute here** — if you know basic HTML/CSS/JS, you're ready.

### Phase 2 — Structure (Upcoming) 🔵
> Introducing modules, a component system, and a lightweight bundler as the codebase grows.

- ES Modules for cleaner code organization
- A simple JSON-based local data layer
- Sass/PostCSS for scalable styling
- Vite as a zero-config bundler

### Phase 3 — Scale (Future) 🟣
> A full-stack architecture for user accounts, sync, and social features.

- React + TypeScript frontend
- Node.js / Next.js backend
- PostgreSQL with Prisma ORM
- Auth via NextAuth.js
- Deployed on Vercel

> ⚠️ We won't jump to Phase 3 until Phase 1 is solid and the community has shaped what Biblioverse should be. No premature complexity.

---

## ✨ Features

- **My Library** — Organize books into shelves: *Currently Reading*, *Want to Read*, *Finished*, and custom collections.
- **Reading Tracker** — Log reading sessions, track page progress, and visualize your reading streaks.
- **Book Discovery** — Get personalized recommendations based on your reading history and favorite genres.
- **Reading Stats** — Explore insights like books read per month, average rating, most-read genres, and annual reading goals.
- **Reviews & Notes** — Write personal reviews, highlight favorite quotes, and jot annotations tied to specific books.
- **Author Universe** — Follow authors, explore their full catalogs, and get notified of new releases.
- **Reading Challenges** — Join themed challenges (e.g., *12 Books in 12 Months*, *Around the World in 80 Books*) or create your own.
- **Social Shelves** — Share reading lists with friends, swap recommendations, and see what your circle is reading.

---

## 🚀 Getting Started

No installs. No setup. Seriously.

```bash
# Clone the repository
git clone https://github.com/vanshika114/biblioverse.git
cd biblioverse

# Open in your browser
open index.html
```

That's it. Biblioverse runs entirely in the browser right now. Data is saved to `localStorage` so your library persists between sessions.

---

## 🤝 Contributing

We'd love your help! Biblioverse welcomes contributors of all backgrounds and experience levels.

### First time contributing to open source?

Start here — these issues are hand-picked for newcomers:

👉 **[Good First Issues](https://github.com/your-org/biblioverse/issues?q=label%3A%22good+first+issue%22)**

No issue is too small. Fixing a typo, improving a color contrast ratio, or adding a missing `alt` attribute all count.

### How to contribute

1. **Fork** the repository
2. **Create a branch** for your change: `git checkout -b fix/your-change-name`
3. **Make your changes** — keep them focused and small
4. **Test** by opening `index.html` in your browser
5. **Commit** with a clear message: `git commit -m "fix: correct shelf count display"`
6. **Push** your branch: `git push origin fix/your-change-name`
7. **Open a Pull Request** — describe what you changed and why

### Contribution guidelines

- Be kind and constructive — we follow the [Contributor Covenant](https://www.contributor-covenant.org/)
- One change per PR where possible
- For big ideas, **open an issue first** to discuss before building
- No change is too small to submit

See [CONTRIBUTING.md](./CONTRIBUTING.md) for the full guide.

---

## 🐛 Reporting Bugs

Found something broken? [Open an issue](https://github.com/your-org/biblioverse/issues/new?template=bug_report.md) and include:

- What you expected to happen
- What actually happened
- Your browser and OS
- Steps to reproduce

---

## 📄 License

Biblioverse is released under the [MIT License](./LICENSE) — free to use, modify, and distribute.

---

## Acknowledgements

- [Google Books API](https://developers.google.com/books) for book metadata
- [Open Library](https://openlibrary.org/) for open-access book data
- Every contributor who has opened an issue, submitted a PR, or just shared the project ❤️

---

## 👥 Contributors

<!-- ALL-CONTRIBUTORS-LIST:START -->
<!-- This section is auto-updated. See .all-contributorsrc -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

Want to see your name here? [Start contributing!](#-contributing)

---

*Happy reading — may your TBR pile never stop growing.* 📖
