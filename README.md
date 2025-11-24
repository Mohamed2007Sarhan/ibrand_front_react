# 🚀 iBrand Marketing Agency - Professional Digital Marketing Platform

<div align="center">

![iBrand Logo](public/globe.svg)

**Professional Digital Marketing & Branding Solutions**

[![Next.js](https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![Framer Motion](https://img.shields.io/badge/Framer_Motion-12-0055FF?style=for-the-badge&logo=framer)](https://www.framer.com/motion/)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Website](https://img.shields.io/badge/Website-ibrand.agency-blue?style=for-the-badge)](https://ibrand.agency)
[![Email](https://img.shields.io/badge/Email-ibrandmarketingagency@gmail.com-red?style=for-the-badge)](mailto:ibrandmarketingagency@gmail.com)

**Developed by [Mohamed Sarhan](https://mohamed-sarhan.vercel.app)**

**Website [IBrand](https://ibrand-agency.vercel.app/)**

</div>

---

## 📋 Table of Contents

- [🎯 Overview](#-overview)
- [✨ Key Features](#-key-features)
- [🏗️ Technical Architecture](#️-technical-architecture)
- [📁 Project Structure](#-project-structure)
- [🚀 Installation & Setup](#-installation--setup)
- [🎨 Design System](#-design-system)
- [🌍 Multi-language Support](#-multi-language-support)
- [📱 Responsive Design](#-responsive-design)
- [⚡ Performance & Optimization](#-performance--optimization)
- [🔧 Customization & Development](#-customization--development)
- [📊 Statistics & Metrics](#-statistics--metrics)
- [🤝 Contributing](#-contributing)
- [📞 Contact](#-contact)

---

## 🎯 Overview

**iBrand Marketing Agency** is a cutting-edge, multi-language digital marketing platform designed to deliver comprehensive and innovative marketing solutions. The platform combines visual excellence with high performance to provide an exceptional user experience.

### 🎨 Design Philosophy
- **Motion-First Design**: Every element is designed to be interactive and visually engaging
- **Results-Oriented**: Every design aims to achieve clear marketing objectives
- **Inclusivity**: Full support for Arabic and English with RTL
- **High Performance**: Comprehensive optimization for speed and performance

### 🏆 Key Strengths
- **Comprehensive Expertise**: From visual identity to paid advertising
- **Professional Quality**: High-quality designs that compete with the best global agencies
- **Fast Execution**: High quality with fast delivery
- **Data-Driven**: Informed decisions based on data

---

## ✨ Key Features

### 🎨 Creative Services
- **🎭 Visual Identity**: Complete logo design and brand guidelines
- **🖼️ Graphic Design**: Marketing materials and social media graphics
- **🎬 Motion Graphics**: Animated logos and explainer videos
- **✂️ Video Editing**: Professional video production and editing
- **✍️ Content Writing**: SEO-optimized content in Arabic and English
- **🎯 Sponsored Ads**: Facebook, Google, and Instagram campaigns
- **🎤 Voiceover**: Professional voice recording in Arabic and English
- **📅 Monthly Management**: Comprehensive social media management

### 🛠️ Technical Features
- **⚡ Next.js 15**: Latest React framework with App Router
- **🔷 TypeScript**: Complete type safety
- **🎭 Framer Motion**: Smooth and interactive animations
- **🎨 Tailwind CSS**: Fast and flexible styling
- **📱 Responsive Design**: Optimized for all devices
- **🌙 Dark/Light Mode**: User preference support
- **🚀 Performance Optimized**: Fast loading and smooth interactions

---

## 🏗️ Technical Architecture

### 🎯 Core Technologies
```typescript
// Technologies Used
{
  "framework": "Next.js 15",
  "language": "TypeScript 5",
  "styling": "Tailwind CSS 4",
  "animations": "Framer Motion 12",
  "icons": "Lucide React",
  "deployment": "Vercel"
}
```

### 🏛️ Architecture
- **App Router**: Modern Next.js routing system
- **Server Components**: Performance-optimized server components
- **Client Components**: Interactive client components
- **API Routes**: Built-in API routes
- **Static Generation**: Static content generation

---

## 📁 Project Structure

```
ibrand-0/
├── 📁 app/                          # Application pages (App Router)
│   ├── 📄 layout.tsx                # Main layout
│   ├── 📄 page.tsx                  # Home page
│   ├── 📄 globals.css               # Global styles
│   ├── 📁 about/                    # About page
│   ├── 📁 services/                 # Service pages
│   │   ├── 📄 page.tsx              # Main services page
│   │   ├── 📁 visual-identity/      # Visual identity service
│   │   ├── 📁 graphic-design/       # Graphic design service
│   │   ├── 📁 motion-graphics/      # Motion graphics service
│   │   ├── 📁 video-editing/        # Video editing service
│   │   ├── 📁 content-writing/      # Content writing service
│   │   ├── 📁 sponsored-ads/        # Sponsored ads service
│   │   ├── 📁 voiceover/            # Voiceover service
│   │   └── 📁 monthly-management/   # Monthly management service
│   ├── 📁 portfolio/                # Portfolio page
│   ├── 📁 testimonials/             # Testimonials page
│   ├── 📁 contact/                  # Contact page
│   ├── 📁 careers/                  # Careers page
│   └── 📁 api/                      # API routes
│       ├── 📁 new/                  # New data API
│       └── 📁 service-results/      # Service results API
│
├── 📁 components/                   # Reusable components
│   ├── 📄 hero.tsx                  # Hero component
│   ├── 📄 header.tsx                # Header component
│   ├── 📄 footer.tsx                # Footer component
│   ├── 📄 services.tsx              # Services component
│   ├── 📄 portfolio.tsx             # Portfolio component
│   ├── 📄 testimonials.tsx          # Testimonials component
│   ├── 📄 contact.tsx               # Contact component
│   ├── 📄 about.tsx                 # About component
│   ├── 📄 careers.tsx               # Careers component
│   ├── 📁 ui/                       # UI components
│   │   ├── 📄 button.tsx            # Button component
│   │   ├── 📄 input.tsx             # Input component
│   │   └── 📄 textarea.tsx          # Textarea component
│   └── 📄 [30+ specialized components]
│
├── 📁 data/                         # Data and constants
│   ├── 📄 constants.ts              # General constants
│   ├── 📄 services.ts               # Services data
│   ├── 📄 portfolio.ts              # Portfolio data
│   ├── 📄 testimonials.ts           # Testimonials data
│   ├── 📄 team.ts                   # Team data
│   ├── 📄 navigation.ts             # Navigation data
│   ├── 📄 social-links.ts           # Social media links
│   └── 📄 types.ts                  # Type definitions
│
├── 📁 hooks/                        # Custom hooks
│   ├── 📄 use-theme.tsx             # Dark/light mode hook
│   ├── 📄 use-translation.ts        # Translation hook
│   ├── 📄 translation-provider.tsx  # Translation provider
│   └── 📄 use-animation.ts          # Animation hook
│
├── 📁 lib/                          # Libraries and utilities
│   └── 📄 utils.ts                  # Utility functions
│
├── 📁 public/                       # Public files
│   ├── 📄 globe.svg                 # Site logo
│   ├── 📄 manifest.json             # App manifest
│   ├── 📁 portfolio/                # Portfolio images
│   ├── 📁 Partners/                 # Partner images
│   └── 📁 result/                   # Result images
│
├── 📁 new/                          # New content
│   ├── 📁 content-writing/          # Content writing images
│   ├── 📁 Graphic-Design/           # Graphic design images
│   ├── 📁 motion-graphics/          # Motion graphics files
│   ├── 📁 sponsored-ads/            # Sponsored ads images
│   ├── 📁 Visual-Identity/          # Visual identity images
│   └── 📁 voiceover/                # Voiceover files
│
├── 📄 package.json                  # Project dependencies
├── 📄 next.config.ts                # Next.js configuration
├── 📄 tailwind.config.js            # Tailwind configuration
├── 📄 tsconfig.json                 # TypeScript configuration
└── 📄 README.md                     # This file
```

---

## 🚀 Installation & Setup

### 📋 Requirements
- Node.js 18+ 
- npm or yarn
- Git

### 🔧 Installation Steps

```bash
# 1. Clone the repository
git clone https://github.com/Mohamed2007Sarhan/ibrand.git

# 2. Navigate to project directory
cd ibrand

# 3. Install dependencies
npm install
# or
yarn install

# 4. Run development server
npm run dev
# or
yarn dev

# 5. Open browser at
http://localhost:3000
```

### 🏗️ Production Build

```bash
# Build the project
npm run build

# Start production server
npm start

# Lint the code
npm run lint
```

---

## 🎨 Design System

### 🎨 Color System
```css
/* Primary Colors */
:root {
  --primary-50: #eff6ff;
  --primary-500: #3b82f6;
  --primary-900: #1e3a8a;
  
  --secondary-50: #fdf4ff;
  --secondary-500: #d946ef;
  --secondary-900: #701a75;
  
  --accent-50: #f0fdf4;
  --accent-500: #22c55e;
  --accent-900: #14532d;
}
```

### 📝 Typography System
- **English**: Inter (Google Fonts)
- **Arabic**: Noto Sans Arabic, Cairo, Tajawal
- **Weights**: 100-900
- **Optimization**: Ligatures and Kerning

### 🎭 Animation System
```typescript
// Animation Examples
const fadeIn = {
  initial: { opacity: 0, y: 20 },
  animate: { opacity: 1, y: 0 },
  transition: { duration: 0.6 }
}

const slideIn = {
  initial: { opacity: 0, x: -50 },
  animate: { opacity: 1, x: 0 },
  transition: { duration: 0.5 }
}
```

---

## 🌍 Multi-language Support

### 🇺🇸 English (Default)
- Professional English content
- Specialized marketing terminology
- SEO-optimized content

### 🇸🇦 Arabic (العربية)
- Full Arabic language support
- RTL (Right-to-Left) layout
- Optimized Arabic fonts
- Cultural adaptation

### 🔄 Language Switching
```typescript
// Using translation hook
const { t, isRTL, currentLang, switchLanguage } = useTranslationContext()

// Switch language
switchLanguage('ar') // For Arabic
switchLanguage('en') // For English
```

---

## 📱 Responsive Design

### 📱 Supported Devices
- **📱 Smartphones**: iPhone, Android
- **📱 Tablets**: iPad, Android Tablets
- **💻 Computers**: Windows, macOS, Linux
- **🖥️ Large Screens**: 4K, Ultra-wide

### 🎯 Breakpoints
```css
/* Breakpoints Used */
sm: 640px   /* Large phones */
md: 768px   /* Tablets */
lg: 1024px  /* Small computers */
xl: 1280px  /* Computers */
2xl: 1536px /* Large screens */
```

---

## ⚡ Performance & Optimization

### 📊 Performance Metrics
- **Lighthouse Score**: 95+ 
- **Core Web Vitals**: Optimized for all metrics
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1

### 🚀 Optimization Techniques
- **Image Optimization**: Next.js Image component
- **Font Loading**: Preloaded critical fonts
- **Code Splitting**: Automatic code splitting
- **Static Generation**: Static content generation
- **CDN**: Content delivery network

---

## 🔧 Customization & Development

### 🎨 Theme Customization
```typescript
// hooks/use-theme.tsx
const { isDark, toggleTheme } = useTheme()

// Using theme
<div className={isDark ? "bg-slate-900" : "bg-white"}>
  Content
</div>
```

### 🌍 Language Management
```typescript
// hooks/use-translation.ts
const { t, isRTL, currentLang, switchLanguage } = useTranslationContext()

// Using translation
<h1>{t('hero.title')}</h1>
```

### 🎭 Animation Customization
```typescript
// Custom Framer Motion animations
const customVariants = {
  hidden: { opacity: 0, scale: 0.8 },
  visible: { 
    opacity: 1, 
    scale: 1,
    transition: { duration: 0.5, ease: "easeOut" }
  }
}
```

---

## 📊 Statistics & Metrics

### 🏢 Company Information
- **📅 Founded**: 2020
- **👥 Employees**: 15+
- **🎯 Projects**: 200+
- **👥 Clients**: 150+
- **🌍 Supported Languages**: Arabic, English
- **⏰ Timezone**: Africa/Cairo

### 📈 Performance Statistics
- **⚡ Loading Speed**: < 2 seconds
- **📱 Responsiveness**: 100%
- **🔍 SEO Optimization**: 95+ score
- **♿ Accessibility**: WCAG 2.1 AA
- **🌐 Browser Support**: 99%+

---

## 🚀 Deployment

### ☁️ Vercel (Recommended)
```bash
# Deploy to Vercel
vercel --prod
```

### 🌐 Other Platforms
- **Netlify**: Compatible with Next.js
- **AWS**: Amplify or custom deployment
- **Docker**: Containerized deployment

---

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. **🍴 Fork** the project
2. **🌿 Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **💾 Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **📤 Push** to the branch (`git push origin feature/AmazingFeature`)
5. **🔄 Open** a Pull Request

### 📋 Contribution Guidelines
- Follow existing code standards
- Add comments for complex code
- Test changes before submitting
- Update documentation when needed

---

## 📞 Contact

### 📧 Contact Information
- **📧 Email**: [ibrandmarketingagency@gmail.com](mailto:ibrandmarketingagency@gmail.com)
- **📱 Phone**: [+20 111 303 9402](tel:+201113039402)
- **🌐 Website**: [https://ibrand.agency](https://ibrand.agency)
- **📍 Address**: Egypt - Damietta - New Damietta

### 🌐 Social Media
- **📘 Facebook**: [facebook.com/ibrand](https://facebook.com/ibrand)
- **📷 Instagram**: [instagram.com/ibrand](https://instagram.com/ibrand)
- **🐦 Twitter**: [twitter.com/ibrand](https://twitter.com/ibrand)
- **💼 LinkedIn**: [linkedin.com/company/ibrand](https://linkedin.com/company/ibrand)
- **📺 YouTube**: [youtube.com/@ibrand](https://youtube.com/@ibrand)

### 👨‍💻 Developer
- **👨‍💻 Developer**: [Mohamed Sarhan](https://mohamed-sarhan.vercel.app)
- **💼 Portfolio**: [mohamed-sarhan.vercel.app](https://mohamed-sarhan.vercel.app)
- **📧 Developer Email**: [Contact Developer](mailto:contact@mohamed-sarhan.vercel.app)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

### 🛠️ Technologies Used
- **[Next.js](https://nextjs.org/)** - React framework
- **[TypeScript](https://www.typescriptlang.org/)** - Type safety
- **[Tailwind CSS](https://tailwindcss.com/)** - CSS framework
- **[Framer Motion](https://www.framer.com/motion/)** - Animation library
- **[Lucide React](https://lucide.dev/)** - Icon library

### 🎨 Resources
- **Google Fonts**: Arabic and English font collection
- **Unsplash**: High-quality images
- **Heroicons**: Custom icons

---

<div align="center">

**🚀 Built with ❤️ by [Mohamed Sarhan](https://mohamed-sarhan.vercel.app)**

[![Website](https://img.shields.io/badge/Website-ibrand.agency-blue?style=for-the-badge)](https://ibrand.agency)
[![Developer](https://img.shields.io/badge/Developer-Mohamed_Sarhan-green?style=for-the-badge)](https://mohamed-sarhan.vercel.app)
[![Email](https://img.shields.io/badge/Email-Contact_Us-red?style=for-the-badge)](mailto:ibrandmarketingagency@gmail.com)

---

*© 2024 iBrand Marketing Agency. All rights reserved.*


</div>
