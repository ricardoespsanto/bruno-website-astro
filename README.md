# Bruno Website – Astro Refactor

Lightweight Astro version of the Bruno marketing site for comparison.

## Key differences from Next.js

- **Layouts**: Single `BaseLayout.astro` wraps every page with shared `<Header />` and `<Footer />`. No duplication.
- **Blog**: Content Collections (`src/content/blog/*.md`). Schema-validated, type-safe, automatic routing.
- **Zero JS by default**: Pure static HTML unless you opt into islands.
- **Tailwind**: Same utility classes, lighter build.

## Run locally

```bash
npm install
npm run dev
```

Compare with the original Next.js repo: https://github.com/usebruno/bruno-website
