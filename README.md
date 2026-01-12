# Production Build

This directory contains the production build of the Internet Speed Calculator.

## How to Build

To regenerate this distribution folder from the source code, run the following command in the project root:

```bash
npm run build
```

## How to Run locally

Due to browser security restrictions (CORS and ES Modules), you cannot simply open `index.html` in your browser. You must serve it via a static file server.

You can use the built-in preview command from the project root:

```bash
npm run preview
```

Or usage any static site server, for example:

```bash
npx serve dist
```

## Source Code

The source code for this project is available at:
https://github.com/sudeepsudhevan/Internet-Speed-ThreeJS

## Deployment

These files are ready to be deployed to any static hosting service (GitHub Pages, Vercel, Netlify, etc.).

For more information on deploying Vite apps, see:
https://vitejs.dev/guide/static-deploy.html
