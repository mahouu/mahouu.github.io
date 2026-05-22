# mauricio-miralles.github.io

Personal resume / CV site for **Mauricio Miralles** — Staff Backend Engineer.

🔗 **Live site:** [mahouu.github.io](https://mahouu.github.io)

---

## Stack

Plain HTML, CSS, and vanilla JS. No build step, no dependencies, no frameworks.  
Designed to be fast, readable, and easy to maintain.

- Dark / light mode (respects system preference, persists via `localStorage`)
- Mobile-friendly responsive layout
- Smooth scroll-reveal animations
- ATS-safe content (same text as the PDF CV)

## Deploy

This site is hosted on **GitHub Pages** from the `main` branch.

To update: edit `index.html`, commit, push. Done.

```bash
git clone https://github.com/mahouu/mahouu.github.io
cd mahouu.github.io
# edit index.html
git add . && git commit -m "update cv" && git push
```

## Local preview

```bash
# Python 3
python -m http.server 8000
# then open http://localhost:8000
```

---

*Built with care. No frameworks were harmed.*
