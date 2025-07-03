# 🏗️ Project Structure & Code Splitting Guide

*How to get properly structured, maintainable projects from Claude instead of giant single files*

---

## 🎯 The Problem

Claude often creates massive single files with everything crammed together. This guide shows you how to request proper project architecture with clean code splitting.

## 🚀 The Project Setup Formula

```
"Set up a Next.js 14 project with proper code splitting and component architecture.

Structure:
- /components/ui/ - shadcn/ui components (Button, Card, etc.)
- /components/layout/ - Layout components (Header, Sidebar, Footer)
- /components/features/ - Feature-specific components
- /lib/ - Utilities, constants, types
- /app/ - Pages and API routes
- /styles/ - Global styles and theme variables

Use our [PALETTE NAME] theming system with:
- CSS variables in globals.css
- Tailwind config integration
- Component-based architecture
- Proper imports/exports

Break everything into small, reusable components. No giant single files!"
```

---

## 📁 Request Templates by Project Size

### 🏃‍♂️ Small Project (Landing Page)

```
"Create a SaaS landing page with proper file structure:

- /components/sections/Hero.tsx
- /components/sections/Features.tsx  
- /components/sections/Pricing.tsx
- /components/ui/Button.tsx
- /components/ui/Card.tsx
- /lib/constants.ts
- /app/page.tsx

Use Forest Night theme with clean component separation."
```

**Perfect for:** Landing pages, portfolios, simple marketing sites

### 🏢 Medium Project (Dashboard)

```
"Build a dashboard with professional file structure:

/components/
├── layout/
│   ├── Sidebar.tsx
│   ├── Header.tsx
│   └── DashboardLayout.tsx
├── features/
│   ├── analytics/
│   │   ├── StatsGrid.tsx
│   │   ├── ChartCard.tsx
│   │   └── MetricsCard.tsx
│   ├── users/
│   │   ├── UserList.tsx
│   │   └── UserCard.tsx
├── ui/
│   ├── Button.tsx
│   ├── Card.tsx
│   └── Badge.tsx
/lib/
├── types.ts
├── constants.ts
└── utils.ts

Each component should be focused and reusable. Show folder structure first, then create components one by one."
```

**Perfect for:** Admin panels, dashboards, SaaS applications

### 🏗️ Large Project (Full App)

```
"Build a full social media app with enterprise-level structure:

Show me the complete folder architecture first, then we'll build:
1. Project structure with all folders
2. Core components (Button, Card, Input, etc.)
3. Layout components (Navigation, Sidebar)
4. Feature modules (Posts, Users, Analytics)
5. Pages that compose everything together
6. Utilities and types

Use Ocean Depth theme. Focus on maintainability and scalability."
```

**Perfect for:** Complex applications, multi-feature platforms, enterprise projects

---

## 🎯 Component-First Approach

### When You Want Specific Components

```
"Create just the [COMPONENT NAME] component for my project:

- File: /components/ui/PricingCard.tsx
- Props interface with TypeScript
- Uses our CSS variables
- Responsive design
- Proper exports

Keep it focused and reusable - no other components in this file."
```

### Building Individual Features

```
"Create the user management feature with proper structure:

/components/features/users/
├── UserList.tsx - Main list component
├── UserCard.tsx - Individual user card
├── UserModal.tsx - Edit/view modal
├── UserFilters.tsx - Search and filters
└── index.ts - Clean exports

Each component should have a single responsibility."
```

---

## 📋 Magic Phrases for Better Structure

### **For Structure:**
- "Show folder structure first"
- "Break into small components"  
- "Proper code splitting"
- "One component per file"
- "Clean imports/exports"

### **For Maintenance:**
- "Make it maintainable"
- "Reusable components"
- "Focused responsibilities"
- "Enterprise-level structure"

### **For Step-by-Step Building:**
- "Don't write code yet, show structure first"
- "Build each component separately"
- "Start with the architecture"
- "Component-based approach"

---

## 🛠️ Step-by-Step Building Process

### Method 1: Architecture First

```
"Let's build this project step by step:

Step 1: Show me the folder structure
Step 2: Create the core UI components
Step 3: Build layout components  
Step 4: Create feature components
Step 5: Compose the main page

Start with just the folder structure - don't write any code yet."
```

### Method 2: Feature-Driven

```
"I want to build [PROJECT TYPE] with these features:
- [Feature 1]
- [Feature 2] 
- [Feature 3]

Show me:
1. How to organize these features in folders
2. What components each feature needs
3. Shared components we can reuse
4. Order to build them in

Then we'll create each feature module separately."
```

### Method 3: Component Library First

