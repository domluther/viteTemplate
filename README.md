
# Vite + React 19 + TypeScript Template

This template provides a modern setup for building React applications with Vite, TypeScript, and Tailwind CSS. It includes fast refresh, advanced routing, linting, formatting, and utility libraries for rapid development.

## Features

- **React 19** & **React DOM**
- **TypeScript**
- **Vite** (with [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) for fast refresh)
- **Tailwind CSS** (with [@tailwindcss/vite](https://github.com/privatenumber/tailwindcss-vite), [tailwind-merge](https://github.com/dcastil/tailwind-merge), and [tw-animate-css](https://github.com/rohit-gohri/tw-animate-css))
- **TanStack React Router** ([react-router](https://tanstack.com/router/v1), [devtools](https://tanstack.com/router/v1/docs/devtools), [plugin](https://tanstack.com/router/v1/docs/plugins))
- **Lucide React** icons
- **Utility libraries:** [clsx](https://github.com/lukeed/clsx), [class-variance-authority](https://cva.style/)
- **Biome** for linting and formatting

## Getting Started

```bash
npm install
```

### Development

```bash
npm run dev
```

### Build

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Lint & Format

```bash
npm run lint
npm run format
```

### Type Checking

```bash
npm run type-check
```

## Project Structure

- `src/` — Main source code
- `routes/` — App routes (using TanStack React Router)
- `lib/` — Utility functions
- `public/` — Static assets

## Installed Packages

**Dependencies:**
- react, react-dom
- @tanstack/react-router, @tanstack/react-router-devtools
- @tailwindcss/vite, tailwindcss, tailwind-merge
- lucide-react
- clsx, class-variance-authority

**DevDependencies:**
- vite, @vitejs/plugin-react-swc
- typescript, @types/react, @types/react-dom, @types/node
- @biomejs/biome
- @tanstack/router-plugin
- tw-animate-css
- globals

## Linting & Formatting

This template uses [Biome](https://biomejs.dev/) for linting and formatting. See `biome.json` for configuration.

## Routing

App routes are defined in `src/routes/` using TanStack React Router. See [TanStack Router docs](https://tanstack.com/router/v1/docs/overview) for usage.

## Tailwind CSS

Tailwind is configured via `@tailwindcss/vite` and supports advanced merging and animation utilities.

---

## Customization

You can further expand linting, formatting, and routing as needed. For advanced ESLint rules, see [Biome documentation](https://biomejs.dev/docs/linting/).


