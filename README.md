# 🛒 Amazon Homepage Clone

A pixel-perfect clone of **Amazon's homepage** built using only **HTML & CSS** — no JavaScript, no frameworks, no libraries. Just pure frontend fundamentals.

> ⭐ Star this repo if you found it helpful or learned something from it!

---

## 📸 Preview

<!-- Add your screenshot here after uploading it to the repo -->
> 📌 *Screenshot taken on a laptop screen at 1920×1080 resolution*

![Amazon Clone Preview](images)

---

## ⚠️ Important Note

> 🖥️ **This project is optimized for laptop/desktop screens only.**
> It is **not responsive** — on tablets and mobile devices the layout will break.
> Responsive design is planned as a future improvement.
>
> **Recommended viewing:** Full-screen browser on a laptop or desktop at 1280px+ width.

---

## 🔗 Live Demo

> 🚫 No live demo available at the moment due to the non-responsive nature of the project.
> A responsive version will be deployed once mobile support is added.

---

## ✨ Features

- ✅ **Top Navigation Bar** — Logo, delivery address with location icon, department dropdown, search bar with search button, language selector, account & lists, returns & orders, and cart icon
- ✅ **Secondary Navigation Bar** — All, Today's Deals, Prime Video, Buy Again, Registry, Customer Service, Gift Cards, Sell
- ✅ **Hero Section** — Full-width banner image
- ✅ **Product Cards Grid** — Multiple shop category cards (Gaming, Hair Products, Electronics, Office Chairs, Clothes)
- ✅ **Multi-Image Category Cards** — "Shop for your home essentials" cards with 4 sub-images (Cleaning Tools, Decoration, Jeans, Baby Clothes)
- ✅ **Horizontal Scroll Bar** — "Trending Internationally: Top Picks" with smooth horizontal scroll — no JavaScript
- ✅ **Footer — Level 1** — "Back to top" button
- ✅ **Footer — Level 2** — 4-column dark footer (Get to Know Us, Make Money with Us, Amazon Payment Products, Let Us Help You)
- ✅ **Footer — Level 3** — Amazon logo + Language / Currency / Country dropdowns
- ✅ **Footer — Level 4 (Black)** — Amazon subsidiaries grid (Amazon Music, AWS, IMDb, Audible, Zappos, Ring, etc.)
- ✅ **Last Footer** — Conditions of Use, Privacy Notice, Copyright line
- ✅ **Hover Effects** — White border hover on all navbar items, darken on search button, translateY lift on product scroll cards

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Page structure & semantic markup |
| **CSS3** | All styling, layout & hover effects |
| **Flexbox** | Primary layout system used throughout |
| **Font Awesome 7** | Icons (location pin, search, cart, bars) |
| **CSS Background Images** | Product cards & hero section images |

> 🚫 Zero JavaScript | 🚫 Zero Frameworks | 🚫 Zero CSS Libraries

---

## 📁 Project Structure

```
amazon-clone-html-css/
│
├── index.html              # Main HTML file
├── style.css               # All CSS styles
│
├── images/                 # All local images used
│   ├── amazon logo iii.jpg
│   ├── united-states.png
│   ├── h2.jpg              # Hero banner
│   ├── foot logo.png
│   ├── image 6.jpg         # Cleaning Tools
│   ├── image 8.jpg         # Jeans
│   ├── image 9.jpg         # Baby Clothes
│   ├── image 12.jpg        # Decoration
│   ├── image 13.jpg        # Clothes
│   ├── image 15-24.jpg     # Trending products scroll
│   ├── image 28.jpg        # Gaming
│   ├── image 29.jpg        # Electronics (Laptop)
│   ├── image 30.webp       # Hair Products
│   ├── c (2).jpg           # Office Chair
│   └── p.jpg               # Electronics (Monitor)
│
└── README.md               # You are here!
```

---

## 🚀 How To Run Locally

No installations needed. Literally just 3 steps:

**Step 1 — Clone the repository**
```bash
git clone https://github.com/loedex/amazon-UI-clone-html-css.git
```

**Step 2 — Navigate into the project folder**
```bash
cd amazon-clone-html-css
```

**Step 3 — Open in browser**
```bash
# Simply open index.html in your browser
# OR right-click index.html → Open with → Your Browser
# OR use VS Code Live Server extension
```

> 💡 **Tip:** Use the **Live Server** extension in VS Code for the best experience. Right-click `index.html` → *Open with Live Server*

---

## 🧠 What I Learned Building This

This project taught me things no tutorial ever explained clearly:

- **Flexbox in real layouts is messier than tutorials show** — aligning 7 different navbar items with different widths requires careful use of `justify-content: space-between` combined with individual `transform: translateX()` micro-adjustments
- **The hero-to-card overlap trick** — I used `margin-top: -290px` on the product section to float cards on top of the hero image, not `position: absolute` which broke the page flow entirely
- **CSS-only horizontal scroll** — `overflow-x: auto` on the parent + `flex: 0 0 auto` on each child card = smooth scrolling with zero JavaScript
- **`background-size: 100% 100%`** fills image cards perfectly without distortion, unlike `cover` which crops
- **`vw` units for sizing** — using viewport-width units (`4.5vw`, `43vw`) keeps proportions consistent across different laptop screen widths
- **Footer structure complexity** — Amazon's footer has 4 completely different sections stacked, each with its own layout logic

---

## 🔮 Future Improvements

- [ ] Make it fully responsive (mobile + tablet)
- [ ] Add JavaScript for working search functionality  
- [ ] Add a functional cart counter
- [ ] Add smooth scroll behavior
- [ ] Deploy on GitHub Pages once responsive

---

## ⚠️ Disclaimer

> This project is built **purely for educational and learning purposes**.
> It is a **UI clone only** — no backend, no real data, no commercial use.
> All Amazon logos, product images, and brand elements belong to **Amazon.com, Inc.**
> This is not affiliated with or endorsed by Amazon in any way.

---

## 👨‍💻 Author

**Husnain Ahmad**


---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---
