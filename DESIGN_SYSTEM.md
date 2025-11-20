# Portfolio Design System - Harsh Akshit
## Cyber-Minimalist Theme for AI Security Professional

---

## 🎨 Color Palette

### Primary Colors
- **Deep Space**: `#0A0E27` - Main background (midnight blue)
- **Charcoal Dark**: `#1A1D2E` - Secondary background
- **Obsidian**: `#16213E` - Card backgrounds

### Accent Colors
- **Cyber Cyan**: `#00F5FF` - Primary accent (CTAs, links, highlights)
- **Electric Green**: `#39FF14` - Secondary accent (code, security indicators)
- **Neon Purple**: `#B026FF` - Tertiary accent (special highlights)

### Text Colors
- **Ghost White**: `#F8F9FA` - Primary text
- **Silver Gray**: `#B8C1CC` - Secondary text
- **Muted Slate**: `#6C757D` - Tertiary text

### Status Colors
- **Success Green**: `#00D9A3` - Achievements, certifications
- **Warning Amber**: `#FFB800` - Important highlights
- **Error Red**: `#FF3366` - Critical security focus

---

## 📐 Typography System

### Font Families
```css
--font-primary: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
--font-heading: 'Inter', sans-serif;
--font-mono: 'JetBrains Mono', 'Fira Code', monospace;
```

### Type Scale
- **H1 (Hero)**: 4.5rem (72px) - Font weight: 700
- **H2 (Section Headers)**: 3rem (48px) - Font weight: 600
- **H3 (Sub-sections)**: 2rem (32px) - Font weight: 600
- **H4 (Cards/Items)**: 1.5rem (24px) - Font weight: 500
- **Body Large**: 1.25rem (20px) - Font weight: 400
- **Body Regular**: 1rem (16px) - Font weight: 400
- **Body Small**: 0.875rem (14px) - Font weight: 400
- **Code/Technical**: 0.9rem (14.4px) - Font weight: 400 (Monospace)

---

## 📱 Layout Structure

### Grid System
- **Container Max Width**: 1280px
- **Breakpoints**:
  - Mobile: 0-640px
  - Tablet: 641-1024px
  - Desktop: 1025px+
- **Spacing Scale**: 4px base (4, 8, 16, 24, 32, 48, 64, 96, 128)

### Section Layout

#### 1. **Hero Section** (Full Viewport Height)
```
┌─────────────────────────────────────────┐
│  Navigation Bar (Fixed Top)             │
├─────────────────────────────────────────┤
│                                         │
│       H1: Main Headline                 │
│       [Cyber Cyan underline effect]     │
│                                         │
│       H2: Sub-headline                  │
│       [Muted color, wider tracking]     │
│                                         │
│   [CTA Button 1]  [CTA Button 2]        │
│   (Cyber Cyan)    (Outlined)            │
│                                         │
│   [LinkedIn] [GitHub] [Medium]          │
│   Social icons with hover glow          │
│                                         │
│        ↓ Scroll Indicator ↓             │
└─────────────────────────────────────────┘
```

#### 2. **About Me Section**
```
┌─────────────────────────────────────────┐
│  H2: About Me [Electric Green accent]   │
│  ─────────────                          │
│                                         │
│  ┌───────────────────────────────────┐  │
│  │  Profile Image (circular)         │  │
│  │  + Decorative code bracket        │  │
│  └───────────────────────────────────┘  │
│                                         │
│  Body text with technical terms        │
│  highlighted in monospace font         │
│                                         │
│  Key Stats Cards (3-column grid):      │
│  ┌─────┐  ┌─────┐  ┌─────┐             │
│  │ 2M+ │  │ 80+ │  │ 15+ │             │
│  │Users│  │Proj │  │Pubs │             │
│  └─────┘  └─────┘  └─────┘             │
└─────────────────────────────────────────┘
```

#### 3. **Experience Timeline** (Interactive)
```
┌─────────────────────────────────────────┐
│  H2: Experience                         │
│  ─────────────                          │
│                                         │
│  ┌─────────────────────────────────┐    │
│  │ [Current] AI Security Research  │    │
│  │ Pillar Security Inc.            │    │
│  │ • Bullet points                 │    │
│  │ • Tech stack badges             │    │
│  └─────────────────────────────────┘    │
│           │                             │
│           ● (Timeline dot)              │
│           │                             │
│  ┌─────────────────────────────────┐    │
│  │ Security Consultant             │    │
│  │ Synopsys Pvt Ltd               │    │
│  └─────────────────────────────────┘    │
│           │                             │
│           ● (Timeline dot)              │
└─────────────────────────────────────────┘
```

