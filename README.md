# Fourth Coast Contractors website

Static site (HTML, CSS, a little JavaScript). No build step. Works as-is on GitHub Pages.

## Files
```
index.html        the whole site (Services, Why us, About us, Contact us)
css/styles.css    all styling and Ohio State colors
js/main.js        mobile menu
assets/           logo.png and favicon.png
.nojekyll         tells GitHub Pages to serve files exactly as they are
```

## Publish on GitHub Pages
1. Create a GitHub account, then click **New repository**. Name it `fourth-coast-contractors` (or `yourusername.github.io` for a root URL). Set it to Public.
2. Click **uploading an existing file** and drag in everything from this folder, keeping the folders (`css`, `js`, `assets`). `index.html` must be at the top level of the repository. Commit the upload.
3. Go to **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then **Save**.
4. After about a minute your site is live at `https://yourusername.github.io/fourth-coast-contractors/`.

## Use your own domain (optional)
Buy a domain, then in **Settings > Pages > Custom domain** enter it and follow GitHub's DNS instructions. Turn on **Enforce HTTPS**.

## Make the contact form send to your inbox
The form currently opens the visitor's email app (`mailto:`). To receive submissions directly:
1. Make a free account at formspree.io and create a form for `fourthcoastcontractors@yahoo.com`.
2. In `index.html`, change the `<form>` tag to:
   `<form class="form" action="https://formspree.io/f/YOUR_ID" method="post">`

## Edit content
Open `index.html` in any text editor. Phone numbers and email appear in the top bar, hero, contact section and footer, so use find and replace if they change.
