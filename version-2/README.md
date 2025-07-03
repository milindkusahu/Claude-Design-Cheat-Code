# 🎨 Claude Design Cheat Code v2.0 - ULTIMATE EDITION

## 🚀 Next.js Project Setup Formula

```
"Create a Next.js 14 project with Tailwind CSS and shadcn/ui setup. 

Set up a custom theming system using CSS variables for the [PALETTE NAME] 
color scheme:

Configure:
1. Custom CSS variables in globals.css for all colors
2. Tailwind config to use these variables  
3. shadcn/ui theme configuration with custom variants
4. Utility classes (.glass-card, .gradient-primary, .text-gradient)
5. A demo page showing all theme colors and components

Make it so I can use classes like 'bg-primary', 'text-secondary', 
'glass-card' instead of hardcoding colors everywhere."
```

## 🔥 The Magic Design Formula

```
"Create a [PROJECT TYPE] that looks like it belongs on Awwwards/Dribbble. 

**Visual Style:**
- [AESTHETIC CHOICE]: Modern/Minimalist/Bold/Futuristic/Elegant
- [COLOR PALETTE]: Use [PALETTE NAME] from our theming system
- [DESIGN TREND]: Glassmorphism/Neumorphism/Gradient backgrounds/Floating elements/Bento grids

**Make it premium enough that I'd screenshot and share it. Add:**
- Smooth hover animations and micro-interactions
- Bold typography with proper hierarchy  
- Perfect spacing and visual flow
- High contrast and accessibility
- Current 2024/2025 design trends

**Reference sites:** [PASTE URLS OR SAY: "Think Stripe/Linear/Framer quality"]

Use our CSS variables and utility classes - no hardcoded colors!
Don't make it functional but boring - make it STUNNING."
```

## 🎯 Component Theming Formula

```
"Take the shadcn/ui [COMPONENT NAME] and integrate it with our [PALETTE NAME] 
theming system.

Style it with:
- CSS variables from our theme
- Glassmorphism effects using .glass-card
- Gradient variants using .gradient-primary/.gradient-accent
- Proper hover states and animations
- Consistent with our design system

Make it look premium and modern, not just functional."
```

---

## 🎯 Quick Design Styles

### **Dark & Premium**
```
"Dark gradient background (slate-900 to purple-900), glassmorphism cards, 
purple/pink accent gradients, bold white typography"
```

### **Clean & Modern** 
```
"Light background, subtle shadows, blue/green accents, 
plenty of whitespace, clean sans-serif fonts"
```

### **Bold & Vibrant**
```
"Bright gradient backgrounds, high contrast colors, 
oversized typography, neon accents, playful animations"
```

### **Minimal & Elegant**
```
"Neutral backgrounds, single accent color, 
refined typography, subtle interactions, premium spacing"
```

---

## 🎨 Premium Color Palettes - CSS Variables Ready

### **Dark Mode Palettes**

**Purple Dream (Dark)**
```css
:root {
  --background: 15 23 42; /* slate-900 */
  --background-gradient-to: 88 28 135; /* purple-800 */
  --primary: 147 51 234; /* purple-500 */
  --secondary: 236 72 153; /* pink-500 */
  --accent: 168 85 247; /* purple-400 */
  --text-primary: 255 255 255; /* white */
  --text-secondary: 196 181 253; /* purple-200 */
  --text-muted: 148 163 184; /* slate-400 */
  --border: 147 51 234; /* purple-500 with opacity */
}
```

**Ocean Depth (Dark)**
```css
:root {
  --background: 15 23 42; /* slate-900 */
  --background-gradient-to: 30 58 138; /* blue-800 */
  --primary: 59 130 246; /* blue-500 */
  --secondary: 34 211 238; /* cyan-400 */
  --accent: 96 165 250; /* blue-400 */
  --text-primary: 255 255 255; /* white */
  --text-secondary: 147 197 253; /* blue-200 */
  --text-muted: 148 163 184; /* slate-400 */
  --border: 59 130 246; /* blue-500 with opacity */
}
```

