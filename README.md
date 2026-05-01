# Kommina Revanth Chowdary — Business Portfolio

A modern, fully responsive **business portfolio website** for Kommina Revanth Chowdary — Business & Technology Consultant.

## 🚀 Live Preview

Open `index.html` in any browser or serve it via a static file server:

```bash
# Python
python -m http.server 8080

# Node
npx serve .
```

## 📁 Structure

```
├── index.html   # Main page (all sections)
├── style.css    # Styling (CSS custom properties, responsive)
├── script.js    # Interactivity (scroll effects, animations, form)
└── README.md
```

## 🗂 Sections

| Section | Description |
|---|---|
| **Hero** | Headline, CTA buttons, animated statistics |
| **About** | Bio, highlights, experience badge |
| **Skills** | Animated progress bars across 4 domains |
| **Services** | 6 service cards with feature lists |
| **Portfolio** | Filterable project grid (6 projects) |
| **Testimonials** | 3 client reviews on dark background |
| **Contact** | Contact details + enquiry form |
| **Footer** | Links, social icons, copyright |

## ✨ Features

- **Responsive** — mobile-first layout, hamburger nav on small screens
- **Smooth animations** — fade-up entrance effects via IntersectionObserver
- **Animated skill bars** — triggered when scrolled into view
- **Animated counters** — hero statistics count up on load
- **Portfolio filter** — category-based project filtering
- **Contact form** — client-side validation with a success confirmation
- **Scroll-to-top** button appears after scrolling 400 px
- **Active nav links** — auto-highlights current section

## 🎨 Customisation

All colours and spacing are defined as CSS custom properties in `:root` inside `style.css`. Replace placeholder contact details, project descriptions, and client testimonials in `index.html` with your real information.

## 📄 License

MIT — see [LICENSE](LICENSE).
