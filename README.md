<h1 align="center">En Yi — Personal Portfolio</h1>

<p align="center">
  A personal website showcasing my background, skills, achievements, and projects.<br>
  Built with HTML, CSS, and JavaScript.
</p>

<p align="center">
  <a href="https://enyiportfolio.netlify.app/"><strong>🌐 EXPLORE THE LIVE PORTFOLIO →</strong></a><br>
  <sub>Discover my story, explore my projects, and get in touch.</sub>
</p>

---

## Overview

I'm **Teoh En Yi**, and this portfolio brings together my learning journey, technical interests, and creative work. Across five pages, it introduces my background, highlights my skills, and presents projects through images, interactive details, and demonstrations.

Developed as a Web Fundamentals project, the website uses plain HTML, CSS, and JavaScript to demonstrate page layout, responsive styling, navigation, and interactive components.

## Contents

- [Features](#features)
- [Technology](#technology)
- [Pages](#pages)
- [Featured Projects](#featured-projects)
- [Folder Structure](#folder-structure)
- [Getting Started](#getting-started)
- [Customization](#customization)
- [Refinement Checklist](#refinement-checklist)
- [Author](#author)
- [License](#license)

## Features

- **Personal introduction:** Homepage with an overview of my interests, skills, and featured work.
- **About section:** Personal background, education, and achievements.
- **Skills showcase:** Cards and carousel navigation for exploring different skill areas.
- **Project gallery:** Project cards, detail modals, images, and links to demonstrations.
- **Contact page:** Contact information, social links, an embedded map, and a demonstration form.
- **Responsive styling:** Layout rules and navigation controls for different screen sizes.
- **Interactive details:** Image slideshows, smooth scrolling, and back-to-top controls.

## Technology

| Technology | Purpose |
| --- | --- |
| HTML5 | Page structure, navigation, forms, and images |
| CSS3 | Styling, layout, responsive rules, and visual transitions |
| JavaScript | Carousels, project modals, navigation, and form feedback |
| Google Maps Embed | Map embedded on the contact page |

Styles and scripts are embedded in the HTML pages. The portfolio requires no package installation, framework, database, or build step.

The technologies mentioned inside individual project descriptions refer to those showcased projects, not necessarily to this portfolio's implementation.

## Pages

| Page | File | Content |
| --- | --- | --- |
| Home | [`home.html`](home.html) | Introduction, skills overview, and featured projects |
| About | [`aboutme.html`](aboutme.html) | Biography, education, and achievements |
| Skills | [`skills.html`](skills.html) | Skill areas and development interests |
| Projects | [`project.html`](project.html) | Project gallery and detailed project modals |
| Contact | [`contact.html`](contact.html) | Contact information, social links, map, and form |

## Featured Projects

The portfolio includes presentations of the following work:

| Project | Showcase |
| --- | --- |
| OffBuy | Shopping app concept with screenshots and a local demonstration video |
| HopNTrip | Sabah tourism website |
| Zogin | Fitness website |
| Architecture Portfolio | Architectural work and visual design |
| Personal Blog | Blog website design |

This repository contains the portfolio and its presentation assets. The complete source code of each showcased project is not included.

## Folder Structure

```text
enyi-portfolio/
├── README.md
├── home.html
├── aboutme.html
├── skills.html
├── project.html
├── contact.html
├── image/
│   └── ...                 # Portraits, backgrounds, icons, and project images
└── video/
    └── OffBuy.mp4           # OffBuy demonstration video
```

Keep the media folders beside the HTML files. Pages reference them using relative paths such as `image/me.jpeg` and `video/OffBuy.mp4`.

## Getting Started

### Open in a Browser

1. Download or clone the repository.
2. Extract the ZIP if you downloaded an archive.
3. Open `home.html` in a modern browser.
4. Use the navigation menu to explore the other pages.

### Run a Local Server

If Python 3 is installed, open a terminal in the project folder and run:

```bash
python -m http.server 8000
```

On Windows, you can also run:

```powershell
py -m http.server 8000
```

Visit **[http://localhost:8000/home.html](http://localhost:8000/home.html)**.

Press **Ctrl+C** in the terminal to stop the server.

An internet connection is needed for external project links, social destinations, and the embedded map. Local pages and media can be previewed without a backend.

## Customization

| Change | Where to edit |
| --- | --- |
| Introduction and homepage content | `home.html` |
| Biography, education, and achievements | `aboutme.html` |
| Skill categories and descriptions | `skills.html` |
| Project cards and modal data | `project.html` |
| Featured project modal data | `home.html` |
| Contact information and form behaviour | `contact.html` |
| Photos, icons, and backgrounds | `image/` and the corresponding page references |
| OffBuy demonstration | `video/OffBuy.mp4` |

Navigation and footer content are repeated across pages, so update all relevant files when changing shared elements. Keep asset names and capitalization consistent.


## Author

**Teoh En Yi**  
Personal portfolio developed for Web Fundamentals.

Contact details and social profiles are available on the website's [Contact page](contact.html).

## License

No license file is currently included. This README does not grant reuse rights for the code, personal photographs, or other media. Third-party assets remain subject to their respective owners' terms.




Contact details and social profiles are available on the website's [Contact page](contact.html).

## License

No license file is currently included. This README does not grant reuse rights for the code, personal photographs, or other media. Third-party assets remain subject to their respective owners' terms.
