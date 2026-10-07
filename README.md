# Portfolio site

A self-contained, responsive portfolio with no build tools or dependencies. `index.html` is the home page, `blog.html` is the writing page, `projects.html` is for project write-ups, and `about.html` holds the personal bio.

## Publish with GitHub Pages

1. Copy `index.html`, `about.html`, `projects.html`, and `blog.html` into the root of your GitHub repository (or place all four in a `/docs` folder and select that folder in the repository’s **Settings → Pages**).
2. In **Settings → Pages**, choose **Deploy from a branch**, then select your branch and `/ (root)` or `/docs`.
3. Replace the `hello@example.com` address near the end of `index.html` with your email address. Add your name, project links, and social profiles when you’re ready.

The site uses only HTML and CSS, so it works directly on GitHub Pages without a build step.

The Home page includes a scroll-driven noise effect based on the sparse 3×3-block experiment. The panel starts black and progressively fills with noise as you scroll through the bio.

The footer view counter uses the public CounterAPI service. It counts page views across the GitHub Pages site under one shared total, and does not run in local file previews. CounterAPI documents the no-signup public embed and API at <https://counterapi.com/>.
