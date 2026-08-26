# Somnath Mishra Portfolio

Premium dark portfolio website for Somnath Mishra, a Biotechnology student exploring bioinformatics, programming, data analysis, research, and technology.

## Features

- Responsive single-page portfolio for desktop, tablet, and mobile
- Sticky navigation with mobile menu
- Profile portrait and Lovely Professional University campus imagery
- Certificate showcase with supplied certificate image
- Six selected-work project visuals with category filtering
- Project detail modal for each project
- Contact form validation and success state
- Smooth scrolling, reveal animations, hover states, grain texture, and reduced-motion support
- SEO metadata and Open Graph metadata
- Downloadable resume PDF

## Files

- `index.html` - Page structure, portfolio content, metadata, and navigation
- `styles.css` - Main responsive visual system
- `profile-image.css` - Profile portrait treatment and hero layering
- `asset-layout.css` - Campus and selected-work image layout
- `certificate.css` - Certification card styling
- `supplied-assets.css` - Styling for supplied certificate and university images
- `script.js` - Skills, projects, filtering, modal, menu, form, and image behavior
- Resume details are presented directly in the portfolio; no resume PDF is included.

## Assets

The `assets` folder contains:

- `somnath-profile.jpg` - Profile portrait used in the hero and About section
- `certificate.png` - Social internship certificate
- `lovely-professional-university.jpeg` - University campus image
- `medical-report.svg`, `smart-water-bottle.svg`, and `bioinformatics-data.svg` - Project visuals used by the three resume projects
- Certificate PDFs for additional credentials

## Run Locally

No build step is required. Open `index.html` directly in a browser, or serve the folder with any static web server.

## Edit Content

Update the profile image path, project data, skills, and interactive content in `script.js`. Update text, links, and section structure in `index.html`.

Contact links configured in `index.html`:

- Professional email: `somnathmishra2025@lpu.com`
- LinkedIn: `https://linkedin.com/in/somnath-mishra-802184382`
- GitHub: `https://github.com/somnath699`

The portfolio does not include a resume download button because no PDF is present in the project root.

## Deploy with GitHub Pages

1. Push the repository to GitHub.
2. Open **Settings > Pages** in the repository.
3. Set the source to **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder.
5. Click **Save**.

The published site will be available at:

`https://somnath699.github.io/myportfolio/`

## Updating the Site

```powershell
cd "C:\Users\HP\OneDrive\Desktop\portfolio"
& "C:\Program Files\Git\cmd\git.exe" add .
& "C:\Program Files\Git\cmd\git.exe" commit -m "Update portfolio"
& "C:\Program Files\Git\cmd\git.exe" push
```