# Rhodri Mativo Landing Page

landing page built with Next.js, TypeScript, styled-components, and Storybook, featuring the Catppuccin Macchiato color scheme.

![Front Page](public/front-page.svg)

## 🚀 Features

- **Modern Tech Stack**: Next.js 15 with App Router, TypeScript, styled-components
- **Beautiful Design**: Catppuccin Macchiato theme with gradient text and glow effects
- **Theme Toggle**: Switch between Catppuccin Latte (light) and Macchiato (dark) themes
- **Social Links**: LinkedIn, GitHub, and external website icons
- **Component Library**: Storybook for component development and documentation
- **Responsive**: Fully responsive design that works on all devices
- **Accessible**: Proper ARIA labels and keyboard navigation

## 🛠️ Tech Stack

- **Framework**: Next.js 15 with App Router
- **Language**: TypeScript
- **Styling**: styled-components
- **Icons**: react-icons
- **Package Manager**: pnpm
- **Component Development**: Storybook
- **Theme**: Catppuccin Macchiato & Latte

## 🎨 Design System

The project uses the beautiful Catppuccin Macchiato color palette with semantic color mappings for consistent theming throughout the application.

## 📦 Getting Started

First, install dependencies using pnpm:

```bash
pnpm install
```

Then, run the development server:

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the landing page.

## 📖 Storybook

To run Storybook for component development:

```bash
pnpm run storybook
```

Open [http://localhost:6006](http://localhost:6006) to view the component library.

## 🏗️ Project Structure

```
src/
├── app/                    # Next.js App Router
│   ├── layout.tsx         # Root layout with theme provider and favicon
│   └── page.tsx           # Main landing page with theme toggle
├── components/            # React components
│   ├── LandingPage.tsx    # Main landing page component
│   ├── SocialIcons.tsx    # Social media icons component
│   ├── ThemeToggle.tsx    # Theme toggle button component
│   └── *.stories.tsx      # Storybook stories
├── providers/             # React providers
│   ├── ThemeProvider.tsx  # Theme context and state management
│   ├── StyledComponentsProvider.tsx
│   └── GlobalStyles.tsx   # Global CSS styles
├── styles/
│   ├── theme.ts           # Catppuccin themes (Macchiato & Latte)
│   └── styled.d.ts        # styled-components type definitions
└── public/
    ├── favicon.svg        # Custom developer-themed favicon
    └── favicon-16x16.svg  # Smaller favicon for clarity
```

## 🎯 Customization


### Customizing Colors

The theme is defined in `src/styles/theme.ts`. You can modify colors while maintaining the Catppuccin Macchiato aesthetic.

## 🧪 Development Commands

- `pnpm dev` - Start Next.js development server
- `pnpm build` - Build for production
- `pnpm start` - Start production server
- `pnpm run storybook` - Start Storybook
- `pnpm run build-storybook` - Build Storybook
- `pnpm lint` - Run ESLint

## 🌟 Components

### LandingPage
The main landing page component with gradient title, subtitle, and social icons.

### SocialIcons
Animated social media icons with hover effects for LinkedIn, GitHub, and external links.

### ThemeToggle
Interactive theme toggle button with sun/moon icons for switching between Catppuccin Latte (light) and Macchiato (dark) themes. Includes localStorage persistence for user preference.

## 📱 Responsive Design

The landing page is fully responsive with breakpoints for:
- Mobile: < 640px
- Tablet: 640px - 1024px
- Desktop: > 1024px
