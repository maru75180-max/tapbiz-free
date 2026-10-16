# TapBiz Website

A responsive, static TapBiz local-business directory inspired by the supplied design.

## Run it on your computer
1. Extract `tapbiz-website.zip`.
2. Open `index.html` in Chrome, Edge, or Firefox.

No Node.js, database, or build tools are required.

## Publish with GitHub Pages
1. Sign in to GitHub and create a new repository, for example `tapbiz`.
2. Upload `index.html` and this `README.md` to the repository's root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then click **Save**.
6. Wait for GitHub to publish the site. The Pages section will show the public URL.

## Included features
- Responsive layout for desktop and mobile
- Search by business name, owner, category, address, or description
- Category filters
- Add Business form with basic required-field validation
- New listings saved to the current browser using localStorage
- Google Maps search links for directions

## Important limitations
This is a front-end demo. Businesses added through the form are saved only in the browser that submitted them; they are **not shared with other visitors** and will not be stored in a central database. For a real public directory where everyone sees submitted listings, connect a backend/database such as Supabase or Firebase and add authentication/moderation. Do not collect sensitive information until you have appropriate privacy and security protections.
