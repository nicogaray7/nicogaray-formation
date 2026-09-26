# nicogaray-formation

Landing site for [formation.nicogaray.com](https://formation.nicogaray.com): in-home and remote computer, smartphone and AI lessons, mainly for seniors around La Sauve, Créon and the Entre-deux-Mers area (Gironde, France).

## About

- Static HTML/CSS/JS, no build step.
- Hosted on GitHub Pages with the custom domain `formation.nicogaray.com` (see [CNAME](CNAME) once the domain is switched).
- Google Analytics 4 events are sent by [assets/track.js](assets/track.js); `/go/rdv/` is a tracked redirect to the booking page.
- Split out of [nicogaray7/nicogaraycons](https://github.com/nicogaray7/nicogaraycons), which hosts the main site, with its history preserved.

## Structure

| Path | Content |
| --- | --- |
| `index.html` | Home page |
| `bordeaux-seniors/`, `creon-entre-deux-mers/`, `apprendre-smartphone-senior/`, `demarches-en-ligne-seniors/`, `chatgpt-debutant/` | Local and topic landing pages |
| `favicon/`, `assets/`, `go/rdv/` | Shared files copied from the main site |
| `404.html` | Page served for unknown URLs |

## License

Proprietary. All rights reserved.
