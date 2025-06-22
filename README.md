# Checklist App Template

This repository showcases a small React application powered by the [Bun](https://bun.sh) runtime. It uses Tailwind CSS for styling and [shadcn/ui](https://ui.shadcn.com) components.

## Getting Started

Install the dependencies:

```bash
bun install
```

Run the development server with hot reloading:

```bash
bun dev
```

### Building for Production

Create an optimized build into the `dist` folder:

```bash
bun run build.ts
```

Start the application in production mode:

```bash
bun start
```

## Project Structure

- `src/index.tsx` – Bun server with example API routes
- `src/frontend.tsx` – entry point for the React client
- `src/App.tsx` – main UI including a small API tester component
- `styles/globals.css` – Tailwind configuration and global styles

Bun v1.2.17 was used when setting up the project.

