ComicVerse Hub — Dynamic Online Comic Store

A high-fidelity, fully client-side comic store simulation built with HTML5, CSS3, and modern JavaScript (ES6+).
Deployed as a static, interactive, portfolio-grade front-end project.

📌 Overview

ComicVerse Hub replicates the feel of a modern comic-book e-commerce platform (in the style of Marvel, DC, and other major publishers) without any backend systems.
All content, catalog data, and interactions run purely on the client through JavaScript, JSON, and browser storage.

This project demonstrates:

Professional-grade UI design

Fully responsive layouts

Client-side filtering, sorting, and cart logic

Dynamic routing via URL parameters

Deployed, production-ready static hosting

📸 Feature Summary
1. Homepage (index.html)

Full-width hero carousel

Sections for New Releases, Popular Series, Publisher Spotlights

Sticky, responsive navbar

High-impact visual design

2. Browse All Comics (browse.html)

Grid layout for the full catalog

Client-side filtering (publisher, genre, character)

Sorting (price, title, release date)

Each comic card links to a dynamic detail page

3. Comic Detail Page (comic-detail.html)

Dynamic content population using URL parameters

Large cover image with zoom interaction

Detailed metadata: synopsis, creators, price, publisher

Add-to-cart powered by JavaScript

4. Shopping Cart (cart.html)

Fully dynamic cart rendered via JavaScript

Quantity updates and item removal

Persistent cart using localStorage

Auto-updating total price

Checkout flow with simulated confirmation

🛠 Technology Stack

HTML5 for structure

CSS3 for responsive, polished UI

Vanilla JavaScript (ES6+) for all interactions

localStorage for persistent cart

Optional CDN-based lightweight libraries for:

Carousel

Icons

No backend. No frameworks. No build tools.

📦 Installation & Setup
1. Clone the repo
git clone https://github.com/ojas1805/comicverse.git
cd comicverse

2. Run locally

No build step required.
Just open index.html in any browser.

3. Deploy

Recommended: GitHub Pages

Push repo

Enable Pages under repo → Settings → Pages

Choose branch: main → /root

Save → Deployment goes live

All assets use relative paths to ensure full compatibility with static hosting.

🧪 Testing Guidance

Validate responsiveness on mobile, tablet, and desktop

Refresh browser frequently to confirm localStorage persistence

Test edge cases (empty cart, sorting resets, direct URL detail page access)

Validate image paths and project structure after deployment

📘 Future Enhancements (Optional)

Add wishlist functionality

Add user profile mockups

Implement search-as-you-type

Lazy-loading images


👥 Contribution Breakdown


Himanshu Verma — Front-End Architecture & UI Engineering (35%)

Built core layout structure across all pages

Implemented responsive grid system and navigation framework

Developed homepage hero carousel with custom JavaScript

Established overall visual theme, typography, and styling guidelines

Ensured cross-device responsiveness and mobile-first UX

Prateek Singh — Catalog Engine & Dynamic Data Systems (30%)

Authored comics.js / JSON data model

Implemented browse-page filtering & sorting logic

Built dynamic rendering of catalog cards

Engineered detail-page population based on URL parameters

Ensured zero-backend deployment compatibility

Ojas Singh — Cart Logic & Persistence Layer (25%)

Implemented cart system using localStorage

Built add/remove/update quantity functionalities

Developed real-time price calculation logic

Designed cart UI interactions and state-management workflow

Performed integration testing between detail → cart → persistence

Abhishek Dhar — Peripheral Tasks & Minor Contributions (10%)

Basic CSS adjustments and minor styling fixes

Assisted with image optimization and asset structuring

Added small content updates and validated links

Performed light QA on final pages
