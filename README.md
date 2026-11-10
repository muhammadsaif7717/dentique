# 🦷 Dentique — Luxury Dental Clinic & Aesthetic Smile Studio

[![Next.js](https://img.shields.io/badge/Next.js-16.4-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![Vercel](https://img.shields.io/badge/Vercel-Deployed-black?style=for-the-badge&logo=vercel)](https://dentique-vert.vercel.app)
[![License: Custom Evaluation](https://img.shields.io/badge/License-Evaluation_Only-orange?style=for-the-badge)](./LICENSE)

> **Dentique** is an ultra-modern, high-converting web platform crafted for luxury dental clinics, oral healthcare centers, and aesthetic smile makeover studios. Designed with clean clinical aesthetics, sunlit warmth, and friction-free patient booking workflows.

🌐 **Live Demo:** [https://dentique-vert.vercel.app](https://dentique-vert.vercel.app)  
💻 **GitHub Repository:** [https://github.com/muhammadsaif7717/dentique](https://github.com/muhammadsaif7717/dentique)

---

## 🌟 Key Features

### 1. 🏥 Dynamic Multi-Clinic Architecture
- Built-in multi-tenant clinic personalization via query parameters (`?client=...`).
- Dynamically loads specific clinic profiles, contact details, branch addresses, emergency hotlines, and branding.

### 2. 📅 Interactive Appointment Booking Modal
- Seamless modal workflow accessible across any section or service card.
- Auto-populates selected dental treatment (e.g., Cosmetic Makeover, Dental Implants, Teeth Whitening).
- Interactive date & time picker, doctor selection, and instant booking confirmation state.

### 3. ✨ Smile Transformation Before & After Slider
- Interactive split-image comparison slider showcasing real patient dental transformations.
- Instant visual validation of cosmetic dentistry, veneer installations, and orthodontics.

### 4. 🧭 Tabbed "Why Choose Us" Navigator
- Intuitive tab-driven feature breakdown covering routine dental checkups, root canal therapies, laser teeth cleaning, and dental implants.
- Smooth transitions with verified clinical statistics and technology highlights.

### 5. 🩺 Comprehensive Dental Services Catalog
- Dedicated cards for key dental specializations: Cosmetic Smile Makeovers, Orthodontics, Pediatric Care, Dental Implants, Periodontal Therapy, and Laser Whitening.
- Direct-to-booking triggers embedded in each service.

### 6. 🛣️ 4-Step Patient Journey Workflow
- Transparent treatment roadmap: **Appointment Scheduling ➔ Diagnostic Dental Scan ➔ Gentle Treatment ➔ Post-Care & Smile Follow-up**.
- Builds patient confidence and eliminates dental anxiety.

### 7. 👨‍⚕️ Specialist Doctors & Verified Reviews
- Complete certified dental specialist profiles with BMDC qualifications, specialties, and appointment slots.
- Real patient feedback with 5-star ratings, verified badges, and testimonial carousels.

### 8. 📰 SEO-Driven Dental Health Blog
- Dynamic slug-based routing (`/blog/[slug]`) featuring in-depth dental wellness guides.
- Search engine-optimized with `sitemap.ts`, `robots.ts`, OpenGraph previews, and structured metadata.

### 9. 📱 Mobile-First UX & Floating Booking Bar
- Sticky mobile navigation with one-tap emergency call and quick booking bar.
- Animated smooth scroll-to-top progress button.

---

## 🛠️ Technology Stack

| Layer | Technologies |
|---|---|
| **Framework** | [Next.js 16](https://nextjs.org/) (App Router, Server & Client Components) |
| **Library** | [React 19](https://react.dev/) |
| **Language** | [TypeScript](https://www.typescriptlang.org/) |
| **Styling** | [Tailwind CSS v4](https://tailwindcss.com/) with `@tailwindcss/turbopack` |
| **Icons** | [Lucide React](https://lucide.dev/) |
| **Typography** | Google Fonts (`DM Sans`) |
| **SEO & Meta** | Dynamic Next.js Metadata, XML Sitemap, Robots.txt |
| **Deployment** | [Vercel](https://vercel.com/) |

---

## 📂 Project Structure

```text
dentique/
├── public/                 # Optimized clinic assets, doctor portraits & icons
├── src/
│   ├── app/
│   │   ├── blog/           # Blog index & dynamic [slug] article pages
│   │   ├── globals.css     # Tailwind v4 configuration & theme variables
│   │   ├── layout.tsx      # Root layout, metadata & font providers
│   │   ├── page.tsx        # Dentique flagship interactive landing page
│   │   ├── robots.ts       # Automated robots.txt generator
│   │   └── sitemap.ts      # Automated XML sitemap generator
│   ├── components/         # Modular UI components
│   │   ├── AppointmentModal.tsx
│   │   ├── BeforeAfterSection.tsx
│   │   ├── DoctorSection.tsx
│   │   ├── FaqSection.tsx
│   │   ├── Hero.tsx
│   │   ├── Navbar.tsx
│   │   ├── ServicesSection.tsx
│   │   ├── WhyChooseUs.tsx
│   │   └── ...
│   └── data/
│       ├── blog.ts         # Dental articles & educational content
│       └── clinics.ts      # Multi-clinic configuration data & services
├── package.json
├── tsconfig.json
└── next.config.ts
```

---

## 🚀 Getting Started

### Prerequisites
- **Node.js**: v18.17.0 or higher
- **npm**, **yarn**, or **pnpm**

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/muhammadsaif7717/dentique.git
   cd dentique
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the local development server:**
   ```bash
   npm run dev
   ```

4. **Open in browser:**
   Navigate to [http://localhost:3000](http://localhost:3000)

### Production Build

```bash
npm run build
npm run start
```

---

## 💡 Engineering Highlights

- **Component Modularity:** Decoupled UI components allowing rapid rebranding and custom deployments for diverse clinics.
- **Micro-Interactions:** Subtle hover states, smooth scroll-into-view triggers, and interactive before/after sliders designed to maximize patient conversion.
- **Accessibility & Performance:** Strict WCAG color contrast standards, semantic HTML5 tags, and responsive layouts tested across mobile, tablet, and ultra-wide screens.

---

## 👨‍💻 Author

**Muhammad Saif**  
- GitHub: [@muhammadsaif7717](https://github.com/muhammadsaif7717)  
- Live Project: [https://dentique-vert.vercel.app](https://dentique-vert.vercel.app)

---

## 📄 License

This project is licensed under a **Custom Source-Available & Evaluation License**.

- ✅ **Allowed:** You are welcome to clone, download, inspect, and run this application locally for personal learning, evaluation, and educational demonstration purposes.
- ❌ **Prohibited:** You may **not** modify, alter, redistribute, rebrand, or publish this software (in whole or in part) under your own name or for commercial use without explicit prior written authorization from the copyright holder.

See the full [`LICENSE`](./LICENSE) file for legal details.
