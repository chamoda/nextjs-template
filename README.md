This is a [Next.js](https://nextjs.org) project template with special focus on SSG first rendering.

## Architecture

This project is built on the **Jamstack architecture**, leveraging Next.js's powerful Static Site Generation (SSG) capabilities. By pre-rendering pages at build time, the application delivers:

- **Lightning-fast performance**: Static HTML files served directly from CDN
- **Enhanced security**: No server-side runtime reduces attack surface
- **Scalability**: Static files can be distributed globally with minimal infrastructure
- **SEO optimization**: Fully rendered HTML improves search engine indexing

### Next.js SSG Configuration

The project is configured with SSG-first rendering, meaning pages are generated as static HTML at build time.

## Getting Started

First, run the development server:

```bash
npm run dev
```

## Deployment

### Cloudflare Static Hosting

This template is optimized for deployment on **Cloudflare Pages** as Next.js static site deployment
