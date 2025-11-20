# AAFC Landing Page Design Guidelines

## Design Approach
**Reference-Based Approach** - Drawing inspiration from social impact and nonprofit organizations like charity: water, TOMS, and Patagonia's mission-driven aesthetics. This landing page serves an experience-focused purpose where emotional connection and visual storytelling drive engagement for social change.

## Core Design Principles
1. **Mission-First Visual Hierarchy** - Lead with impact and purpose
2. **Authentic Representation** - Showcase real artists and athletes
3. **Trust & Credibility** - Professional polish balanced with grassroots energy
4. **Action-Oriented** - Clear pathways to engagement and involvement

---

## Typography

**Font Families:**
- Primary: Inter or DM Sans (modern, professional, highly readable)
- Accent: Space Grotesk or Archivo (bold, impactful for headlines)

**Hierarchy:**
- Hero Headline: 3.5rem - 4.5rem (font-bold, tracking-tight)
- Section Headlines: 2.5rem - 3rem (font-bold)
- Subsection Titles: 1.5rem - 2rem (font-semibold)
- Body Text: 1rem - 1.125rem (font-normal, leading-relaxed)
- Button Text: 1rem (font-semibold, uppercase tracking)

---

## Layout System

**Spacing Primitives:**
Use Tailwind units of **4, 8, 12, 16, 20, 24** for consistent vertical rhythm.
- Section padding: `py-20` desktop, `py-12` mobile
- Component spacing: `gap-8` for grids, `space-y-4` for stacked content
- Container margins: `px-4` mobile, `px-8` tablet, `px-12` desktop

**Container Strategy:**
- Max-width: `max-w-7xl` for full sections, `max-w-4xl` for content blocks
- Center alignment: `mx-auto` throughout

---

## Page Structure & Components

### 1. Navigation
**Sticky Header** with transparent-to-solid transition on scroll
- Logo left-aligned
- Navigation links: About, Programs, Impact, Get Involved
- Primary CTA button: "Donate" or "Join Us" (right-aligned)
- Mobile: Hamburger menu

### 2. Hero Section (Full viewport impact)
**Layout:** Split design with 60/40 text-to-visual ratio
- Left: Headline + subheadline + dual CTAs
- Right: Dynamic imagery showcasing artists/athletes in action
- Height: `min-h-screen` with centered content
- Gradient overlay on image for text contrast
- Primary CTA: Blurred background button ("Get Involved")
- Secondary CTA: Ghost/outline button ("Learn More")

### 3. Mission Statement Section
**Full-width centered content**
- Large impactful quote or mission statement
- Supporting paragraph (max-w-3xl centered)
- Statistical highlights in 3-column grid (desktop) showing impact metrics
- Spacing: `py-24`

### 4. Programs Showcase
**Card-based grid layout**
- 3-column grid (desktop), 1-column (mobile): `grid-cols-1 md:grid-cols-3`
- Each card includes: Icon/image, program name, 2-3 line description, "Learn More" link
- Hover states: Subtle lift effect and border highlight
- Programs could include: Youth Empowerment, Community Art, Athlete Mentorship, Advocacy Initiatives

### 5. Impact Section
**Visual storytelling with data**
- Large statistics display: 4-column grid of key metrics
- Before/after stories or testimonials in 2-column layout
- Photo gallery grid showcasing real impact (masonry or equal-height cards)
- Include: People reached, Programs launched, Communities served, Funds raised

### 6. Featured Stories/Testimonials
**Alternating layout for depth**
- Staggered image-text blocks (image left, then right, then left)
- Each block: Large quote, person's name/role, supporting image
- 2-3 featured stories maximum

### 7. Call-to-Action Section
**High-contrast, centered engagement block**
- Bold headline prompting action
- 2-3 action cards in row: "Volunteer", "Donate", "Partner"
- Each card: Icon, title, brief description, CTA button
- Background treatment for visual separation from surrounding content

### 8. Footer
**Comprehensive information hub**
- 4-column layout: About AAFC, Quick Links, Programs, Connect
- Newsletter signup with inline form
- Social media icons
- Contact information and physical address
- Legal links: Privacy Policy, Terms of Service
- Copyright notice

---

## Component Library

**Buttons:**
- Primary: Solid fill with semibold text
- Secondary: Outline style with transparent background
- On-image: Backdrop blur effect `backdrop-blur-md` with semi-transparent background

**Cards:**
- Rounded corners: `rounded-xl`
- Shadow: `shadow-lg` with hover `shadow-xl`
- Padding: `p-8`
- Border: Subtle 1px accent on hover

**Forms:**
- Input fields: `rounded-lg`, generous padding `py-3 px-4`
- Labels: Uppercase, small tracking, positioned above inputs
- Focus states: Accent color ring

**Icons:**
Use **Heroicons** via CDN for consistency

---

## Images

**Hero Section:**
- Large hero image: High-quality photo of artists/athletes collaborating or in action (community event, performance, training)
- Dimensions: 1920x1080 minimum
- Placement: Right side of hero (40% width) or full-width background with overlay

**Programs Section:**
- 3 supporting images: Each representing a program category
- Dimensions: 600x400 landscape orientation
- Content: Real participants in programs, diverse representation

**Impact Section:**
- Photo gallery: 6-8 images in masonry or grid layout
- Dimensions: Various (square and landscape)
- Content: Events, success stories, community gatherings, before/after transformations

**Testimonial Section:**
- 2-3 portrait images of featured individuals
- Dimensions: 800x800 square
- Content: High-quality headshots with authentic expressions

**General Image Treatment:**
- Maintain consistent aspect ratios within sections
- Apply subtle overlays where text overlaps images
- Ensure all images show diverse representation of artists and athletes

---

## Animations
**Minimal, purposeful motion:**
- Scroll-triggered fade-ins for section reveals (once per page load)
- Stat counter animations when Impact section enters viewport
- Smooth scroll behavior for anchor links
- No parallax, no continuous animations

This design creates an emotionally engaging, professional landing page that effectively communicates AAFC's mission while driving user action through clear visual hierarchy and strategic calls-to-action.