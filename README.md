# 🎮 Gameon Galaxy — Gaming Tournament & eSports Website

A dark-themed, high-energy gaming website built with pure HTML, CSS, and JavaScript. Features a live match section, latest game releases, featured games with hover overlay, a gaming gear shop, blog, and newsletter — deployed live on Vercel.

## 🌐 Live Demo

🔗 **[gameon-galaxy-website.vercel.app](https://gameon-galaxy-website.vercel.app)**

---

## ✨ Features

- 📢 **Top Announcement Bar** — Black Friday countdown banner ("10 Days") with social links
- 🏠 **Hero Section** — Full-background hero with "Create Manage Matches" headline and gaming character banner
- 🏢 **Brand Strip** — 6 scrollable gaming brand/partner logos
- 🆕 **Latest Game Releases** — 3 horizontally scrollable game cards with genre badge, title & entry fee
- 🎥 **Live Match Section** — Video banner with play button, upcoming match time display & team player cards
- 🕹️ **Featured Games** — 4 tall game cards with hover overlay showing title, platform info & icon
- 🛍️ **Gaming Shop** — 4 scrollable product cards (T-Shirt, Xbox Controller, GPU, VR Box) with Add to Cart
- 📰 **Blog / News** — 3 blog cards with author, date & "Read More" link
- 📧 **Newsletter** — Email subscription form with skew/parallelogram styled input
- 🔍 **Search Box** — Toggle-able full-width search overlay in header
- 🛒 **Cart Button** — Header cart icon with item badge count
- 📱 **Responsive Design** — Mobile hamburger menu, horizontal scroll for game/shop cards
- 🔝 **Back to Top** — Smooth scroll anchor

---

## 🎲 Latest Game Releases

| Game | Genre | Entry Fee |
|------|-------|-----------|
| White Walker Daily | Zombie | Free |
| Hunter Killer II | Adventure | $25.00 |
| Cyberpunk Daily | Action | $25.00 |

---

## 🕹️ Featured Games

| Game | Platform |
|------|----------|
| Just for Gamers | PlayStation 5, Xbox |
| Need for Speed | PlayStation 5, Xbox |
| Egypt Hunting Gamers | PlayStation 5, Xbox |
| Just for Gamers (Alt) | PlayStation 5, Xbox |

---

## 🛒 Gaming Shop Products

| Product | Category | Price |
|---------|----------|-------|
| Women Black T-Shirt | T-Shirt | $29.00 |
| Gears 5 Xbox Controller | Xbox | $29.00 |
| GeForce RTX 2070 | Graphics Card | $29.00 |
| Virtual Reality Smiled | VR Box | $29.00 |

---

## 📰 Blog Posts

| Title | Date |
|-------|------|
| Shooter Action Video | September 19, 2022 |
| The Walking Dead | September 19, 2022 |
| Defense Of The Ancients | September 19, 2022 |

---

## 🗂️ Project Structure

```
Gameon-Galaxy-Website/
│
├── Assets/                          # All images, icons & SVGs
│   ├── hero-bg.jpg                  # Hero section full background
│   ├── hero-banner.png              # Hero gaming character image
│   ├── brand-1.png → brand-6.png   # Partner/brand logos
│   ├── latest-game-1.jpg           # White Walker Daily
│   ├── latest-game-2.jpg           # Hunter Killer II
│   ├── latest-game-3.jpg           # Cyberpunk Daily
│   ├── live-match-banner.jpg       # Live match video thumbnail
│   ├── live-match-player-1.png     # Tokyo Eagle team card
│   ├── live-match-player-2.png     # New York Hunter7 team card
│   ├── featured-game-1.jpg         # Just for Gamers
│   ├── featured-game-2.jpg         # Need for Speed
│   ├── featured-game-3.jpg         # Egypt Hunting Gamers
│   ├── featured-game-4.jpg         # Just for Gamers (alt)
│   ├── featured-game-icon.png      # Overlay icon on featured cards
│   ├── shop-bg.jpg                 # Shop section background
│   ├── shop-img-1.jpg              # Women Black T-Shirt
│   ├── shop-img-2.jpg              # Gears 5 Xbox Controller
│   ├── shop-img-3.jpg              # GeForce RTX 2070
│   ├── shop-img-4.jpg              # Virtual Reality Smiled
│   ├── blog-1.jpg                  # Shooter Action Video
│   ├── blog-2.jpg                  # The Walking Dead
│   ├── blog-3.jpg                  # Defense of the Ancients
│   └── favicon.svg                 # Browser tab icon
│
├── index.html                       # Main HTML — full single-page site (1165 lines)
├── style.css                        # Dark gaming theme, skew effects, animations
└── script.js                        # Navbar toggle, search toggle, back-to-top
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **HTML5** | Semantic structure & accessibility |
| **CSS3** | Dark theme, skew/parallelogram effects, custom CSS variables, Grid & Flexbox |
| **JavaScript (Vanilla)** | Navbar toggle, search box toggle, back-to-top button |
| **Google Fonts** | Oxanium (headings/brand) + Poppins (body) |
| **Ionicons 5** | All icons — cart, search, play, notifications, location etc. |
| **Vercel** | Deployment & hosting |

---

## 📄 Sections Overview

| Section | Description |
|---------|-------------|
| **Header Top** | Black Friday countdown + Social links (Facebook, Twitter, Pinterest, LinkedIn) |
| **Header Bottom** | Logo, nav links (Home, Live, Features, Shop, Blog, Contact), Cart, Search, Hamburger |
| **Search Overlay** | Full-width togglable search bar |
| **Hero** | "Create Manage Matches" headline, gaming character, Read More CTA |
| **Brand Strip** | 6 scrollable gaming partner logos |
| **Latest Releases** | 3 game cards with genre badge & entry fee |
| **Live Match** | Video banner, upcoming match time, vs. team player display |
| **Featured Games** | 4 tall cards with hover overlay (title + platform info) |
| **Shop** | 4 gaming gear product cards with Add to Cart button |
| **Blog** | 3 gaming news articles with date & Read More |
| **Newsletter** | Email subscribe form with skew-styled input |
| **Footer** | Brand text, address, phone, email, quick links, social icons |

---

## 🎨 Design Highlights

- **Skew / Parallelogram UI** — Nav links, badges, and buttons all use a slanted `skewBg` class for a sharp gaming aesthetic
- **Dark Background Hero** — Full-bleed background image with glowing text and accent colors
- **Hover Overlay Cards** — Featured game cards reveal a full dark overlay with icon + details on hover
- **Neon Accent Colors** — Highlight spans and badges use a vivid accent color to pop against dark backgrounds
- **Scroll-snap Carousels** — Latest games, featured games, and shop sections use horizontal scrollbar with custom snap

---

## 🚀 Getting Started

### Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/Daniish-Qureshi/Gameon-Galaxy-Website.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd Gameon-Galaxy-Website
   ```

3. **Open in browser**
   ```
   Open index.html directly in your browser
   — use Live Server (VS Code extension) for best experience
   ```

> ✅ Zero dependencies. No npm install required. Pure HTML/CSS/JS!

---

## 📱 Responsive Design

| Screen | Behavior |
|--------|----------|
| **Mobile** | Hamburger nav, horizontal-scroll game/shop rows, stacked blog cards |
| **Tablet** | 2-column blog grid, wider hero layout |
| **Desktop** | Full dark hero, multi-column featured grid, all hover effects active |

---

## 👨‍💻 Author

**Danish Qureshi**  
BCA Final Year Student | Full Stack Developer  
📍 Dadri, Uttar Pradesh, India  
🔗 [GitHub — @Daniish-Qureshi](https://github.com/Daniish-Qureshi)  
🌐 [Portfolio](https://danish-qureshi-6ew5.vercel.app)

---

## 📄 License

This project is built for **educational & portfolio purposes**.  
Free to use as reference or inspiration.

---

⭐ If you liked this project, give it a **star** on GitHub!
