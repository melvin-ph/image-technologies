# Image Technologies — Official Website

<p align="center">
  <strong>Innovate • Automate • Grow</strong>
</p>

<p align="center">
  A modern digital presence for a technology startup focused on AI, software engineering, computer vision, and intelligent automation.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge" alt="Project status: In development" />
  <img src="https://img.shields.io/badge/React-Technology-blue?style=for-the-badge&logo=react" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-Typed%20JavaScript-blue?style=for-the-badge&logo=typescript" alt="TypeScript" />
  <img src="https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge" alt="Proprietary license" />
</p>

---

## About Image Technologies

**Image Technologies** is a technology startup focused on developing practical digital solutions for real-world business challenges.

Our areas of interest include artificial intelligence, machine learning, computer vision, custom software development, web applications, and intelligent automation.

This repository contains the source code for the official Image Technologies company website, designed to communicate our capabilities, showcase projects, introduce our founders, and help prospective clients connect with us.

**Brand tagline:** Innovate • Automate • Grow

## Website Features

- **Modern UI/UX:** A clean, premium interface aligned with the company's brand identity.
- **Responsive Design:** Layouts designed for desktop, tablet, and mobile devices.
- **Company Profile:** Information about Image Technologies, its mission, vision, and approach.
- **Solutions:** An overview of AI/ML, computer vision, software development, and automation capabilities.
- **Project Portfolio:** A structured way to showcase projects, technical work, and case studies.
- **Founder Profiles:** Introduction to Melvin Philip, Founder & CEO, and Steve Antto D, Co-Founder.
- **Contact & Enquiries:** A dedicated interface for prospective clients to discuss projects.
- **SEO Foundations:** Structured page content, metadata, and search-friendly navigation.
- **Accessibility:** Semantic markup, readable contrast, and keyboard-friendly interactions.

Features requiring external services, credentials, or backend integration must be configured and tested before production deployment.

## Technology Stack

The intended stack for the website includes:

| Technology | Purpose |
|---|---|
| React | Component-based user interface |
| TypeScript | Type safety and maintainability |
| Vite | Development server and build tooling |
| Tailwind CSS | Responsive styling and design consistency |
| React Router | Client-side page navigation |
| Lucide | Interface icons |
| Supabase / serverless backend | Optional enquiry storage and backend functionality |
| Vercel | Suggested hosting platform |

The actual dependencies and integrations should match the implementation in this repository.

## Brand Identity

The website follows the official Image Technologies visual identity.

| Element | Value |
|---|---|
| Primary red | `#E50914` |
| Carbon black | `#17191C` |
| White | `#FFFFFF` |
| Cool grey | `#F2F3F5` |

Red is used for primary actions and highlights, black for strong typography and dark sections, and white and grey for clarity and readability.

**Design principles:**
- Minimal and purposeful layouts.
- Clear information hierarchy.
- Consistent spacing and typography.
- Restrained animation.
- Mobile-first usability.
- Credible, technically grounded content.

## Website Pages

The planned website structure includes:

| Page | Purpose |
|---|---|
| Home | Introduce the company and its capabilities |
| About Us | Present the company's mission, vision, and founders |
| Solutions | Explain services and technical capabilities |
| Industries | Explore potential industry applications |
| Projects | Showcase projects and case studies |
| Contact | Receive project enquiries |
| Privacy Policy | Explain the handling of personal information |

## Getting Started

### Prerequisites

Install the following before running the project:

- Node.js — use a current supported LTS release.
- npm, or the package manager specified by the repository.
- Git.
- A code editor such as Visual Studio Code or Google Antigravity.

### 1. Clone the repository

Replace the placeholder below with your actual GitHub repository URL.

```bash
git clone https://github.com/YOUR-USERNAME/image-technologies-website.git
cd image-technologies-website
```

### 2. Install dependencies

For an npm-based project:

```bash
npm install
```

### 3. Configure environment variables

If the project requires external services, create a local environment file using the variables documented in `.env.example`.

```bash
cp .env.example .env
```

On Windows, you can create `.env` manually if the command is unavailable.

Only add variables that the actual application requires. Never commit API keys, database credentials, private tokens, or production secrets.

### 4. Start the development server

```bash
npm run dev
```

Open the local URL printed in the terminal, commonly `http://localhost:5173`.

### 5. Build for production

```bash
npm run build
```

### 6. Preview the production build

```bash
npm run preview
```

Check `package.json` for the scripts available in your particular implementation.

## Project Structure

A suggested structure for the application is:

```text
image-technologies-website/
├── public/
│   ├── images/
│   │   ├── image-technologies-logo.jpg
│   │   ├── melvin-philip.png
│   │   └── steve-antto-d.png
│   └── icons/
├── src/
│   ├── components/
│   ├── layouts/
│   ├── pages/
│   ├── data/
│   ├── hooks/
│   ├── lib/
│   ├── styles/
│   ├── types/
│   ├── App.tsx
│   └── main.tsx
├── .env.example
├── .gitignore
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

This is an illustrative structure. Adapt it to the actual repository rather than moving or renaming existing files unnecessarily.

## Founders

### Melvin Philip
**Founder & CEO**

Responsible for the company's strategic direction, business development, and overall vision.

### Steve Antto D
**Co-Founder**

Contributes to the company's development and collaborative execution of its technology initiatives.

## Company Information

**Image Technologies**

Tagline: Innovate • Automate • Grow

**Address:**

First Floor, 913–925, Dr Rajendra Prasad Road,  
Near GP Signal,  
Coimbatore, Tamil Nadu 641012, India.

Use the official company contact details and website domain when they are finalized.

## Deployment

The website can be deployed using a supported hosting platform such as Vercel.

General deployment workflow:

1. Push the source code to GitHub.
2. Import the repository into the hosting platform.
3. Configure the build command and output directory according to the project.
4. Add the required environment variables securely.
5. Deploy a preview build.
6. Test navigation, mobile layouts, forms, and external integrations.
7. Connect the verified company domain.
8. Publish after completing the production checklist.

If client-side routing is used, configure the hosting platform to serve the application entry point for valid application routes.

## Security and Quality

Before production release:

- Validate contact form submissions on the server.
- Configure real email delivery or secure enquiry storage.
- Protect private credentials.
- Add spam protection and reasonable rate limits.
- Test all navigation and form states.
- Optimize images and loading performance.
- Verify mobile responsiveness and accessibility.
- Configure appropriate metadata and indexing.
- Publish a privacy policy that reflects actual data practices.

## Project Status

The website is intended to evolve as Image Technologies develops its brand, portfolio, and business offerings.

Update this section when the project reaches verified milestones, such as:
- Initial implementation completed.
- Contact form integration verified.
- Production deployment completed.
- Custom domain connected.

## License

Unless a different license is explicitly selected, this repository is intended for proprietary use by Image Technologies.

All rights reserved. No permission is granted to reproduce, redistribute, or commercially reuse this code without authorization from the copyright holder.

Third-party dependencies remain subject to their respective licenses.

---

<p align="center">
  <strong>Image Technologies</strong><br />
  Innovate • Automate • Grow
</p>

<p align="center">
  Building practical technology solutions for real-world challenges.
</p>
