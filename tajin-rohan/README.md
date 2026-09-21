# Tajin Rohan — Digital Marketer & Creative Professional Portfolio

A modern, high-performance, fully responsive personal portfolio website built with Vite and Tailwind CSS design principles. Designed with custom liquid reveal hero aesthetics, interactive project showcase, direct WhatsApp & Facebook channels, client inquiry management, and an integrated private admin dashboard.

---

## 🚀 Features

- **Liquid Reveal Hero Section**: Dynamic interactive portrait banner with mouse/touch fluid reveal and high-contrast typography.
- **100% Fully Responsive Layout**: Mobile-first design architecture with adaptive touch targets (44px+), fluid typography, and clean layouts from 320px mobile screens to 4K ultra-wide monitors.
- **Direct Connect Channels**:
  - **WhatsApp Direct**: Configured with `+880 1745-004768` (`https://wa.me/8801745004768`) across contact cards, footer, and a floating quick-action pill button.
  - **Facebook Profile**: Direct link to `https://www.facebook.com/profile.php?id=61592719674201`.
  - **Email**: Direct mailto integration for `rohanhrfnf@gmail.com`.
- **Project Case Studies & Filtering**: Categorized showcase (Digital Campaigns, Video & Reels, Photo Retouching, Portfolio Websites) with impact metrics, detail modals, and live data synchronization.
- **Interactive Inquiry & Quote Form**: Validated project inquiry form with instant submission feedback and local persistence.
- **Built-in Admin Panel**: Accessible via secret shortcut (clicking the copyright text 3 times or pressing the hero edit button) with PIN protection (`1234` by default, customizable).
  - Edit profile bio, roles, banner image, email, WhatsApp number, and Facebook URL.
  - Add, edit, or delete projects with live image uploads.
  - View, manage, and delete incoming client inquiries.
  - Export and import complete portfolio backup JSON files.

---

## 📦 Deployment to Vercel

This repository is pre-configured with `vercel.json` for zero-configuration, production deployment on [Vercel](https://vercel.com).

### Option 1: Deploy via Vercel Dashboard (Recommended)

1. Push this project to your GitHub, GitLab, or Bitbucket account.
2. Go to [vercel.com/new](https://vercel.com/new).
3. Import your repository.
4. Vercel will automatically detect the settings from `vercel.json`:
   - **Framework Preset**: `Vite`
   - **Build Command**: `npm run build`
   - **Output Directory**: `dist`
   - **Install Command**: `npm install`
5. Click **Deploy**. Your portfolio will be live with an SSL certificate within seconds!

### Option 2: Deploy via Vercel CLI

```bash
# 1. Install Vercel CLI globally
npm i -g vercel

# 2. Login to Vercel
vercel login

# 3. Deploy to production
vercel --prod
```

---

## 💻 Local Development

### Prerequisites
- Node.js 18.0 or higher
- npm, yarn, or pnpm

### Setup
```bash
# 1. Clone the repository
git clone <your-repo-url>
cd <repo-folder>

# 2. Install dependencies
npm install

# 3. Start local development server
npm run dev
```

Visit `http://localhost:3000` in your web browser.

### Build for Production
```bash
npm run build
```
The compiled, production-ready static assets will be output to the `dist/` directory.

### Preview Production Build
```bash
npm run preview
```

---

## ⚙️ Configuration Files

- `vercel.json`: Vercel routing rules, single-page application fallback, and HTTP security/caching headers.
- `vite.config.ts`: Vite build configuration with Tailwind CSS plugin and path aliases.
- `metadata.json`: Application metadata and platform capabilities.
- `package.json`: NPM scripts and dependencies.
- `index.html`: Main HTML entry point, typography tokens, semantic structure, responsive CSS, and application engine.

---

## 🔒 Admin Access
- **Default PIN**: `1234`
- **Trigger**: Click "© 2026 Tajin Rohan" in the website footer 3 times in quick succession, or click the small edit icon beside your name in the hero section.
