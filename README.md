# FlavorBook — Food Recipe App

A React + Vite recipe application with Admin and User modules. Authentication, users, recipes, and favorites are stored in browser Local Storage for this academic demo.

## Features

- User signup and login with Local Storage
- Admin login and protected Admin Dashboard
- Admin can create, edit, and delete recipes
- Users can browse and search recipes, filter by category, and save favorites
- Responsive layout for desktop and mobile
- Demo data is seeded automatically on first visit

## Run locally

1. Install Node.js (LTS) from https://nodejs.org/
2. Extract this project ZIP and open the folder in VS Code.
3. Open a terminal in the project folder and run:

```bash
npm install
npm run dev
```

4. Open the local URL printed by Vite, usually http://localhost:5173.

## Demo accounts

- Admin email: `admin@flavorbook.com`
- Admin password: `Admin@123`

You can also create a regular user account from the Sign up page.

## GitHub upload

Create a new empty repository on GitHub, then run these commands in the project folder (replace the URL):

```bash
git init
git add .
git commit -m "Build FlavorBook recipe app"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

## Deploy on Vercel

### Option A — Vercel website (recommended)

1. Push the project to GitHub using the commands above.
2. Sign in at https://vercel.com/ using GitHub.
3. Select **Add New → Project** and import your repository.
4. Keep Framework Preset as **Vite**.
5. Build command: `npm run build`
6. Output directory: `dist`
7. Click **Deploy**. Vercel will provide your public URL.

### Option B — Vercel CLI

```bash
npm install
npm run build
npm install -g vercel
vercel login
vercel
```

Follow the prompts. For production deployment after preview:

```bash
vercel --prod
```

## Important note for your review

This project intentionally uses Local Storage as requested. It is suitable for a classroom demonstration, not production authentication. Users and passwords are stored in the browser and can be inspected or changed by the browser owner. A real production app should use a secure backend, password hashing, server-side authorization, and a database.

## Review demonstration checklist

1. Open the app and sign in with the admin demo account.
2. Add a recipe, edit it, then delete it.
3. Log out and sign up as a normal user.
4. Search/filter recipes and add one to Favorites.
5. Refresh the browser to show that Local Storage preserves the demo data.
6. Open the deployed Vercel URL in a fresh browser tab.
"# flavour-book" 
