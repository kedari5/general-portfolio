# Portfolio - Site Map & Structure

## Header (Global)
*   Logo
*   **Accessibility Controls**
    *   Text to Speech
# Kedareswari Portfolio

A personal portfolio website designed to showcase product design, development, and thoughtful digital experiences. Built with a focus on accessibility, ease of use, and premium aesthetics.

## Tech Stack
*   **Framework**: Next.js 14+ (App Router)
*   **Styling**: Tailwind CSS v4, Vanilla CSS (for complex animations)
*   **Language**: TypeScript
*   **Icons**: Lucide React
*   **Theming**: next-themes (Light/Dark mode)
*   **Accessibility**: Web Speech API (Text-to-Speech), Custom CSS Filters

## Key Features
*   **Dynamic Theme System**: Fully responsive Light and Dark modes with specific "OLED" deep blue/black themes for dark mode.
*   **Comprehensive Accessibility Suite**:
    *   Text-to-Speech (Read Aloud)
    *   Dyslexia-Friendly Font
    *   High Contrast / Invert Colors (Smart inversion excluding images)
    *   Text Resizing & Spacing Control
    *   Large Cursor & Link Highlighting
*   **Interactive Carousels**: Custom-built, touch-friendly carousels for Projects and Designs using smooth scroll locking.
*   **Glassmorphism Effects**: Premium frosted glass effects on sidebars, modals, and overlays.
*   **Smart Navigation**: Side drawer with smooth animations and a dedicated "Site Map" page.

## Site Map & Structure

### Header (Global)
*   Logo (Home Link)
*   **Accessibility Menu**: Floating panel with 10+ accessibility tools.
*   **Hamburger Menu (Side Drawer)**:
    *   Home
    *   Projects
    *   Work & Design
    *   Capabilities
    *   About
    *   Resume (View/Download)
    *   Contact
    *   Site Map

### Home (`/`)
*   **Hero Section**: Intro, "Explore Projects" CTA, Resume Link.
*   **About Preview**: Profile image and design philosophy.
*   **Projects Carousel**: Horizontal scroll of key case studies.
*   **Designs Carousel**: Horizontal scroll of visual identity work.
*   **Capabilities**: Grid of skills (Research, Design, Dev, Testing).
*   **Collaboration CTA**: "Get in Touch" button triggering the contact modal.

### Projects
Detailed case studies with Sidebar (Role, Timeline, Category), Content Sections, Tool Icons, and Final Screens Gallery.
*   `/projects/hungry-hub`: Food Delivery App
*   `/projects/build-bond`: Parent-Child Connection App
*   `/projects/krishi-sakhi`: AgriTech Farming Assistant
*   `/projects/pm-ajay`: Government Dashboard
*   `/projects/personal-portfolio`: This website's case study

### Work & Design
Visual-focused pages for brand identity and posters.
*   `/design/personal-identity`: Personal Branding
*   `/design/build-bond-identity`: App Branding
*   `/design/creative-minds-poster`: Event Poster Design

### Resources
*   **Site Map** (`/sitemap`): Full list of all pages and external links.
*   **Resume**: Direct download/view link.
*   **Socials**: LinkedIn, Behance, GitHub.

### Contact
*   **Modal**: Accessible popup form with validation (connected to Google Sheets via API).
*   **Standalone Page** (`/contact`): Dedicated contact page for direct access.

## Installation & Local Development

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/kedari5/kedareswari-portfolio.git
    ```
2.  **Install dependencies**:
    ```bash
    npm install
    ```
3.  **Run the development server**:
    ```bash
    npm run dev
    ```
4.  **Build for production**:
    ```bash
    npm run build
    ```

## deployment
Deployed on **Vercel** with automatic deployments from the `main` branch.
