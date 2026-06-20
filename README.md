# 📓 Keith's Notebook

> Technical write-ups and mental models — notes on systems, thinking, and building.

This is the source code for [keithkeekw.github.io](https://keithkeekw.github.io), my public notebook where I write about distributed systems, debugging methodologies, and the mental models that shape how we think about software.

It's built with [Hugo](https://gohugo.io/) and a custom theme called `notebook` (real creative, I know).

## ✍️ What you'll find here

There are a handful of posts so far, walking the line between "actually useful" and "things I wish I'd known six months ago":

- Distributed systems through the lens of mental models
- Systematic approaches to debugging complex systems
- Caching strategies from browser to distributed cache
- Why I publish raw technical notes (and why you might want to too)

No hot takes. No listicles. Just notes I'd want to find if I were searching for them.

## 🛠️ Tech stack

| Layer | Choice |
|-------|--------|
| Static site generator | Hugo v0.163.3 |
| Theme | Custom `notebook` (hand-rolled, no training wheels) |
| Search | Fuse.js v7 (client-side, because who needs a server?) |
| Fonts | DM Sans + JetBrains Mono |
| Deployment | GitHub Pages (`gh-pages` branch, because rituals matter) |
| OG image | A lovingly crafted `/images/og.png` |

## 🚀 Running locally

```bash
# dev server with live reload
hugo server

# include draft posts
hugo server -D

# production build
hugo
```

The static output lands in `public/`. Point any HTTP server at it and you're in business.

## 📁 Structure

```
├── content/
│   └── posts/          # Where the writing happens
├── themes/
│   └── notebook/       # Custom theme (layouts, assets, CSS, JS)
├── layouts/            # Site-level overrides (search index)
├── hugo.toml           # Config — site title, social links, etc.
└── README.md           # You are here. Hello.
```

New posts are created with `draft = true` by default (Hugo's archetype does this). Run `hugo server -D` to preview them before publishing.

## 🤝 Contributing

This is a personal notebook, so contributions aren't really the point. But if you spot a typo or a technical error, feel free to open an issue or a PR. I promise I won't be mad — I'll probably be grateful.

## 📬 Find me elsewhere

- [GitHub](https://github.com/keithkeekw)
- [LinkedIn](https://linkedin.com/in/keithkeekw)
- [X / Twitter](https://x.com/keithkeekw)

Or subscribe to the [RSS feed](/index.xml) if you're old school.

---

*Last updated: June 2026. Built with Hugo, fueled by coffee.*