**Forest Night (Dark)**
```css
:root {
  --background: 17 24 39; /* gray-900 */
  --background-gradient-to: 6 78 59; /* emerald-800 */
  --primary: 16 185 129; /* emerald-500 */
  --secondary: 45 212 191; /* teal-400 */
  --accent: 52 211 153; /* emerald-400 */
  --text-primary: 255 255 255; /* white */
  --text-secondary: 209 250 229; /* emerald-100 */
  --text-muted: 156 163 175; /* gray-400 */
  --border: 16 185 129; /* emerald-500 with opacity */
}
```

**Sunset Glow (Dark)**
```css
:root {
  --background: 15 23 42; /* slate-900 */
  --background-gradient-to: 154 52 18; /* orange-800 */
  --primary: 249 115 22; /* orange-500 */
  --secondary: 239 68 68; /* red-500 */
  --accent: 251 146 60; /* orange-400 */
  --text-primary: 255 255 255; /* white */
  --text-secondary: 254 215 170; /* orange-200 */
  --text-muted: 148 163 184; /* slate-400 */
  --border: 249 115 22; /* orange-500 with opacity */
}
```

### **Light Mode Palettes**

**Sky Fresh (Light)**
```css
.light {
  --background: 255 255 255; /* white */
  --background-gradient-to: 240 249 255; /* blue-50 */
  --primary: 37 99 235; /* blue-600 */
  --secondary: 79 70 229; /* indigo-600 */
  --accent: 59 130 246; /* blue-500 */
  --text-primary: 17 24 39; /* gray-900 */
  --text-secondary: 51 65 85; /* slate-700 */
  --text-muted: 100 116 139; /* slate-500 */
  --border: 37 99 235; /* blue-600 with opacity */
}
```

**Nature Clean (Light)**
```css
.light {
  --background: 255 255 255; /* white */
  --background-gradient-to: 240 253 244; /* green-50 */
  --primary: 22 163 74; /* green-600 */
  --secondary: 5 150 105; /* emerald-600 */
  --accent: 34 197 94; /* green-500 */
  --text-primary: 17 24 39; /* gray-900 */
  --text-secondary: 15 78 61; /* green-800 */
  --text-muted: 107 114 128; /* gray-500 */
  --border: 22 163 74; /* green-600 with opacity */
}
```

**Warm Professional (Light)**
```css
.light {
  --background: 255 255 255; /* white */
  --background-gradient-to: 255 251 235; /* amber-50 */
  --primary: 217 119 6; /* amber-600 */
  --secondary: 234 88 12; /* orange-600 */
  --accent: 245 158 11; /* amber-500 */
  --text-primary: 17 24 39; /* gray-900 */
  --text-secondary: 146 64 14; /* amber-800 */
  --text-muted: 107 114 128; /* gray-500 */
  --border: 217 119 6; /* amber-600 with opacity */
}
```

### **Light Mode Palettes**

**Sky Fresh**
- Background: `white` to `blue-50`
- Accents: `blue-600` to `indigo-600`
- Text: `gray-900` / `blue-800`

**Nature Clean**
- Background: `white` to `green-50`
- Accents: `green-600` to `emerald-600`
- Text: `gray-900` / `green-800`

**Warm Professional**
- Background: `white` to `amber-50`
- Accents: `amber-600` to `orange-600`
- Text: `gray-900` / `amber-800`

## ⚠️ CRITICAL: Contrast & Accessibility Rules

### **Text Contrast Guidelines:**
```
DARK MODE:
✅ text-text-primary (white) on dark backgrounds
✅ text-text-secondary (light colors) on dark backgrounds  
✅ text-text-muted (gray-400/slate-400) for less important text
❌ NEVER use dark text on dark backgrounds
❌ NEVER use text-text-secondary on light backgrounds

LIGHT MODE:
✅ text-text-primary (gray-900) on light backgrounds
✅ text-text-secondary (darker accent colors) on light backgrounds
✅ text-text-muted (gray-500) for less important text
❌ NEVER use light text on light backgrounds
❌ NEVER use white text on light backgrounds
```

### **Background Safety Rules:**
```
DARK MODE:
✅ Dark backgrounds (slate-900, gray-900) + Light text
✅ Glass cards (bg-white/5, bg-white/10) + Light text
❌ Light backgrounds + Light text = INVISIBLE

LIGHT MODE:
✅ Light backgrounds (white, gray-50) + Dark text
✅ Subtle tinted backgrounds (blue-50, green-50) + Dark text
❌ Dark backgrounds + Dark text = INVISIBLE
```

