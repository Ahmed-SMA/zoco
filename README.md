# ZOCO Website

Minimal, bold, and designer-oriented custom apparel website for **Zoco**.  
Includes: animated hero with 3D elements, product sections, FAQ, testimonials, quotation form, lead capture, and Calendly integration.  

---

## 🚀 Getting Started

### 1. Clone or Download
```bash
git clone https://github.com/your-username/zoco-site.git
cd zoco-site
```
Or just upload the ZIP to GitHub.  

### 2. Open Locally
Simply open `index.html` in your browser.  
No build tools required (pure HTML, CSS, JS).  

---

## 📂 Project Structure

```
zoco-site/
│
├── index.html          # Main landing page
├── quote.html          # Quotation request page
│
├── assets/
│   ├── css/
│   │   └── styles.css  # All site styling
│   ├── js/
│   │   └── main.js     # Animations, carousel, lead capture, dialogs
│   ├── img/            # Logo + gallery images (replace with your own)
│   └── banner/         # Banner placeholder (replace with custom hero)
│
└── README.md
```

---

## 🎨 Customization

- **Colors / Gradients** → edit in `assets/css/styles.css` under the `:root` variables:
```css
--grad-primary: linear-gradient(90deg, #6a5af9, #ff57e1); /* purple → pink */
--grad-accent:  linear-gradient(90deg, #00e0ff, #29ffd2); /* cyan → aqua */
```

- **Images** → replace files in `assets/img/gallery-1.jpg … gallery-6.jpg` with your own **square product photos**.  

- **Banner** → swap `assets/banner/banner-placeholder.png` with a custom image (1920×700 recommended).  

- **Text** → edit directly in `index.html` and `quote.html`.  

---

## 🧩 Features

- **3D Hero Banner** with animated geometric shapes.  
- **Image Carousel** with 3D coverflow effect.  
- **FAQ & Testimonials** sections.  
- **Quotation Page** with form (article, org, sizes, deadline).  
- **Lead Capture** (name, email, phone, address → exportable as CSV).  
- **Location Dialog** (province → city selection).  
- **Calendly Integration** (chat with an expert).  
- Fully **mobile-optimized** and responsive.  

---

## ☁️ Deployment

### GitHub Pages
1. Push the repo to GitHub.  
2. Go to **Settings → Pages → Deploy from branch**.  
3. Choose `main` and root (`/`).  
4. Your site will be live at `https://your-username.github.io/zoco-site/`.  

### Netlify / Vercel
- Drag & drop the whole folder into Netlify (or import repo).  
- Done. No config required.  

---

## 📌 Notes

- Keep gallery images square (≥1200×1200) for best carousel look.  
- If you want form submissions emailed or stored in Google Sheets, you’ll need to connect a backend service (Formspree, Netlify Forms, Firebase, etc.).  
- All animations are vanilla JS & CSS, no frameworks.  

---

✍️ **Maintainer:** Syed Muhammad Ahmed (Zoco)
