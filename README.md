# Asha Coaching Classes, Lucknow 🎓

[![React 19](https://img.shields.io/badge/React-19-blue.svg)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-6.0-blue.svg)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-8.3-purple.svg)](https://vite.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-38bdf8.svg)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A complete, responsive, agency-grade website for **Asha Coaching Classes**, located in **Krishna Vihar, near V-Mart, Faizabad Road, Chinhat, Lucknow, Uttar Pradesh, India**.

Designed to look and feel like a modern educational brand — trustworthy, academic, and student-focused — with strict adherence to non-fabrication standards, accessible UI components, and local SEO for Chinhat and Lucknow.

---

## 📌 Table of Contents

- [Visual Identity & Design Tokens](#-visual-identity--design-tokens)
- [Website Sections](#-website-sections)
- [Tech Stack](#-tech-stack)
- [Project Architecture](#-project-architecture)
- [Local Setup & Installation](#-local-setup--installation)
- [Push to GitHub Guide](#-push-to-github-guide)
- [One-Click Deployment](#-one-click-deployment)
- [Institute Customization Guide](#-institute-customization-guide)
- [Local SEO Configuration](#-local-seo-configuration)
- [License](#-license)

---

## 🎨 Visual Identity & Design Tokens

| Token | Hex / Value | Applied Purpose |
| :--- | :--- | :--- |
| **Primary Navy** | `#142747` | Navbar, hero background, cards, typography, and authority branding |
| **Secondary Sand** | `#F8F7F3` | Page canvas, soft backgrounds, badges, and card borders |
| **Accent Orange** | `#FF8A36` | Primary action CTAs, step indicators, focus rings, and badges |
| **Fonts** | Plus Jakarta Sans & Inter | Clean, academic, and modern typography |
| **Icons** | Lucide React | Uniform line icons |

---

## 🚀 Website Sections

1. **Top Bar & Sticky Navbar**:
   - Location display (*Krishna Vihar, near V-Mart, Faizabad Road, Chinhat, Lucknow*).
   - Live admission status badge.
   - Smooth-scrolling desktop links & responsive mobile slide drawer.
   - Shortcut to the in-browser **Institute Admin Guide**.

2. **Hero Section (Two-Column Layout)**:
   - Eyebrow: `"YOUR FUTURE STARTS HERE"`.
   - Headline: `"Learn Today. Lead Tomorrow."`.
   - Verified educational narrative emphasizing foundations and student confidence.
   - High-definition study photography with refined academic focus card.
   - Zero invented metrics or rankings.

3. **About the Institute ("A Better Way to Learn")**:
   - 5 Teaching Philosophy pillars:
     - Clear Conceptual Understanding
     - Supportive Teaching & Mentorship
     - Regular Practice & Revision
     - Individual Attention Where Available
     - Building Confidence & Consistent Study Habits

4. **Courses Section**:
   - Interactive category filter (*All, Foundation 6th-8th, High School Boards 9th-10th, Senior Secondary Science/Commerce, Custom Revision*).
   - Verified placeholder badges (`[Sample Entry]`) for development transparency.
   - *"Enquire About This Course"* buttons automatically pre-fill the course in the admission form and smooth-scroll to it.

5. **Why Choose Us (5 Core Brand Pillars)**:
   - Concept-focused learning, student-friendly environment, practice and revision, academic guidance, and patient mentorship.
   - Footnote stating proposed institute messaging.

6. **Three-Step Learning Journey**:
   - **Step 1: Understand the Concepts** (Building Strong Foundations).
   - **Step 2: Practice and Improve** (Bridging Knowledge to Execution).
   - **Step 3: Grow with Confidence** (Excelling in Academic Milestones).

7. **Results, Testimonials & Trust**:
   - Strict non-fabrication adherence:
     > *"Student achievements will be updated here upon batch record verification."*
   - Interactive preview toggle for client walkthroughs showing how verified student and parent reviews render once records are confirmed.

8. **Visual Highlights & Gallery**:
   - Category filtering (*Classroom, Study Sessions, Guidance, Campus*).
   - Clearly labeled `[Demo Visual]` badges.
   - Accessible Fullscreen Lightbox with keyboard navigation (`Esc`, `ArrowLeft`, `ArrowRight`).

9. **Admission Enquiry Form**:
   - Complete field validation: Student Name, Parent Name, 10-digit Indian Mobile Number (`/^[6-9]\d{9}$/`), Course dropdown, and Preferred Contact Method.
   - Instant visual error messages & duplicate submission protection.
   - Real-time submission receipt with unique reference code (e.g. `ACC-XXXX-XXX`) and localStorage logging.
   - Pre-formatted WhatsApp transfer button.
   - Clean backend integration point for EmailJS, Formspree, or webhooks.

10. **Contact & Location**:
    - Physical address: *Krishna Vihar, near V-Mart, Faizabad Road, Chinhat, Lucknow, Uttar Pradesh 226028*.
    - Proximity guidance: Matiyari, Chinhat Tiraha, and Kamta crossing.
    - One-click Google Maps navigation button and responsive embedded Google Map iframe.

11. **Footer & Compliance**:
    - Dynamic copyright year (`new Date().getFullYear()`).
    - Modals for **Privacy Policy** and **Terms of Admission**.
    - Local area citations for Chinhat and Lucknow.

12. **Floating WhatsApp Action**:
    - Floating bottom-right action button with pulsing notification badge for instant mobile inquiries.

---

## 🛠️ Tech Stack

- **Framework**: [React 19](https://react.dev/) + [Vite 8](https://vite.dev/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/) (using `@tailwindcss/vite`)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Typography**: Google Fonts (Plus Jakarta Sans & Inter)
- **Structured Data**: Schema.org `EducationalOrganization` (JSON-LD)

---

## 📁 Project Architecture# asha-coaching-website