### **Button Contrast Rules:**
```
DARK MODE BUTTONS:
✅ Gradient backgrounds + white text
✅ Glass buttons (bg-white/10) + white text + light borders
❌ Dark buttons + dark text

LIGHT MODE BUTTONS:
✅ Solid color backgrounds + white text (if bg is dark enough)
✅ Outline buttons + dark text on light backgrounds
❌ Light buttons + white text
```

### **Testing Checklist:**
```
Before shipping ANY design:
☐ Can I read ALL text clearly?
☐ Do buttons have proper contrast?
☐ Are borders visible but not overwhelming?
☐ Does it work in both light AND dark mode?
☐ No invisible text anywhere?
```

### **For Bold Designs:**
- "Make it bold enough to stop someone mid-scroll"
- "Premium feel that screams quality"
- "Add visual wow factor with gradients and animations"

### **For Interactions:**
- "Smooth micro-interactions that make it feel alive"
- "Hover effects that surprise and delight"
- "Buttery smooth transitions"

### **For Layout:**
- "Perfect visual hierarchy and spacing"
- "Bento grid layout with floating cards"
- "Asymmetrical but balanced composition"

## 📸 Perfect Image Strategy for Landing Pages

### **🎯 Image Sources (Best to Worst):**

**1. High-Quality Free Sources:**
```
✅ Unsplash.com - Professional photos, great for heroes/backgrounds
✅ Pexels.com - Diverse stock photos, good quality
✅ Pixabay.com - Mix of photos and illustrations
✅ Freepik.com - Illustrations, icons, and graphics (credit required)
```

**2. AI-Generated (When You Need Specific Concepts):**
```
✅ Midjourney - Highest quality, paid
✅ DALL-E 3 - Good for specific concepts
✅ Leonardo.ai - Free tier available
```

**3. Placeholder Services (For Development):**
```
✅ Picsum.photos - Random beautiful photos
✅ Unsplash Source API - Themed photos
```

### **🚀 Optimized Image Implementation:**

**Next.js Image Component (ALWAYS USE THIS):**
```tsx
import Image from 'next/image'

// Hero Background
<div className="relative h-screen">
  <Image
    src="/hero-bg.jpg"
    alt="Hero background"
    fill
    className="object-cover object-center"
    priority
    quality={90}
  />
  <div className="relative z-10 glass-card">
    {/* Your content */}
  </div>
</div>

// Feature Images
<Image
  src="/feature-image.jpg"
  alt="Feature description"
  width={600}
  height={400}
  className="rounded-xl object-cover"
  loading="lazy"
/>

// Profile/Avatar Images
<Image
  src="/avatar.jpg"
  alt="User name"
  width={64}
  height={64}
  className="rounded-full object-cover"
/>
```

### **📐 Perfect Image Dimensions:**

```
Hero Sections: 1920x1080 (16:9) or 1600x900
Feature Cards: 600x400 (3:2) or 800x600  
Profile/Avatars: 400x400 (1:1) minimum
Blog Thumbnails: 800x450 (16:9)
Product Images: 800x800 (1:1) or 600x800 (3:4)
Background Patterns: 1920x1080 or seamless tiles
Icons: 64x64, 128x128, 256x256 (SVG preferred)
```

### **🎨 Image + Theme Integration:**

**Overlay Techniques:**
```tsx
// Dark overlay for text readability
<div className="relative">
  <Image src="/bg.jpg" alt="" fill className="object-cover" />
  <div className="absolute inset-0 bg-black/50" />
  <div className="relative z-10 text-white">Content</div>
</div>

// Gradient overlay matching theme
<div className="relative">
  <Image src="/bg.jpg" alt="" fill className="object-cover" />
  <div className="absolute inset-0 bg-gradient-to-r from-primary/80 to-secondary/80" />
  <div className="relative z-10 text-white">Content</div>
</div>

// Glassmorphism effect
<div className="relative">
  <Image src="/bg.jpg" alt="" fill className="object-cover blur-sm scale-110" />
  <div className="relative z-10 glass-card m-8">Content</div>
</div>
```

