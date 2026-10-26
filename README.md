# Mohan Zhang – Academic Homepage

Personal academic website of Mohan Zhang, live at https://joyymoonh.github.io/.

## Editing content

The site is static: Markdown files in `contents/` are parsed in the browser on load, so there is nothing to build.

| File | Section |
| --- | --- |
| `contents/home.md` | About |
| `contents/news.md` | News |
| `contents/publications.md` | Publications |
| `contents/experience.md` | Research experience |
| `contents/awards.md` | Honors & awards |
| `contents/config.yml` | Page title and footer text |

The sidebar (photo, contact, interests) lives in `index.html`; styles are in `static/css/main.css`.

To preview locally, run `python3 -m http.server` in this folder and open http://localhost:8000.

## Credits

Built on the MIT-licensed [academic homepage template](https://github.com/senli1073/senli1073.github.io) by Sen Li, which is based on [Start Bootstrap – New Age](https://github.com/StartBootstrap/startbootstrap-new-age). See `LICENSE`.
