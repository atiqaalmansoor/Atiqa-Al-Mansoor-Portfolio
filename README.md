# Atiqa Al Mansoor – Personal Portfolio

A responsive personal portfolio for Atiqa Al Mansoor, a Software Engineering student at Sindh Madressatul Islam University (SMIU). The site introduces her academic background, current skills, selected projects, certificate and contact placeholders in a polished navy and light-blue visual style.

## Technologies used

- HTML5 for semantic page structure
- CSS3 for layout, styling, responsive behavior and interactions
- No JavaScript or frontend frameworks

## Website sections

- Home / introduction
- About
- Education
- Technical skills
- Projects
- Certificates
- Contact and a non-submitting form design

## Run locally

1. Download or clone this project.
2. Open `index.html` in a modern web browser.

No build step or package installation is required. An internet connection is used only for the optional Google Fonts; system sans-serif fallbacks are provided.

## Personalize before publishing

- Replace `images/profile-placeholder.jpg` with a profile photograph, keeping the same filename or updating the image path in `index.html`.
- Add a certificate image in the certificate placeholder if desired.
- Replace the project-link placeholders with the actual GitHub repository and live demo links.
- Add real email, GitHub and LinkedIn details in the contact section.
- The contact form is visual only. Connect it to a backend or a form service before presenting it as a working submission form.

## Upload to GitHub

1. Create a new repository on GitHub.
2. In a terminal, open this project folder and initialize Git if it is not already a repository:

   ```bash
   git init
   git add index.html style.css README.md images/profile-placeholder.jpg
   git commit -m "Add personal portfolio website"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
   git push -u origin main
   ```

3. Replace the sample remote URL with your own repository URL.
4. To publish with GitHub Pages, open the repository's **Settings → Pages**, choose the `main` branch and `/ (root)` folder, then save. GitHub Pages will publish `index.html` from the project root.
