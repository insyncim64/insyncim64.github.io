# Jibin Ou — Personal Website & Portfolio

Modern static personal website and portfolio for **Jibin Ou**, System Architect at Volvo Group.

Built with [Astro](https://astro.build/) and [Tailwind CSS](https://tailwindcss.com/), automatically deployed to GitHub Pages via GitHub Actions.

## Tech Stack

- **Framework:** Astro 5.x (zero client-side JS overhead by default)
- **Styling:** Tailwind CSS v4 (Vite plugin)
- **Icons:** Lucide Icons & SVG
- **Deployment:** GitHub Pages via GitHub Actions (`.github/workflows/deploy.yml`)

## Local Development

```bash
# Install dependencies
npm install

# Start local development server (http://localhost:4321)
npm run dev

# Build production static output (to dist/)
npm run build

# Preview production build locally
npm run preview
```

## GitHub Pages Deployment

Deployment is automated via GitHub Actions on every push to `master` (or `main`).
To enable:
1. In your GitHub repository, navigate to **Settings** → **Pages**.
2. Under **Build and deployment > Source**, select **GitHub Actions**.
3. Push to `master`, and the site will automatically build and publish to `https://insyncim64.github.io`.
