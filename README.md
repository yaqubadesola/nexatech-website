# NexaTech Solutions

NexaTech Solutions is a fictional digital technology agency featured in this responsive, four-page website. The site introduces the agency, its services and values, and provides a way for visitors to get in touch.

## Pages

- **Home** (`index.html`): agency introduction, service highlights, and calls to action.
- **About** (`about.html`): the agency's story, mission, vision, and values.
- **Services** (`services.html`): service descriptions and a four-step process.
- **Contact** (`contact.html`): contact information and a project inquiry form.

## Implementation

The website uses semantic HTML and separate external stylesheets for global styles (`styles.css`), the hero (`hero.css`), navigation (`nav.css`), and the footer (`footer.css`). Splitting the CSS by page section keeps the styles organized and makes the code easier to read and maintain. No build tools or JavaScript are required. The layouts adapt to smaller screens, including a CSS-only mobile navigation menu and responsive SVG artwork on the home page. The homepage hero uses `<picture>` and a mobile `<source>` to select the composition better suited to narrow screens; the SVGs remain sharp at different display resolutions. The service illustrations use SVG `<img>` elements because each is a scalable vector that stays crisp at any screen density and works in the same card layout at every viewport. Their shared 4:3 viewBox matches the displayed dimensions, while the global image sizing and card styles preserve their proportions. The contact form uses `mailto:` and is a demonstration only; it does not submit to a website backend. Agency contact details shown on the page are fictional.

## Run locally

Open `index.html` in a web browser, then use the navigation to visit the other pages.

## Team

- Divan Le Grange: [dvnlegrang@gmail.com](mailto:dvnlegrang@gmail.com)
- Yaqub Adesola: [yaqub.adesola@gmail.com](mailto:yaqubadesola@gmail.com)
- Lethabo Kaphioa: [lethabokatlego120@gmail.com](mailto:lethabokatlego120@gmail.com)
