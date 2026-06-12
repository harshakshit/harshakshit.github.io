# Harsh Akshit - AI Security & AppSec Portfolio

A modern, high-fidelity portfolio website showcasing expertise in AI Security, LLM Jailbreaking, and Application Security. Built with a "cyber-minimalist" design aesthetic featuring dark mode, neon accents, and smooth animations.

---

## 🎨 Design Overview

### Theme: Cyber-Minimalist
- **Color Scheme**: Deep space backgrounds (midnight blue/charcoal) with cyber cyan and electric green neon accents
- **Typography**: 
  - Headers: Inter (modern sans-serif)
  - Code/Technical: JetBrains Mono (monospaced)
- **Vibe**: Authoritative yet innovative, immediately communicating AI Security and AppSec expertise

### Color Palette

| Color | Hex Code | Usage |
|-------|----------|-------|
| Deep Space | `#0A0E27` | Main background |
| Charcoal Dark | `#1A1D2E` | Secondary background |
| Obsidian | `#16213E` | Card backgrounds |
| Cyber Cyan | `#00F5FF` | Primary accent (CTAs, links) |
| Electric Green | `#39FF14` | Secondary accent (code, security) |
| Neon Purple | `#B026FF` | Tertiary accent |
| Ghost White | `#F8F9FA` | Primary text |
| Silver Gray | `#B8C1CC` | Secondary text |
| Muted Slate | `#6C757D` | Tertiary text |

---

## 📁 Project Structure

```
portfolio-explorash/
├── index.html              # Main portfolio HTML file
├── DESIGN_SYSTEM.md        # Complete design system documentation
├── CONTENT_COPY.md         # All written content and copy
└── README.md               # This file
```

---

## 🚀 Quick Start

### Option 1: Local Development

1. **Navigate to the repository:**
   ```bash
   cd /Users/harshakshit/portfolio-explorash
   ```

2. **Open the portfolio:**
   - Simply open `index.html` in your web browser
   - Or use a local server for best results:
   
   ```bash
   # Python 3
   python3 -m http.server 8000
   
   # Then visit: http://localhost:8000
   ```

### Option 2: Deploy to GitHub Pages

1. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Add portfolio website"
   git push origin main
   ```

2. **Enable GitHub Pages:**
   - Go to repository Settings → Pages
   - Source: Deploy from branch `main`
   - Folder: `/ (root)`
   - Save and wait for deployment

3. **Your site will be live at:**
   ```
   https://harshakshit.github.io/portfolio-explorash/
   ```

### Option 3: Deploy to Netlify

1. **Drag and drop** the entire folder to [Netlify Drop](https://app.netlify.com/drop)
2. **Or connect via Git:**
   - New site from Git → GitHub
   - Select `portfolio-explorash` repository
   - Build settings: None needed (static site)
   - Deploy!

---

## 📋 Portfolio Sections

### 1. **Hero Section**
- Headline: "Securing the Future of AI & Application Infrastructure"
- Sub-headline with specializations
- Dual CTAs: "View Research" and "Contact Me"
- Social media links (LinkedIn, GitHub, Medium)
- Animated scroll indicator

### 2. **About Me**
- Professional summary highlighting AI Security and AppSec expertise
- Key stats cards:
  - 2M+ Consumers Protected
  - 80+ Client Projects
  - 15+ Publications & Research

### 3. **Professional Journey (Timeline)**
Interactive timeline featuring:
- **AI Security Research Engineer** @ Wingback Security, Inc. (Current)
- **AI Security Research Intern** @ Pillar Security Inc.
- **Teaching Assistant** @ Indiana University Bloomington
- **Security Consultant** @ Synopsys (formerly Cigital)

### 4. **Featured Research & Projects**
- Breaking Payment Gateways: A Deep Dive
- Deep Dive: Latest LLM Jailbreak Techniques
- Cloud Village CTF Challenges @ DEF CON
- Google Calendar IDOR Vulnerability Discovery

### 5. **Technical Arsenal (Skills)**
Organized into 5 categories:
- AI & Cloud Security
- Application Security
- Compliance & Privacy
- Development & Automation
- Network & Infrastructure

### 6. **Recognition & Certifications**
- AWS Certified Security – Specialty
- AWS Solutions Architect (Associate)
- CompTIA Security+
- Google Bughunter Hall of Fame
- Amazon AppSec CTF Finalist
- DEF CON Goon (Volunteer)
- Cloud Village CTF Creator

### 7. **Education**
- MS in Cybersecurity Risk Management (Indiana University)
- B.Tech in Computer Science (BIT Mesra)

### 8. **Contact**
- Email: harshakshit.bit@gmail.com
- Phone: +1 (930) 904-4151
- Location: Indiana, US

---

## ✨ Interactive Features

### Animations & Effects
- ✅ **Neon glow effects** on headings and accents
- ✅ **Card hover animations** with lift and glow
- ✅ **Timeline pulse animation** on experience dots
- ✅ **Skill pill hover effects** with shimmer
- ✅ **Smooth scroll navigation**
- ✅ **Fade-in animations** on section scroll
- ✅ **Social icon rotate & scale** on hover
- ✅ **Mobile-responsive design**
- ✅ **Animated background gradient**

### Interactive Elements
- ✅ Fixed navigation bar with blur effect
- ✅ Mobile hamburger menu
- ✅ Smooth scroll to sections
- ✅ CTA buttons with neon glow
- ✅ Social media links with external icons
- ✅ Project cards with hover effects
- ✅ Badge grid with shimmer

---

## 🛠️ Customization Guide

### Update Personal Information

1. **Contact Details** (Line 875-880):
   ```html
   <a href="mailto:YOUR_EMAIL@gmail.com">
   <a href="tel:+1YOURNUMBER">
   ```

2. **Social Media Links** (Multiple locations):
   - GitHub URL: Currently placeholder - add your GitHub profile
   - LinkedIn: Already configured
   - Medium/InfoSec: Already configured

### Add New Projects

Find the "Featured Projects" section (around line 620) and duplicate a card:

```html
<div class="card">
    <div class="mb-4">
        <span class="text-xs font-semibold text-cyber-cyan bg-cyber-cyan/10 px-3 py-1 rounded-full">
            🔐 Your Category
        </span>
    </div>
    <h3 class="text-xl font-bold text-ghost-white mb-3">Your Project Title</h3>
    <p class="text-silver-gray mb-4 text-sm leading-relaxed">
        Your project description...
    </p>
    <!-- Add your content -->