### **🔥 Pro Image Patterns:**

**1. Hero with Floating Cards:**
```tsx
<section className="relative h-screen overflow-hidden">
  <Image 
    src="https://images.unsplash.com/photo-1557804506-669a67965ba0?w=1920&h=1080&fit=crop"
    alt="Team collaboration"
    fill
    className="object-cover"
    priority
  />
  <div className="absolute inset-0 bg-gradient-to-r from-background/80 to-transparent" />
  <div className="relative z-10 flex items-center h-full">
    <div className="glass-card max-w-2xl mx-8">
      <h1 className="text-6xl font-bold text-gradient">Your Content</h1>
    </div>
  </div>
</section>
```

**2. Feature Grid with Images:**
```tsx
const features = [
  {
    title: "Fast Performance",
    image: "https://images.unsplash.com/photo-1551434678-e076c223a692?w=600&h=400&fit=crop",
    icon: <Zap />
  }
]

<div className="grid grid-cols-1 md:grid-cols-3 gap-8">
  {features.map((feature) => (
    <div className="glass-card-hover group">
      <div className="relative h-48 mb-6 overflow-hidden rounded-lg">
        <Image
          src={feature.image}
          alt={feature.title}
          fill
          className="object-cover group-hover:scale-110 transition-transform duration-500"
        />
        <div className="absolute inset-0 bg-gradient-to-t from-black/50 to-transparent" />
        <div className="absolute bottom-4 left-4">
          {feature.icon}
        </div>
      </div>
      <h3 className="text-xl font-bold text-text-primary">{feature.title}</h3>
    </div>
  ))}
</div>
```

### **📱 Responsive Image Classes:**

```css
/* Responsive image containers */
.hero-image {
  @apply relative h-[50vh] md:h-[70vh] lg:h-screen;
}

.feature-image {
  @apply relative h-48 md:h-56 lg:h-64;
}

.card-image {
  @apply relative h-32 md:h-40 lg:h-48;
}

/* Image effects */
.image-hover-zoom {
  @apply group-hover:scale-110 transition-transform duration-500;
}

.image-parallax {
  @apply transform-gpu transition-transform duration-1000;
}
```

### **Utility Classes to Use:**
```css
/* Cards & Containers */
.glass-card              /* Basic glassmorphism card */
.glass-card-hover        /* Glassmorphism with hover effects */

/* Gradients */
.gradient-primary        /* Primary to secondary gradient */
.gradient-accent         /* Accent gradient */
.text-gradient          /* Gradient text effect */

/* Buttons */
.btn-primary            /* Primary gradient button */
.btn-secondary          /* Secondary glass button */

/* Colors */
bg-primary              /* Uses CSS variable --primary */
bg-secondary            /* Uses CSS variable --secondary */
bg-accent               /* Uses CSS variable --accent */
text-text-primary       /* Uses CSS variable --text-primary */
text-text-secondary     /* Uses CSS variable --text-secondary */
text-text-accent        /* Uses CSS variable --text-accent */
border-border           /* Uses CSS variable --border */
```

### **shadcn/ui Button Variants:**
```tsx
<Button variant="default">    {/* Primary gradient */}
<Button variant="secondary">  {/* Glass effect */}
<Button variant="accent">     {/* Accent gradient */}
<Button variant="success">    {/* Success color */}
<Button variant="warning">    {/* Warning color */}
<Button variant="error">      {/* Error color */}
```

### **🎯 Perfect Image Request Formula:**

```
"Add high-quality images throughout using Next.js Image component:

- Hero: Professional team/office photo from Unsplash with gradient overlay
- Features: Relevant concept images (600x400) with hover zoom effects  
- Testimonials: Professional headshots (circular, 64x64)
- Background: Subtle pattern or gradient, not distracting
- All images: Optimized, responsive, with proper alt text

Use glassmorphism overlays and ensure images complement our [PALETTE] theme.
No placeholder rectangles - use actual Unsplash URLs."
```

### **📋 Quick Copy-Paste Unsplash URLs:**

