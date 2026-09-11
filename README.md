# Chance Regine Abijuru — Portfolio

A responsive personal portfolio for **Chance Regine Abijuru**, a Software Engineer based in Kigali, Rwanda. The site presents selected work, experience, skills, and contact details in a calm, dark visual style.

## Live projects featured

- [DreamizeAfrica](https://dreamizeafrica.com/)
- [AgriSense](https://agrisense.rw/)
- [RwandaWorks UI/UX Design](https://www.figma.com/design/we7oIyxLeOXmHWG7l97eha/RwandaWorks?node-id=0-1&t=YMTGvAnkG5sdy0aS-0)
- [FarmLink UI/UX Design](https://www.figma.com/design/c5E2nVboEUPq24cekLikC4/FarmLink?t=6W0zilEjovWIoDJI-0)

## Features

- Responsive layout for desktop, tablet, and mobile
- Dark, minimal portfolio design
- Smooth scrolling and animated section reveals
- Subtle falling-star background and interactive hover motion
- Work experience timeline and project grid
- Contact form with validation and Gmail compose flow
- Links to GitHub, phone, email, live projects, and Figma designs
- Motion accessibility support for visitors who prefer reduced animation

## Built with

- HTML5
- CSS3
- Vanilla JavaScript

No framework or build step is required.

## Run locally

1. Clone this repository.

   ```bash
   git clone https://github.com/ChanceRegine/portfolio.git
   ```

2. Open the project folder.

   ```bash
   cd portfolio
   ```

3. Open `index.html` in your browser.

For a local development server, you can use the VS Code **Live Server** extension.

## Project structure

```text
portfolio/
├── index.html       # Portfolio content and interactions
├── styles.css       # Design, animation, and responsive styles
└── README.md        # Project documentation
```

## Customisation

The primary content is in `index.html`:

- Update project names, descriptions, and links in **Selected Work**.
- Update experience, skills, email, phone number, and GitHub link as your career grows.
- Update the contact form recipient in the Gmail URL if your professional email changes.

The visual system is in `styles.css`. You can adjust the background, accent colour, type, animation speed, and spacing through the CSS variables at the top of the file.

## Contact form note

The current form validates the visitor’s input and opens a complete draft in Gmail for them to review before sending. It does not store visitor data on the website.

For direct form delivery in production, connect a verified custom-domain email address with a service such as Resend and configure SPF, DKIM, and DMARC records.

## Deployment

This is a static site and can be deployed easily with:

- [GitHub Pages](https://pages.github.com/)
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)

## License

This project is personal portfolio work. Please do not reuse Chance Regine Abijuru’s personal details, project descriptions, or visual identity without permission.
