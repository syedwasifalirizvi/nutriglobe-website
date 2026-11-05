# NutriGlobe 2.0 — Official Website

Official public website for **NutriGlobe 2.0**, featuring precision botanical nutrition tracking, Mifflin-St Jeor metabolic science, global cultural cuisines, and privacy disclosures.

- **GitHub Repository:** [https://github.com/syedwasifalirizvi/nutriglobe-website](https://github.com/syedwasifalirizvi/nutriglobe-website)
- **Live GitHub Pages URL:** [https://syedwasifalirizvi.github.io/nutriglobe-website/](https://syedwasifalirizvi.github.io/nutriglobe-website/)
- **Privacy Policy URL:** [https://syedwasifalirizvi.github.io/nutriglobe-website/privacy.html](https://syedwasifalirizvi.github.io/nutriglobe-website/privacy.html)
- **Account & Data Deletion URL:** [https://syedwasifalirizvi.github.io/nutriglobe-website/delete-account.html](https://syedwasifalirizvi.github.io/nutriglobe-website/delete-account.html)
- **Developer Contact:** [wasifrizvi111@gmail.com](mailto:wasifrizvi111@gmail.com)

---

## Architecture & Design System

The website is designed as a direct extension of the **NutriGlobe 2.0 Android application** design system:
- **Botanical Palette:** Warm Ivory (`#F5F3EA`), Botanical Green (`#526B4B`), Deep Olive (`#394A35`), Champagne Gold (`#C6A66B`), Soft Sage (`#E9EEE3`).
- **Typography:** *Playfair Display* (Editorial headings) + *Plus Jakarta Sans* (Metrics, UI, and body).
- **Materiality:** Liquid Glass and Clay Glass styling with soft dimensional drop-shadows and frosted backdrops.
- **Pure Static Architecture:** Zero frameworks, zero build step, and zero third-party tracking scripts. Fast loading, accessible, and 100% compatible with GitHub Pages.

---

## File Structure

```
nutriglobe-website/
├── index.html                # Main homepage (Hero, Features, Cuisines, Tracking, Plus, Support)
├── privacy.html              # Dedicated Privacy Policy (Firebase, Firestore, SQLite, AdMob, Billing)
├── delete-account.html       # Self-service and email account deletion portal
├── README.md                 # Project documentation and deployment guide
└── assets/
    ├── css/
    │   └── style.css         # Botanical responsive design system
    ├── js/
    │   └── main.js           # Navigation, scroll animations, mobile drawer, email copy
    └── images/
        ├── logo.svg          # Official NutriGlobe vector logo
        ├── favicon.svg       # Browser tab icon
        ├── app-dashboard-hero.png
        ├── app-screen-diary.png
        └── foods/            # Real dish photography across regional cuisines
```

---

## How to Enable GitHub Pages

If GitHub Pages is not already active for this repository:
1. Navigate to the repository on GitHub: `https://github.com/syedwasifalirizvi/nutriglobe-website`.
2. Click **Settings** (top tab navigation).
3. In the left sidebar, click **Pages** (under the "Code and automation" section).
4. Under **Build and deployment > Source**, select **Deploy from a branch**.
5. Under **Branch**, choose **`main`** and folder **`/ (root)`**, then click **Save**.
6. Wait 1–2 minutes for the GitHub Actions deployment workflow to finish. The site will be live at:
   `https://syedwasifalirizvi.github.io/nutriglobe-website/`
