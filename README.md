# Selyna

Personal page for Selyna with Vercel Web Analytics integration.

## Features

- Clean, modern design with Tailwind CSS
- Responsive layout
- Vercel Web Analytics for tracking page views
- Font Awesome icons

## Vercel Web Analytics Setup

This project includes Vercel Web Analytics integration. The analytics script is automatically loaded on each page visit.

### How it works:

1. The analytics code is included at the bottom of `index.html`
2. When deployed to Vercel, the `/_vercel/insights/script.js` endpoint is automatically available
3. Page views and navigation are tracked automatically

### To enable analytics on Vercel:

1. Deploy this project to Vercel
2. Navigate to your project's Analytics section in the Vercel dashboard
3. Click the "Enable" button to activate Web Analytics

## Development

```bash
# Install dependencies
npm install

# Run local development server
npm run dev

# Build (for static site)
npm run build
```

## Deployment

This project is configured to deploy on Vercel. Simply connect your GitHub repository to Vercel and it will automatically deploy.

## Analytics Package

This project uses `@vercel/analytics` version 1.4.1 for web analytics tracking.
