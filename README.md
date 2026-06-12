# OneShop - E-Commerce Storefront

:shopping: :rocket: PWA and JAMstack based e-commerce template for E-Com Plus stores

> Generated from [@ecomplus/storefront-starter](https://github.com/ecomplus/storefront-starter)

## 🚀 Quick Links

- **[Documentation](https://developers.e-com.plus/storefront/)**
- **[Get Started](https://github.com/ecomplus/storefront-starter#getting-started)**

## 📋 Project Setup

```bash
npm install
```

### Development

Compiles and hot-reloads for development:

```bash
npm run serve
```

Site will be available at `http://localhost:9100/`

### Production Build

Compiles and minifies for production:

```bash
npm run build
```

Build output is generated in the `dist/` directory and ready for deployment to Vercel.

## 🌐 Deployment

This project is configured for automated deployment to **Vercel** via GitHub Actions.

### Required Secrets

Add these to your GitHub repository secrets:

- `VERCEL_TOKEN` - Your Vercel authentication token
- `VERCEL_ORG_ID` - Your Vercel organization ID
- `VERCEL_PROJECT_ID` - Your Vercel project ID

The workflow automatically triggers on pushes to `master` branch when relevant files change.

## 📦 Built With

- Vue.js
- Webpack
- Progressive Web App (PWA)
- JAMstack architecture
- E-Com Plus API integration

## 📄 License

MIT
