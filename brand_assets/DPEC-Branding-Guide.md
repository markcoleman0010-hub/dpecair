# D PEC Air Conditioning Inc. — Branding & Website Guide

> **Purpose:** This document defines the visual identity, tone, and content structure for building the D PEC Air Conditioning Inc. website. Use this as the single source of truth when generating all pages, components, and copy.

---

## 1. Company Overview

- **Legal Name:** D PEC Air Conditioning Inc.
- **License #:** CAC1822218
- **Industry:** HVAC — Heating, Ventilation, Air Conditioning & Refrigeration
- **Service Area:** Fort Myers and surrounding Southwest Florida
- **Address:** 337 Belliard Rd, Fort Myers, FL 33905
- **Phone:** (239) 785-6399
- **Email:** luispec85@gmail.com
- **Business Type:** Licensed & insured HVAC contractor
- **Core Services:** AC installation, repair, maintenance plans, refrigeration services, duct cleaning, indoor air quality

---

## 2. Logo & Icon

### Description
The logo is a **split sun/snowflake icon** paired with the company name in bold white text:
- **Top half:** A warm golden-yellow sun with radiating petals/rays and an orange outline, representing heating and warmth.
- **Transition zone:** Flowing horizontal wave lines in orange, yellow, and blue bridging the sun and snowflake — symbolizing the transition between heating and cooling.
- **Bottom half:** A blue crystalline snowflake, representing cooling and air conditioning.

### Logo Usage Rules
- Always display the sun/snowflake icon to the **left** of the company name.
- Maintain clear space around the logo equal to the height of the snowflake element.
- Do **not** stretch, rotate, recolor, or crop the logo.
- On dark backgrounds, use the logo as-is (white text). On white/light backgrounds, switch company name text to dark navy or charcoal.

### Logo File Reference
- The logo image file is: `dpec-logo.png` (provide as an asset to the build tool).

---

## 3. Color Palette

| Role | Color Name | Hex | Usage |
|------|-----------|-----|-------|
| **Primary – Warm** | Sun Gold | `#F5B800` | CTAs, highlights, accents representing heating |
| **Primary – Cool** | Ice Blue | `#2E86DE` | Headers, links, accents representing cooling |
| **Accent – Warm** | Flame Orange | `#E8700A` | Hover states, secondary buttons, sun outline |
| **Accent – Cool** | Deep Blue | `#1A5276` | Footer, dark sections, nav background |
| **Neutral – Dark** | Charcoal | `#2C3E50` | Body text, headings on light backgrounds |
| **Neutral – Light** | Soft Gray | `#F4F6F7` | Page backgrounds, card backgrounds |
| **White** | White | `#FFFFFF` | Text on dark/colored backgrounds, card surfaces |

### Gradient
The brand's signature gradient flows from **Sun Gold (#F5B800)** at the top-left to **Deep Blue (#1A5276)** at the bottom-right. Use this gradient for:
- Hero section backgrounds (with a slight overlay for text readability)
- Section dividers
- Accent bars or decorative elements

```css
/* Brand Gradient */
background: linear-gradient(135deg, #F5B800 0%, #7DAABC 50%, #1A5276 100%);
```

---

## 4. Typography

| Role | Font | Fallback | Weight | Usage |
|------|------|----------|--------|-------|
| **Headings** | `Montserrat` | `Arial, sans-serif` | 700 (Bold) | H1–H3, nav links, CTAs |
| **Subheadings** | `Montserrat` | `Arial, sans-serif` | 600 (Semi-Bold) | H4–H6, card titles |
| **Body** | `Open Sans` | `Helvetica, sans-serif` | 400 (Regular) | Paragraphs, descriptions |
| **Accent/Small** | `Open Sans` | `Helvetica, sans-serif` | 600 (Semi-Bold) | Labels, badges, fine print |

- All headings should be **uppercase** or **title case** — match the logo's bold, all-caps styling.
- Minimum body font size: **16px**.
- Line height for body text: **1.6**.

---

## 5. Tone & Voice

