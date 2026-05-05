# Portfolio Website Specification

## Project Overview
- **Project Name**: Pughalvanan C - UI/UX Designer Portfolio
- **Type**: Single-page portfolio website
- **Core Functionality**: Showcase UI/UX design skills, projects, and design vision with modern futuristic UI
- **Target Users**: Recruiters, design agencies, potential employers, collaborators

## UI/UX Specification

### Layout Structure
- Single-page scrollable layout
- Sections: Hero, About, Skills, Projects, Startup Vision, Contact, Footer
- Max content width: 1280px, centered

### Responsive Breakpoints
- Mobile: < 640px
- Tablet: 640px - 1024px
- Desktop: > 1024px

### Visual Design

#### Color Palette
- **Background Primary**: #0a0a0f (deep space black)
- **Background Secondary**: #12121a (dark navy)
- **Background Card**: rgba(255, 255, 255, 0.03) (glassmorphism base)
- **Neon Purple**: #a855f7
- **Neon Blue**: #3b82f6
- **Neon Pink**: #ec4899
- **Neon Cyan**: #06b6d4
- **Text Primary**: #ffffff
- **Text Secondary**: #94a3b8
- **Border Glow**: rgba(168, 85, 247, 0.3)

#### Typography
- **Font Family**: "Outfit" (headings), "DM Sans" (body)
- **Hero Name**: 72px / 48px mobile
- **Hero Title**: 32px / 24px mobile
- **Section Headings**: 48px / 32px mobile
- **Body Text**: 16px-18px
- **Font Weights**: 300 (light), 400 (regular), 600 (semibold), 700 (bold)

#### Spacing System
- Section padding: 100px vertical / 60px mobile
- Card padding: 32px
- Component gaps: 24px
- Button padding: 16px 32px

### Visual Effects
- **Glassmorphism**: backdrop-blur-xl, bg-opacity, border gradients
- **Glow Effects**: box-shadow with neon colors, gradient borders
- **Background**: Animated gradient orbs, subtle particle effect
- **Animations**: Fade-in-up on scroll, hover scale/glow, gradient shifts

### Components

#### Hero Section
- Full viewport height
- Animated gradient orbs in background (3-4 orbs, slowly moving)
- Name in large gradient text
- Title with typewriter or fade effect
- Three CTA buttons with glow hover effect
- Floating UI cards (decorative) with glassmorphism

#### About Section
- Centered text block
- Glassmorphism card background

#### Skills Section
- Three categories: Programming, Tools, Concepts
- Each skill as glowing card with icon
- Hover: scale up, increased glow
- Staggered animation on scroll

#### Projects Section
- Grid: 3 columns desktop, 2 tablet, 1 mobile
- Glassmorphism cards
- Project name, description, tech stack tags
- Hover: lift effect, border glow intensifies

#### Startup Vision Section
- Centered layout
- Gradient text heading
- Text in glassmorphism card

#### Contact Section
- Two columns: form + info (desktop)
- Form: Name, Email, Message inputs with glassmorphism style
- Submit button with gradient glow
- Social links with icon hover effects

#### Footer
- Minimal, centered
- Social icons only (GitHub, LinkedIn)

## Functionality Specification

### Core Features
- Smooth scroll navigation
- Scroll-triggered animations (fade in)
- Interactive hover states on all clickable elements
- Responsive layout adaptation
- Contact form with visual feedback (no backend)

### User Interactions
- Scroll to navigate sections
- Click CTA buttons (scroll to projects/contact, open GitHub link)
- Hover effects on all interactive elements
- Form input focus states

### Animations
- Hero gradient orbs: continuous slow movement (CSS)
- Scroll reveal: elements fade in from bottom
- Button hover: glow intensifies, slight scale
- Card hover: lift and glow
- Skill cards: staggered fade in

## Acceptance Criteria
- [ ] Page loads with animated hero background
- [ ] All sections render correctly on desktop, tablet, mobile
- [ ] Smooth scrolling works between sections
- [ ] Hover effects work on buttons and cards
- [ ] Skills display in three categories with glowing cards
- [ ] Three projects display with glassmorphism cards
- [ ] Contact form inputs are functional (visual only)
- [ ] No console errors on load
- [ ] Fonts load correctly (Outfit, DM Sans)
