## Bearn Consulting — Astro + Tailwind site

This is the marketing website for Bearn Consulting (Bearn Hibbins). Built with Astro (TypeScript) and Tailwind CSS.

Features:
- Fast static site (Astro)
- Tailwind CSS styling
- Responsive, accessible components
- Pages: Home, Services (WhatsApp Business API, AI, DevOps), Contact

How to run locally:
1. Install dependencies
   - npm install
2. Start dev server
   - npm run dev
3. Build for production
   - npm run build

Preview the production build
- Recommended: npm run preview
  - Serves the built site with correct absolute paths (/_astro, /favicon.svg).
- Alternative static server (from dist/): npm run serve:dist
  - Starts a simple HTTP server rooted at dist. Avoid opening dist/*.html with file://, which breaks absolute URLs and hashed chunks (e.g., /_astro/*, /favicon.svg).

Notes
- If you open the built HTML via file://, the browser resolves “/...” to your filesystem root and assets like /_astro/*.css or /favicon.svg will 404. Always use a local server to preview the dist build.
# bearn-consulting