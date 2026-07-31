# VolunteerForFood

A volunteering-awareness website that introduces The Akshaya Patra Foundation's mission and ways people can support it.


## Disclaimer

This repository is presented as an educational front-end project. Organisation names, programme information, contact details, and external links are retained from the supplied source material. The repository does not state or imply official affiliation or endorsement.

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white">
  <img alt="Bootstrap 5" src="https://img.shields.io/badge/Bootstrap-5.0.2-7952B3?logo=bootstrap&logoColor=white">
  <img alt="Static website" src="https://img.shields.io/badge/type-static%20website-6B7AA1">
</p>

## Overview

VolunteerForFood is a front-end informational website focused on food-support volunteering. It presents The Akshaya Patra Foundation's work, meal programme, recognitions, volunteering options, contact details, and a downloadable volunteering request form.

The project uses static HTML and CSS, with Bootstrap components supplied through a CDN. It does not include a database, login system, server-side processing, or an online form-submission backend.

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


## Current limitations

- The website is an informational front-end project; it does not store user data.
- There is no authentication, administration dashboard, or database.
- The volunteer form is downloaded, completed offline, and sent using the contact information displayed on the site.
- Bootstrap, Font Awesome, and Google Fonts require internet access because they are loaded from external CDNs.
- Organisation details and contact information reflect the supplied repository snapshot and should be verified before a public deployment.

<p align="center">
  <img src="docs/assets/volunteerforfood-hero.png" alt="Illustration of volunteers supporting a community meal programme" width="900">
</p>