| Attribute | Description |
|-----------|-------------|
| **Professional** | We are licensed experts. Communicate competence and reliability. |
| **Friendly** | Approachable, not corporate. Speak like a trusted neighbor. |
| **Urgent but calm** | AC emergencies happen — acknowledge urgency without panic. |
| **Local** | Reference South Florida climate, humidity, and lifestyle. |
| **Action-oriented** | Every section should guide toward contacting us or requesting a quote. |

### Example Phrases
- "Keeping South Florida cool since day one."
- "24/7 emergency AC repair — we're one call away."
- "Your comfort is our business."
- "Licensed, insured, and ready to serve."

### Approved Website Headlines

**Hero / Main:**
- "Comfort You Can Count On — 24/7"
- "Southwest Florida's Trusted HVAC Professionals"
- "Cooling Fort Myers, One Home at a Time"
- "Your Comfort. Our Priority. Every Day."

**Services Section:**
- "Expert AC Repair, Installation & Maintenance"
- "From Emergency Repairs to Annual Tune-Ups — We Do It All"

**Maintenance Plan Section:**
- "Protect Your System. Prevent the Breakdown."
- "One Plan. Two Tune-Ups. Year-Round Peace of Mind."
- "Stop Paying for Problems — Start Preventing Them"

**Why Choose Us:**
- "Licensed. Insured. Locally Owned. Always Available."
- "No Hidden Fees. No Surprises. Just Honest HVAC Service."

**CTA / Contact:**
- "Ready for Reliable AC? Call (239) 785-6399"
- "Get a Free Quote — It Only Takes a Minute"
- "Schedule Your Tune-Up Before the Heat Hits"

### Words to USE: reliable, trusted, certified, comfort, efficient, fast, local, family
### Words to AVOID: cheap, discount, basic, simple, okay

---

## 6. Website Structure

### 6.1 Single-Page Layout (Recommended)
Build as a smooth-scrolling single-page site with anchored sections:

```
[Nav Bar — sticky]
  ├── Logo (left)
  ├── Links: Home | Services | About | Reviews | Contact
  └── CTA Button: "Get a Free Quote" (Sun Gold bg)

[Hero Section]
  ├── Brand gradient background with subtle overlay
  ├── H1: "D PEC Air Conditioning Inc."
  ├── Tagline: "South Florida's Trusted HVAC Experts"
  ├── CTA: "Call Now" + "Request a Quote"
  └── Optional: hero image of technician or clean AC unit

[Services Section]
  ├── H2: "Our Services"
  ├── Icon cards (grid: 2–3 columns):
  │   ├── AC Installation
  │   ├── AC Repair
  │   ├── Preventive Maintenance
  │   ├── Duct Cleaning
  │   ├── Refrigeration Services
  │   └── Indoor Air Quality
  └── Each card: icon + title + 1–2 sentence description + "Learn More" link

[About Section]
  ├── H2: "About D PEC"
  ├── Brief company story / mission (2–3 paragraphs)
  ├── Bullet highlights: Licensed, Insured, Locally Owned, 24/7 Service
  └── Optional team/owner photo

[Why Choose Us Section]
  ├── H2: "Why Choose D PEC?"
  ├── 3–4 feature blocks:
  │   ├── 24/7 Emergency Service
  │   ├── Licensed & Insured
  │   ├── Upfront Pricing — No Hidden Fees
  │   └── 100% Satisfaction Guarantee
  └── Trust badges / certifications if available

[Reviews / Testimonials]
  ├── H2: "What Our Customers Say"
  ├── Carousel or grid of 3–5 review cards
  └── Link to Google Reviews

[Contact Section]
  ├── H2: "Get In Touch"
  ├── Contact form: Name, Phone, Email, Service Needed, Message
  ├── Phone: (239) 785-6399 (click-to-call)
  ├── Email: luispec85@gmail.com
  ├── Address: 337 Belliard Rd, Fort Myers, FL 33905
  ├── Service area map or text
  └── Business hours

[Footer]
  ├── Logo (small)
  ├── Quick links
  ├── Phone / Email
  ├── Social media icons
  ├── License #CAC1822218
  └── © 2025 D PEC Air Conditioning Inc. All rights reserved.
```

---

## 7. UI Component Guidelines

### Buttons
- **Primary CTA:** Sun Gold (`#F5B800`) background, Charcoal (`#2C3E50`) text, rounded corners (8px), bold uppercase text. Hover → Flame Orange (`#E8700A`).
- **Secondary CTA:** Transparent with Ice Blue (`#2E86DE`) border and text. Hover → filled Ice Blue with white text.

