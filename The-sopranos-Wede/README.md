# 🍷 The Sopranos Restaurant & Lounge

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Status](https://img.shields.io/badge/Status-Completed-success)]()

Welcome to the repository for **The Sopranos Restaurant & Lounge** web platform. This responsive multi-page website showcases the venue's dining, craft cocktails, VIP nightlife events, operating details, and a table reservation form.

---

## 📌 Project Overview

Located in Northern Roodepoort, Gauteng, South Africa, **The Sopranos Restaurant & Lounge** offers a premium culinary and nightlife experience.

### Key Pages & Features
* 🏠 **Home (`index.html`):** Hero section, featured special, live "Open now / Closed" badge.
* 📖 **About Us (`about.html`):** Background, culinary vision, design approach and references.
* 🍽️ **Menu (`menu.html`):** Burgers, wings, cocktails and event specials with a category filter.
* 🍸 **Services (`services.html`):** Fine dining, cocktail bar and VIP lounge event hosting.
* 📅 **Reservations (`enquiry.html`):** Booking form with date, time, phone and party-size validation.
* 📞 **Contact Us (`contact.html`):** Opening hours, address, validated contact form and Google Map.

### JavaScript Features (`js/main.js`)
* Reservation and contact form validation with on-page confirmation messages
* Menu category filter
* Open now / Closed badge in South African time
* Back-to-top button, auto-updating footer year, mobile menu auto-close

---

## 🛠️ Built With

* **HTML5:** Semantic structure for accessibility and SEO.
* **CSS3:** Responsive layout with Flexbox/Grid and custom properties (`css/style.css`).
* **JavaScript (vanilla):** No libraries or frameworks (`js/main.js`).

---

## 📂 Repository Structure

```text
.
├── index.html                 # Home page
├── about.html                 # About page
├── menu.html                  # Food, drinks & specials
├── services.html              # Services & VIP events
├── enquiry.html               # Reservation form
├── contact.html               # Contact details, form & map
├── CHANGELOG.md               # Version history
├── SITEMAP.md                 # Page hierarchy
├── css/
│   └── style.css              # Main stylesheet
├── js/
│   └── main.js                # Interactivity & form validation
└── images/                    # burger.jpg.jpg, cocktail.jpg.jpeg,
                               # developer.jpg.jpeg, event&specials.jpg,
                               # gourmet dish.jpg, Signature cocktails.jpg,
                               # vipevents.jpg, wings.jpg, wings2.jpg, ...
```

---

## 🚀 Deployment (GitHub Pages)

1. Push the project to GitHub with `index.html` in the **root** of the repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose branch `main` and folder `/ (root)`, then **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/<repository-name>/`.

> **Important:** GitHub Pages is **case-sensitive**. `images/Signature cocktails.jpg` and `images/signature cocktails.jpg` are different files. File names in the HTML must match the files in the repository exactly.

### Custom domain (optional)

1. Buy a domain (for example `thesopranos.co.za`) from a registrar.
2. In **Settings → Pages → Custom domain**, enter the domain and save. GitHub creates a `CNAME` file in the repository.
3. At the registrar's DNS settings, add these records:

| Type | Name | Value |
|---|---|---|
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| CNAME | `www` | `<your-username>.github.io` |

4. Wait for DNS to update (from a few minutes up to 24 hours), then tick **Enforce HTTPS**.

GitHub's current DNS values are listed at https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site, so check them there before changing your DNS.
