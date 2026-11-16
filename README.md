# noman-k.github.io

Personal homepage of Noman Khan, live at **[noman.io](https://noman.io)**.

A simple, single dark page with a short intro, links to my profiles, and the projects I've built.

## Projects

| | Project | Link |
|---|---|---|
| <img src="icons/slate.svg" width="24" alt=""> | Slate | [slate.noman.io](https://slate.noman.io) |
| <img src="icons/flyte.png" width="24" alt=""> | Flyte | [flyte.noman.io](https://flyte.noman.io) |

## Structure

```
index.html    the whole page (HTML + inline CSS, no build step)
icons/        app icons for each project
robots.txt    crawler rules
sitemap.xml   sitemap for search engines
```

## Running locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploying

Hosted on GitHub Pages from the `main` branch. Pushing to `main` publishes the site within a minute or two.

## Adding a project

1. Save the app's icon in `icons/`.
2. Copy one of the `<li>` blocks in the Projects list in `index.html` and update the name, URL and icon.
3. Add the project to the `ItemList` in the structured data (`application/ld+json`) near the top of `index.html`.

## Elsewhere

- [GitHub](https://github.com/noman-k)
- [LinkedIn](https://www.linkedin.com/in/noman-khan)