#### 4. **Featured Projects** (Card Grid)
```
┌─────────────────────────────────────────┐
│  H2: Featured Research & Projects       │
│  ──────────────────────────             │
│                                         │
│  ┌──────┐  ┌──────┐  ┌──────┐          │
│  │Card 1│  │Card 2│  │Card 3│          │
│  │      │  │      │  │      │          │
│  │[IMG] │  │[IMG] │  │[IMG] │          │
│  │Title │  │Title │  │Title │          │
│  │Desc  │  │Desc  │  │Desc  │          │
│  │[Link]│  │[Link]│  │[Link]│          │
│  └──────┘  └──────┘  └──────┘          │
│                                         │
│  Hover: Card lifts with glow effect     │
└─────────────────────────────────────────┘
```

#### 5. **Skills Cloud** (Categorized Pills)
```
┌─────────────────────────────────────────┐
│  H2: Technical Arsenal                  │
│  ────────────────                       │
│                                         │
│  H3: AI & Cloud Security                │
│  [AWS] [LLM Security] [Prompt Inject]   │
│  [Cloud Computing] [MCP Vulnerabilities]│
│                                         │
│  H3: Application Security               │
│  [Burp Suite] [OWASP Top 10] [SAST]     │
│  [DAST] [SANS Top 25] [Web Security]    │
│                                         │
│  H3: Compliance & Privacy               │
│  [HIPAA] [GDPR] [PCI DSS]               │
│                                         │
│  Pills: Rounded, glowing border on hover│
└─────────────────────────────────────────┘
```

#### 6. **Awards & Certifications** (Badge Grid)
```
┌─────────────────────────────────────────┐
│  H2: Recognition & Certifications       │
│  ──────────────────────────             │
│                                         │
│  ┌─────┐ ┌─────┐ ┌─────┐ ┌─────┐       │
│  │ 🏆  │ │ 🎯  │ │ ☁️  │ │ 🔒  │       │
│  │Google│ │Amazon│ │AWS  │ │CompT│       │
│  │Bug  │ │AppSec│ │Cloud│ │IA+  │       │
│  │Hunter│ │ CTF │ │Cert │ │     │       │
│  └─────┘ └─────┘ └─────┘ └─────┘       │
│                                         │
│  Shimmer effect on load                 │
└─────────────────────────────────────────┘
```

#### 7. **Footer**
```
┌─────────────────────────────────────────┐
│  "Securing the Future, One Exploit      │
│   at a Time"                            │
│                                         │
│  Based in Indiana, US                   │
│  harshakshit.bit@gmail.com              │
│                                         │
│  [LinkedIn] [GitHub] [Medium]           │
│                                         │
│  © 2025 Harsh Akshit                    │
│  All Rights Reserved                    │
└─────────────────────────────────────────┘
```

---

## 🎭 Visual Effects & Interactions

### Animations
- **Page Load**: Fade-in with upward slide (0.5s ease-out)
- **Section Scroll**: Parallax effect on background elements
- **Cards**: Lift on hover (translateY(-8px) + shadow increase)
- **Buttons**: Neon glow pulse on hover
- **Timeline**: Dots pulse when in viewport
- **Skills Pills**: Shimmer effect on hover

### Micro-interactions
- **CTA Buttons**: Ripple effect on click
- **Links**: Underline slide-in from left
- **Code Elements**: Typing cursor blink effect
- **Social Icons**: Rotate + scale on hover
- **Cards**: Border glow animation on hover

### Accessibility
- Focus indicators with Cyber Cyan outline
- ARIA labels for all interactive elements
- Keyboard navigation support
- High contrast ratios (WCAG AAA compliant)
- Reduced motion support via prefers-reduced-motion

---

## 🔧 Technical Implementation Notes

### Performance
- Lazy load images below the fold
- CSS Grid for layouts (no heavy JS frameworks initially)
- Tailwind CSS for utility-first styling
- SVG icons for crisp rendering
- Web font optimization (preload critical fonts)

### Responsiveness
- Mobile-first approach
- Fluid typography (clamp() for scalable text)
- Flexible grid systems
- Touch-friendly tap targets (min 44x44px)

### Browser Support
- Modern evergreen browsers
- CSS Grid and Flexbox
- CSS Custom Properties
- Progressive enhancement approach

---

## 📊 Content Hierarchy

### Information Architecture
1. **Primary Goal**: Establish expertise in AI Security & AppSec
2. **Secondary Goal**: Showcase hands-on experience and research
3. **Tertiary Goal**: Build trust through certifications and community involvement

### Call-to-Actions Priority
1. "View Research" (Primary) - Links to publications
2. "Contact Me" (Primary) - Email or contact form
3. Social links (Secondary) - LinkedIn, GitHub, Medium
4. "Download Resume" (Tertiary) - PDF download

---

This design system ensures a cohesive, professional, and authoritative presence that immediately communicates Harsh's specialization in AI Security and Application Security while maintaining excellent usability and accessibility.