```
"Let's build a component library first, then compose the app:

Phase 1: Core UI components (Button, Card, Input, Modal)
Phase 2: Layout components (Header, Sidebar, Footer)
Phase 3: Feature-specific components
Phase 4: Pages that use everything

Create each component as a separate file with proper TypeScript interfaces."
```

---

## 📂 Recommended Folder Structure

### Standard Next.js 14 Structure

```
my-project/
├── app/
│   ├── globals.css
│   ├── layout.tsx
│   ├── page.tsx
│   └── (dashboard)/
│       ├── analytics/
│       ├── users/
│       └── settings/
├── components/
│   ├── ui/
│   │   ├── button.tsx
│   │   ├── card.tsx
│   │   ├── input.tsx
│   │   └── modal.tsx
│   ├── layout/
│   │   ├── header.tsx
│   │   ├── sidebar.tsx
│   │   └── footer.tsx
│   ├── features/
│   │   ├── auth/
│   │   ├── dashboard/
│   │   └── users/
│   └── sections/
│       ├── hero.tsx
│       ├── features.tsx
│       └── pricing.tsx
├── lib/
│   ├── utils.ts
│   ├── constants.ts
│   ├── types.ts
│   └── validations.ts
├── hooks/
│   ├── use-local-storage.ts
│   └── use-debounce.ts
├── styles/
│   └── components.css
└── public/
    └── images/
```

### Enterprise-Level Structure

```
my-enterprise-app/
├── app/
├── components/
│   ├── ui/           # Base components
│   ├── layout/       # Layout components  
│   ├── forms/        # Form components
│   └── features/     # Feature modules
│       ├── auth/
│       │   ├── components/
│       │   ├── hooks/
│       │   └── types.ts
│       ├── dashboard/
│       └── users/
├── lib/
│   ├── api/          # API layer
│   ├── auth/         # Authentication
│   ├── utils/        # Utilities
│   └── validations/  # Zod schemas
├── hooks/            # Shared hooks
├── types/            # Global types
├── constants/        # App constants
└── styles/           # Global styles
```

---

## 💡 Pro Tips

### 1. Always Ask for Structure First
```
"Before writing any code, show me the complete folder structure for this project."
```

### 2. Specify File Responsibilities
```
"Each component should have a single responsibility:
- Button.tsx handles only button logic
- Modal.tsx handles only modal behavior  
- UserCard.tsx handles only user display"
```

### 3. Request Clean Exports
```
"Create proper index.ts files for clean imports:
- /components/ui/index.ts exports all UI components
- /components/features/users/index.ts exports user components"
```

### 4. Enforce Component Limits
```
"Keep components under 100 lines. If bigger, break into smaller pieces."
```

### 5. Ask for TypeScript Interfaces
```
"Create proper TypeScript interfaces for all props and data structures."
```

---

## 🚫 What NOT to Ask For

### ❌ Avoid These Requests:
- "Create a complete dashboard" (too vague, will get huge files)
- "Build everything in one file" 
- "Make it work first, structure later"
- "Just get it done quickly"

### ✅ Ask for This Instead:
- "Create a dashboard with proper component structure"
- "Break this into maintainable pieces"
- "Show me the architecture before coding"
- "Build it the professional way"

---

## 🎯 Example: Refactoring Request

If Claude gives you a huge single file:

```
"This component is too large. Please refactor it with proper structure:

Break this into:
- /components/layout/DashboardLayout.tsx
- /components/features/analytics/StatsGrid.tsx  
- /components/features/analytics/ChartCard.tsx
- /components/ui/StatCard.tsx

Each component should be in its own file with proper exports."
```

---

## 🔄 Iterative Development

### Perfect Development Flow:

1. **Architecture Phase:**
   ```
   "Show me the folder structure for this project"
   ```

2. **Component Planning:**
   ```
   "List all components we need and their responsibilities"
   ```

3. **UI Foundation:**
   ```
   "Create the core UI components first (Button, Card, Input)"
   ```

4. **Layout Building:**
   ```
   "Build the layout components (Header, Sidebar, Footer)"
   ```

5. **Feature Development:**
   ```
   "Create the [feature name] module with its components"
   ```

6. **Page Composition:**
   ```
   "Compose the main page using all our components"
   ```

---

## 🎨 Integration with Design System

```
"Use our [PALETTE NAME] theming system throughout:

- All components use CSS variables
- Consistent glassmorphism effects
- Proper contrast ratios
- Responsive design patterns
- Reusable utility classes

Maintain design consistency across all components."
```

---

**Remember:** Good architecture takes time upfront but saves hours of refactoring later. Always invest in proper structure from the beginning!