### Cards
- White background, subtle box shadow (`0 2px 8px rgba(0,0,0,0.08)`), rounded corners (12px).
- Icon or image at top, title in Semi-Bold, description in Regular body text.

### Navigation
- Sticky top nav with Deep Blue (`#1A5276`) background.
- White text links. Active/hover state: Sun Gold underline or text color.
- Mobile: hamburger menu with slide-out drawer.

### Icons
- Use a consistent icon set (Lucide, Heroicons, or Font Awesome).
- Icon color: Ice Blue for services, Sun Gold for highlights/features.

---

## 8. Imagery Style

- **Photography:** Bright, well-lit images. Clean AC units, happy homeowners, professional technicians in branded shirts.
- **Avoid:** Dark/gloomy images, stock photos that feel generic or unrelatable to Florida.
- **Style:** Warm and inviting — should feel like South Florida sunshine.
- **Overlays:** When placing text over images, use a semi-transparent gradient overlay (brand gradient at 60–70% opacity).

---

## 9. Approved Service Plan Copy

Use the following copy for the Maintenance Plan section of the website or as a standalone service page. This is also used on invoices and proposals.

### Annual HVAC Maintenance Plan — $450/year

> Your D PEC Annual Maintenance Plan includes two comprehensive tune-ups per year designed to keep your system running at peak efficiency and extend its lifespan.

**What's Included:**
- Two scheduled maintenance visits per year — one per season to prepare your system for the demands of Southwest Florida's climate
- All standard filters supplied and replaced at each visit (sizes on file for your unit)
- Complete system inspection: cleaning components, lubricating moving parts, testing controls, and verifying proper operation
- Minor repairs covered at no additional cost, including thermostat replacement, capacitor or fuse swap, short circuit correction, and drain line clearing
- Priority scheduling for plan members

**What's Not Included:**
- Major repairs such as compressor replacement, motor failure, ductwork damage, or refrigerant leak remediation — quoted separately at preferred customer rates

**Closing CTA:** "Prevent unexpected breakdowns, maintain healthy indoor air quality, and protect your investment. Call (239) 785-6399 to sign up today."

---

## 10. SEO & Meta

```html
<title>D PEC Air Conditioning Inc. | Fort Myers HVAC Experts</title>
<meta name="description" content="D PEC Air Conditioning Inc. provides expert AC installation, repair, and maintenance services in Fort Myers and Southwest Florida. License #CAC1822218. Available 24/7. Call (239) 785-6399 for a free quote.">
<meta name="keywords" content="HVAC, air conditioning, AC repair, AC installation, Fort Myers, Southwest Florida, D PEC, refrigeration, duct cleaning, maintenance plan">
```

### Schema Markup
Include `LocalBusiness` structured data with:
- Business name, phone, address, service area
- Opening hours
- Rating/reviews if available

---

## 11. Technical Requirements

- **Responsive:** Mobile-first design, fully responsive across all breakpoints.
- **Performance:** Lazy-load images, optimize assets, target Lighthouse score ≥ 90.
- **Accessibility:** WCAG 2.1 AA compliance — proper contrast ratios, alt text, keyboard navigation.
- **Framework:** Use whatever modern framework is appropriate (React, Next.js, plain HTML/CSS/JS — dealer's choice).
- **Hosting-ready:** Static export preferred for easy deployment to Cloudflare Pages, Netlify, or Vercel.

---

## 12. Assets Checklist

| Asset | Status | Notes |
|-------|--------|-------|
| Logo (PNG, transparent bg) | ✅ Provided | `dpec-logo.png` |
| Logo (SVG) | ⬜ Needed | Vector version for scalability |
| Favicon | ⬜ Generate | Crop the sun/snowflake icon |
| Hero image | ⬜ Needed | Technician photo or AC unit |
| Service icons | ⬜ Generate | Use icon library |
| Team/owner photo | ⬜ Optional | For About section |
| Google Reviews link | ⬜ Needed | For testimonials section |

---

*Generated for use with Gemini Pro or any AI code generation tool. Provide this file alongside the logo asset when prompting for website creation.*
