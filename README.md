# Discover Your Influencing Style — Quiz

A single-page quiz to help people identify their influencing style (Bridging, Rationalizing, Asserting, Inspiring, Negotiating) based on the BRAIN framework. Includes personalized results and a guide to all five styles.

## Run locally

- **Option 1:** Open `index.html` in a browser (double-click or `open index.html` on macOS).
- **Option 2:** Serve the folder with any static server, e.g.:
  ```bash
  python3 -m http.server 8080
  ```
  Then visit `http://localhost:8080`.

## Deploy as a website

`index.html` is self-contained (HTML, CSS, JS in one file). Deploy the project folder as a static site.

### GitHub Pages

1. Create a repo and push this folder.
2. **Settings → Pages → Source:** Deploy from branch.
3. Choose the branch and `/ (root)` (or the folder that contains `index.html`).
4. The site will be at `https://<username>.github.io/<repo>/`.

### Netlify

1. Drag the project folder into [app.netlify.com/drop](https://app.netlify.com/drop), or
2. Connect the repo and set the publish directory to the project root.

### Vercel

1. Import the project and deploy; no build step needed for static files.

### Other hosts

Upload the folder (or just `index.html` if you keep assets in the same directory) to any static hosting (e.g. S3, Cloudflare Pages, your own server). The app works with `file://` and does not require a special server.

## Structure

- **Home:** Intro and “Start the quiz”.
- **Quiz:** 10 questions, randomized option order, Back (to Home on Q1), progress.
- **Results:** Primary (and co-primary when tied or within 1 point), optional secondary, why, strengths, blind spots, how to work best with your style(s), and how to use other styles in your own way.
- **Guide:** Overview of all five styles (what, when it works, example, working with each type).

## Content

Content is based on the BRAIN influencing styles (Musselwhite & Plouffe) and your source PDFs. Edit the `CONTENT` and `GUIDE` objects in the `<script>` section of `index.html` to change copy.
