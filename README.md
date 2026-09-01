# John Anderson — Full-Stack Developer Portfolio

A modern, responsive portfolio website built for a senior full-stack developer showcasing expertise, experience, and professional services.

## 🎨 Color Palette

| Role | Color | Hex |
|------|-------|-----|
| Background / Dark Navy | Primary Background | `#0F172A` |
| Primary / Neon Cyan | Accent Color | `#22D3EE` |
| Secondary / Cool Gray | Text & Borders | `#64748B` |
| Accent / Light Gray | Text & Highlights | `#F4F4F4` |

## ✨ Key Features

- **Fully Responsive** — Optimized for all device sizes (desktop, tablet, mobile)
- **Modern Design** — Clean, professional layout with animated background elements
- **Oval Portrait Frames** — Unique visual style for profile images
- **Interactive Elements** — Hover effects, scroll animations, and smooth transitions
- **Contact Form** — Enhanced form with service selection and budget options
- **Animated Stats** — Counter animations that trigger on scroll
- **Mobile-First Navigation** — Hamburger menu for mobile devices
- **Accessibility Ready** — Skip links, ARIA labels, and keyboard navigation

## 🛠️ Technologies Used

- HTML5
- CSS3 (Custom properties, Flexbox, Grid, Animations)
- Vanilla JavaScript
- Google Fonts (Playfair Display, Inter, JetBrains Mono)
- SVG Icons

## 📁 Project Structure

```
portfolio/
├── index.html          # Main portfolio page (single-file)
├── assets/             # Image assets
│   ├── profile-hero.jpg
│   └── John_Anderson_CV.pdf
└── README.md           # This file
```

## 🚀 Getting Started

1. **Clone or download** this repository
2. **Replace images** in the `assets/` folder with your own:
   - `profile-hero.jpg` — Hero section portrait (400×533px recommended)
   - `profile-about.jpg` — About section photo (400×500px recommended)
3. **Update personal information** in `index.html`:
   - Name, title, bio
   - Contact details (phone, email, location)
   - Social media links
   - Experience timeline
4. **Add your CV** as `assets/John_Anderson_CV.pdf`
5. **Open `index.html`** in your browser to preview

## 📱 Responsive Breakpoints

| Breakpoint | Devices |
|------------|---------|
| > 1024px | Desktop |
| 860px - 1024px | Tablet Landscape |
| 768px - 860px | Tablet Portrait |
| 480px - 768px | Mobile Landscape |
| < 480px | Mobile Portrait |

## 🔧 Customization Tips

- **Change Colors**: Update the `:root` variables in the `<style>` section
- **Add New Expertise Cards**: Copy an existing `.exp-card` block and update content
- **Modify Tech Stack**: Edit the `.hero-tech-stack` spans
- **Update Timeline**: Add new `.tl-item` blocks in the journey section
- **Add Services**: Extend the `<select id="service">` options

## 📝 License

This project is available for commercial use.

---

**Design & Develop By** KimTech
