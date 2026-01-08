# Shopify Store Setup and Google Analytics 4 (GA4) Integration

This repository provides the theme configuration and code changes used for setting up a Shopify e-commerce store and integrating Google Analytics 4 (GA4) tracking. The project demonstrates a straightforward Shopify store configuration, basic theme customization, foundational e-commerce content organization, and GA4 analytics integration for educational and practice purposes.

---

## Project Overview

Covered topics and tasks:
- Shopify store setup and admin panel walkthrough
- Customization of theme for both desktop and mobile responsiveness
- Adding products and organizing them via collections
- Setting up and adjusting the navigation menu
- Installing and exploring Shopify apps (e.g. Shopify Inbox)
- Managing blog posts and content
- Integrating Google Analytics 4 by editing theme files

The primary code changes are in the `theme.liquid` file, where the GA4 Global Site Tag (`gtag.js`) is placed inside the `<head>` section. This enables analytics tracking on all storefront pages.

---

## Google Analytics Integration

- **GA4 Global Site Tag** is inserted into the `<head>` of `theme.liquid`.
- Enables tracking of all user activity, traffic sources, and page interactions across the storefront.
- Data verification should be performed using GA4 real-time reports.

---

## Technologies Used

- Shopify (Admin dashboard and Online Store)
- Liquid Templating Language
- HTML & CSS
- Google Analytics 4 (GA4)

---

## Repository Structure

```
layout/
└── theme.liquid    # Primary theme file, including GA4 script
README.md
```

---

## Usage

1. Upload or edit the `theme.liquid` file in your Shopify store:
   - Shopify Admin → Online Store → Themes → Edit code
2. Replace or merge with your existing `theme.liquid` as needed.
3. Make sure the inserted GA4 tracking code contains your actual **Measurement ID**.
4. Deploy changes, then verify tracking via Google Analytics 4 real-time reports.

---

## Screenshots



---

## Disclaimer

This repository is intended only for learning, demonstration, and personal use.  
It is not designed as a production-grade commercial Shopify store template.
