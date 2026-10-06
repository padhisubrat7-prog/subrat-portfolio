# Portfolio Project Structure

## Content layer

Project descriptions, experience, skills, certifications, and links should eventually be separated from presentation code.

## Asset layer

- `assets/images/` — profile/branding visuals
- `assets/projects/` — project photographs, architecture diagrams, screenshots
- `assets/certificates/` — certificates and verification material

## Presentation layer

`index.html` currently contains the complete responsive interface so the portfolio can be previewed without installing dependencies.

## Recommended next migration

When the design/content is stable:

```text
src/
├── components/
├── data/
├── pages/
├── styles/
└── assets/
```

This keeps future project additions maintainable instead of growing one large HTML file.