**Tech/SaaS Theme:**
```
Hero Backgrounds:
- https://images.unsplash.com/photo-1557804506-669a67965ba0?w=1920&h=1080&fit=crop (team meeting)
- https://images.unsplash.com/photo-1560472354-b33ff0c44a43?w=1920&h=1080&fit=crop (modern office)

Feature Images:
- https://images.unsplash.com/photo-1551434678-e076c223a692?w=600&h=400&fit=crop (analytics)
- https://images.unsplash.com/photo-1563986768609-322da13575f3?w=600&h=400&fit=crop (security)
- https://images.unsplash.com/photo-1460925895917-afdab827c52f?w=600&h=400&fit=crop (development)

Avatars/Testimonials:
- https://images.unsplash.com/photo-1494790108755-2616b612b786?w=400&h=400&fit=crop&crop=face
- https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=400&h=400&fit=crop&crop=face
```

### **🚨 Image Optimization Checklist:**

```
Before Using Any Image:
☐ Using Next.js Image component (not <img>)
☐ Proper width/height or fill prop
☐ Descriptive alt text
☐ priority={true} for above-fold images
☐ loading="lazy" for below-fold images
☐ object-cover for consistent aspect ratios
☐ Responsive classes (h-48 md:h-56 lg:h-64)
☐ Hover effects for interactivity
☐ Overlay if text is on top
☐ Quality set to 80-90 for web optimization
```

**Modern:** Glassmorphism, backdrop-blur, floating elements, subtle shadows
**Bold:** Vibrant gradients, high contrast, oversized typography, neon accents
**Minimal:** Whitespace, single accent color, clean lines, refined typography
**Premium:** Dark themes, gold/purple accents, luxurious spacing, smooth animations
**Playful:** Bright colors, rounded corners, bouncy animations, fun illustrations

---

## 🚀 Copy-Paste Color Classes

### **Gradients:**
```css
/* Purple Magic */
bg-gradient-to-r from-purple-600 to-pink-600
bg-gradient-to-br from-slate-900 via-purple-900 to-slate-900

/* Ocean Vibes */
bg-gradient-to-r from-blue-600 to-cyan-600
bg-gradient-to-br from-slate-900 via-blue-900 to-slate-900

/* Forest Energy */
bg-gradient-to-r from-emerald-600 to-teal-600
bg-gradient-to-br from-gray-900 via-emerald-900 to-gray-900

/* Sunset Power */
bg-gradient-to-r from-orange-500 to-red-500
bg-gradient-to-br from-slate-900 via-orange-900 to-slate-900
```

### **Text Colors:**
```css
/* Gradient Text */
text-transparent bg-clip-text bg-gradient-to-r from-purple-400 to-pink-400
text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-cyan-400

/* Standard Colors */
text-white text-gray-300 text-gray-400
text-purple-400 text-blue-400 text-emerald-400
```

---

## 💡 Pro Tips

1. **Always mention specific reference sites** (Stripe, Linear, Framer, etc.)
2. **Ask for multiple variations** ("Show me 3 different approaches")
3. **Be specific about interactions** ("Add hover effects that...")
4. **Mention the emotional goal** ("Make users want to screenshot this")
5. **Push for boldness** ("Don't be safe, be stunning")

---

## 🎯 Example Perfect Requests

### **Project Setup:**
```
"Set up Next.js 14 with Forest Night theming system. Include all CSS 
variables, Tailwind config, shadcn/ui integration, and utility classes."
```

### **New Component:**
```
"Create a pricing section using Ocean Depth palette. Make it bold enough 
that I'd want to screenshot and share it. Use glassmorphism cards, 
gradient buttons, and smooth hover animations. Reference Stripe's pricing 
but make it more visually striking."
```

### **Theme a Component:**
```
"Take the shadcn Dialog component and style it with Purple Dream theme. 
Add glassmorphism backdrop, gradient borders, smooth animations, and 
make it feel premium. No hardcoded colors - use our CSS variables."
```

### **Full Application:**
```
"Build a SaaS dashboard using Sunset Glow palette. Make it Awwwards-quality 
with floating cards, smooth micro-interactions, gradient accents, and 
bold typography. Think Linear's dashboard but with warmer colors."
```

---

**Remember:** The key is being specific about the vibe, referencing quality sites, and pushing for visual excellence over just functionality!