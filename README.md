# VIBEOCRACY

**Intelligence Over Hierarchy**

Open-source landing site for [Vibeocracy](https://vibeocracy.org) — a 2028 presidential platform for the post-hierarchy era: liquid democracy, collective intelligence, and the end of the two-party pyramid.

**Live site:** [vibeocracy.org](https://vibeocracy.org)  
**Campaign:** [PRES2028.com](https://PRES2028.com)

---

## About

Vibeocracy is a single-page, scroll-driven experience that walks visitors through five chapters:

1. **Intro** — The vision and tagline
2. **Hierarchy** — Why legacy top-down systems are failing
3. **Spiral** — Spiral Dynamics and the path forward
4. **Vibe** — Collective intelligence and decentralized sense-making
5. **Manifesto** — Call to action for the exponential chapter ahead

---

## Tech stack

No build step. Pure static HTML, CSS, and JavaScript.

| Layer | Tools |
|-------|-------|
| Styling | [Tailwind CSS](https://tailwindcss.com) (CDN) |
| Typography | Space Grotesk, Inter (Google Fonts) |
| 3D background | [Three.js](https://threejs.org) |
| Animation | [GSAP](https://greensock.com/gsap/) + ScrollTrigger |
| Smooth scroll | [Lenis](https://lenis.darkroom.engineering/) |

---

## Run locally

**Option A — open directly**

```bash
# Clone the repo, then open index.html in your browser
```

**Option B — local server (recommended)**

Some features work better with a local server:

```bash
# Python
python -m http.server 8080

# Node (npx)
npx serve .

# Then visit http://localhost:8080
```

---

## Project structure

```
vibeocracy/
├── index.html          # Entire site (HTML, CSS, JS)
├── assets/
│   ├── favicon.svg
│   ├── favicon-32.png
│   ├── favicon-512.png
│   ├── apple-touch-icon.png
│   ├── og-image.png    # Social share image (1200×630)
│   └── site.webmanifest
├── README.md
├── LICENSE
└── CONTRIBUTING.md
```

---

## Contributing

PRs are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

1. Fork the repo
2. Create a branch (`git checkout -b feature/your-change`)
3. Commit your changes
4. Open a Pull Request

---

## License

[MIT](LICENSE) — see file for details.
