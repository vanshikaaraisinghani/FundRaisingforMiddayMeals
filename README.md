# VolunteerForFood

<p align="center">
  <img src="docs/assets/volunteerforfood-hero.png" alt="Illustration of volunteers supporting a community meal programme" width="900">
</p>

<p align="center">
  A static volunteering-awareness website that introduces The Akshaya Patra Foundation's mission and ways people can support it.
</p>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white">
  <img alt="Bootstrap 5" src="https://img.shields.io/badge/Bootstrap-5.0.2-7952B3?logo=bootstrap&logoColor=white">
  <img alt="Static website" src="https://img.shields.io/badge/type-static%20website-6B7AA1">
</p>

## Overview

VolunteerForFood is a front-end informational website focused on food-support volunteering. It presents The Akshaya Patra Foundation's work, meal programme, recognitions, volunteering options, contact details, and a downloadable volunteering request form.

The project is intentionally lightweight: it uses static HTML and CSS, with Bootstrap components supplied through a CDN. It does not include a database, login system, server-side processing, or an online form-submission backend.

## Preview

| Home page | Volunteer and contact section |
| --- | --- |
| ![VolunteerForFood home page](docs/screenshots/homepage.png) | ![VolunteerForFood volunteer and contact section](docs/screenshots/volunteering-opportunities.png) |

## What is included

- A landing page with navigation to the contact, volunteering, and about sections
- An introduction to The Akshaya Patra Foundation and its food programme
- Bootstrap carousels for meal photographs and organisational achievements
- Four volunteering-information pages:
  - Online Supporter
  - Blogging
  - Online Fundraising
  - Social Media
- A downloadable Microsoft Word volunteering request form
- Public contact information and links to the organisation's social pages
- Responsive styling for desktop and smaller screens

## Visitor journey

```mermaid
flowchart LR
    A["Open VolunteerForFood"] --> B["Learn about the mission"]
    B --> C["View meals and achievements"]
    C --> D["Explore volunteering options"]
    D --> E["Read an opportunity page"]
    D --> F["Download the request form"]
    F --> G["Complete the form offline"]
    G --> H["Send it to the listed HR email"]
    A --> I["Visit contact or social links"]
```

For a more detailed page map and technical view, see [docs/application-flow.md](docs/application-flow.md).

## Technology

| Area | Technology |
| --- | --- |
| Structure | HTML5 |
| Styling | CSS3 |
| Components and layout | Bootstrap 5.0.2 via CDN |
| Icons | Font Awesome 5.10 via CDN |
| Typography | Google Fonts: Montserrat and Ubuntu |
| Downloadable resource | Microsoft Word `.docx` form |

## Project structure

```text
VolunteerForFood/
├── index.html
├── online-supporter.html
├── blogging.html
├── online-fundraising.html
├── social-media.html
├── Volunteering-Request-Form.docx
├── css/
│   └── styles.css
├── images/
│   └── ...
└── docs/
    ├── application-flow.md
    ├── assets/
    └── screenshots/
```

## Run locally

No installation or build step is required.

1. Download or clone the repository.
2. Open a terminal in the project folder.
3. Start a simple local web server:

   ```bash
   python3 -m http.server 8000
   ```

4. Visit `http://localhost:8000` in a browser.

Opening `index.html` directly also works for most content, but a local server provides behavior closer to normal web hosting.

## Page guide

| File | Purpose |
| --- | --- |
| `index.html` | Main landing page, organisation overview, carousels, volunteering links, form download, and contact details |
| `online-supporter.html` | Describes online advocacy activities |
| `blogging.html` | Describes blogging as a volunteering option |
| `online-fundraising.html` | Describes online fundraising participation |
| `social-media.html` | Describes social-media volunteering activities |
| `Volunteering-Request-Form.docx` | Blank request form intended to be completed offline |

## Visual design

The original interface uses a soft, community-oriented palette:

| Colour | Hex | Use in the supplied design |
| --- | --- | --- |
| Sage green | `#BFD8B8` | Primary page background |
| Warm beige | `#E5DCC3` | Supporting section tone |
| Muted blue | `#6B7AA1` | Text and visual accents |

## Current limitations

- The website is an informational front-end project; it does not store user data.
- There is no authentication, administration dashboard, or database.
- The volunteer form is downloaded, completed offline, and sent using the contact information displayed on the site.
- Bootstrap, Font Awesome, and Google Fonts require internet access because they are loaded from external CDNs.
- Organisation details and contact information reflect the supplied repository snapshot and should be verified before a public deployment.

## Repository integrity

The application pages, styles, images, downloadable form, wording, branding, and links are preserved from the supplied project. This GitHub-ready edition adds documentation and preview material only; it does not change the application code or claim functionality that is not present.

## Disclaimer

This repository is presented as an educational front-end project. Organisation names, programme information, contact details, and external links are retained from the supplied source material. The repository does not state or imply official affiliation or endorsement.
