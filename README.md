# Leaflet Campus Book Exchange

A React and Vite app for finding, saving, and listing used textbooks on campus.

## Requirements

- Node.js 18 or newer
- npm

## Run locally

```sh
npm install
npm run dev
```

Vite prints the local URL after the development server starts.

## Production build

```sh
npm run build
npm run preview
```

Saved books, profile details, and user-created listings are stored in browser local storage. Seller messages and waitlists are prototype interactions and are not connected to a backend.

The university sign-in is also a UI prototype: it checks the selected demo campus email domain but does not verify identity or connect to a university single sign-on provider. Add a trusted authentication backend before using it for real student access.