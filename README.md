# Call Plumber — Website

A modern, fully responsive, animated single-page website for a plumbing service business. Built as one self-contained `index.html` file with no build step and no external dependencies beyond Google Fonts and images.

---

## Quick start

1. Download `index.html`.
2. Double-click it to open in any browser — that's it. It works offline except for fonts and the demo images.
3. To put it online, upload `index.html` to any static host (Netlify, Vercel, GitHub Pages, Hostinger, or your existing hosting). No server or database needed.

---

## What's inside

| Section | What it does |
|---|---|
| Emergency bar | Red top strip advertising 24/7 availability |
| Sticky nav | Blur navigation with mobile hamburger menu |
| Hero | Emergency banner, stats, Call / WhatsApp / Book buttons |
| Services | All 12 services with custom icons and hover effects |
| Pricing | 9 clean pricing cards |
| Booking | Form that sends details straight to WhatsApp |
| About | Trust-building copy and feature highlights |
| Before / After | Draggable image comparison slider |
| Reviews | 6 sample customer testimonials |
| FAQ | Accordion of common questions |
| CTA strip | Final call-to-action |
| Footer | Links and contact details |
| Floating buttons | Always-visible Call and WhatsApp buttons |

---

## Before you go live — edit these

Open `index.html` in any text editor and update the following.

### 1. Phone & WhatsApp number

Find and replace the number everywhere it appears:

- **Phone (click-to-call):** search for `09033151098` in `tel:` links.
- **WhatsApp:** search for `919033151098`. The format is country code + number with **no `+`, spaces, or zeros** in front. `91` is India — change it if you are elsewhere.

Near the top of the `<script>` there is a single line you can edit for the booking form:

```js
const WA = "919033151098";
```

### 2. Service images

The photos currently load from Unsplash (placeholders). Replace the image URLs in the hero, About, and Before/After sections with your own real job photos for the best, most trustworthy result. Look for `src="https://images.unsplash.com/..."`.

### 3. Business details

Update the business name, testimonials, pricing, FAQs, and About text directly in the HTML. The services, prices, reviews, and FAQs are defined as simple lists in the `<script>` — easy to add to or change.

### 4. SEO

The `<title>`, `<meta name="description">`, and the LocalBusiness schema near the top of `<head>` are pre-filled for "plumber near me" / "emergency plumber". Add your real city/area names there to rank locally.

---

## How the booking form works

When a visitor fills in the form and taps **Book & Send on WhatsApp**, the site validates the fields, then opens WhatsApp with a ready-made message containing their name, phone, chosen service, date, and time. You receive it as a normal WhatsApp message and reply to confirm. No backend, no sign-up, nothing to maintain.

---

## Features

- Modern animated UI — smooth scroll, hover effects, fade-in-on-scroll
- Click-to-call and pre-filled WhatsApp buttons (floating + in every section)
- 24/7 emergency banner
- Fully mobile-responsive
- Fast — single file, minimal code, no frameworks
- Accessible — keyboard focus, reduced-motion support
- SEO-ready — meta tags and structured data included

---

## Tech

Plain HTML, CSS, and vanilla JavaScript. Fonts: Sora + Inter (Google Fonts). No frameworks, no build tools, no dependencies to install.

---

*Tip: keep a backup copy of `index.html` before making edits.*
