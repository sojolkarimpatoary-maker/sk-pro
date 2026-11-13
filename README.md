# Sojol Karim — Cybersecurity Portfolio

A responsive, multi-file portfolio website for GitHub Pages. The design uses a charcoal-black background, crisp white typography and emerald-green security accents.

## Included features

- Animated bird landing intro, followed by the portfolio reveal
- Sticky responsive navigation for Home, About, Skills, Tools, Projects, Labs and Contact
- Personal profile portrait supplied by Sojol Karim
- Floating terminal/code panel and subtle motion effects
- Animated role text, scroll reveals, progress indicator and back-to-top control
- Interactive 3D skills cube
- Clickable networking knowledge map
- Tool cards with detail popups
- Learning-project showcase and TryHackMe evidence gallery with image viewer
- Responsive layouts for desktop, laptop, tablet, iPhone and Android
- Reduced-motion accessibility support

## Publish on GitHub Pages

1. Download and extract this ZIP file.
2. Open the extracted folder.
3. Select **all contents inside this folder**: `index.html`, `style.css`, `script.js`, `.nojekyll`, `README.md` and `assets/`.
4. Upload those contents to the **root** of your GitHub repository. Do not upload only the ZIP file or place the files inside an extra nested folder.
5. Open the repository's **Settings → Pages**.
6. Under **Build and deployment**, select **Deploy from a branch**.
7. Choose branch `main` and folder `/ (root)`, then save.
8. Wait for GitHub Pages to finish publishing and open the URL shown in the Pages settings.

## Project structure

```text
sojol-karim-portfolio/
├── index.html
├── style.css
├── script.js
├── .nojekyll
├── README.md
└── assets/
    ├── sojol-karim-profile.webp
    ├── favicon.svg
    ├── tool-*.svg
    └── *.webp (TryHackMe and lab evidence)
```

## Update your content

- Replace `assets/sojol-karim-profile.webp` to update the profile picture, keeping the same filename.
- Add new evidence images to `assets/` and add a matching card in `index.html`.
- Keep the relative file/folder structure unchanged so GitHub Pages can load every asset.

## Accuracy and responsible-use notes

- Tool cards distinguish hands-on evidence, user-reported use and learning focus.
- Project cards are labelled as learning projects; they do not claim client work or professional penetration tests.
- Completion labels in the gallery are based on the supplied screenshots.
- Screenshot copies have been prepared with visible IP-address details removed.
- Only test systems and networks you own or have explicit permission to assess.

## Technical notes

This is a static website. It needs no Node.js, package installation, build command, framework or backend. `index.html` is the entry point, and all styles/scripts/assets are linked with relative paths for GitHub Pages compatibility.