</div>
```

### Modify Colors

All colors are defined in CSS variables (line 30-42):

```css
:root {
    --cyber-cyan: #00F5FF;      /* Change primary accent */
    --electric-green: #39FF14;   /* Change secondary accent */
    --deep-space: #0A0E27;      /* Change background */
}
```

---

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints:
- **Mobile**: 0-640px
- **Tablet**: 641-1024px
- **Desktop**: 1025px+

Mobile features:
- Hamburger menu navigation
- Stacked layouts for better readability
- Touch-friendly buttons (min 44x44px)
- Optimized text sizes

---

## 🔧 Technical Stack

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (CDN)
- **Custom CSS**: Advanced animations and effects
- **JavaScript**: Mobile menu, smooth scrolling, intersection observers
- **Font Awesome 6**: Icons
- **Google Fonts**: Inter & JetBrains Mono

### Performance Optimization
- ✅ CDN-hosted libraries for fast delivery
- ✅ Lazy-loading animations via Intersection Observer
- ✅ Minimal JavaScript for better performance
- ✅ Web fonts with preconnect for faster loading
- ✅ Optimized CSS with minimal external dependencies

---

## 🎯 SEO & Accessibility

### SEO Features
- ✅ Semantic HTML structure
- ✅ Meta tags for description and keywords
- ✅ Clean URL structure
- ✅ Fast load times

### Accessibility Features
- ✅ ARIA labels for interactive elements
- ✅ Keyboard navigation support
- ✅ High contrast ratios (WCAG AAA compliant)
- ✅ Focus indicators on interactive elements
- ✅ Semantic heading hierarchy

---

## 📝 Content Documentation

All content is documented in `CONTENT_COPY.md` including headlines, body copy, and descriptions for each section.

Complete design documentation is available in `DESIGN_SYSTEM.md` with color palette, typography, layouts, and interaction patterns.

---

## 🚀 Next Steps

### Enhancements to Consider

1. **Add Profile Photo**: Replace the icon in the About section with your professional headshot
2. **Blog Integration**: Connect to Medium RSS feed for dynamic blog posts
3. **Contact Form**: Add a functional contact form (Formspree, Netlify Forms)
4. **Analytics**: Add Google Analytics or Plausible for visitor tracking
5. **Resume Download**: Add PDF resume download button
6. **Project Screenshots**: Add visuals to project cards

---

## 📄 License

© 2025 Harsh Akshit. All Rights Reserved.

---

## 📫 Connect

- 📧 Email: harshakshit.bit@gmail.com
- 💼 LinkedIn: [linkedin.com/in/harshakshit](https://www.linkedin.com/in/harshakshit/)
- 📝 Blog: [InfoSec Writeups](https://infosecwriteups.com/)

---

**Built with precision and paranoia. 🔐**
