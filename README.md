# A Journey Through the History of Art

This is a plain HTML/CSS/JavaScript static website. It does not use Vite, Create React App, Next.js, React Router, or a backend server.

## Build locally

```bash
npm install
npm run build
```

The build copies `index.html` into `dist/`, which is the Netlify publish directory.

## Deploy to Netlify

Connect this project repository to Netlify. The included `netlify.toml` configures:

- Build command: `npm run build`
- Publish directory: `dist`

The page uses Tailwind CSS, Font Awesome, and Google Fonts from public CDNs, so an internet connection is needed for those external assets.

There is no Express/long-running backend and no SPA client-side router, so no redirect rule or Netlify Function is required.
