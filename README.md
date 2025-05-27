Reproduction of Vite dev server issue:
- Vite Dev server needs long time to start
- HMR takes a long time

This is a default React Router for Cloudflare Workers template, created via `npx create-react-router@latest --template remix-run/react-router-templates/cloudflare`.

The app has only 2 routes, the default `home` route and a `dashboard` route. The dashboard is a `shadcn/ui` [block](https://ui.shadcn.com/blocks) added via `npx shadcn@latest add dashboard-01`.
