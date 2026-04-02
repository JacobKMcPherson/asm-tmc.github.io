# ASM-TMC Chapter Website

Source code for the **American Society of Microbiology – Texas Medical Center (ASM-TMC) Chapter** website, built with [Quarto](https://quarto.org) and deployed to GitHub Pages.

## Pages

| Page | File | Description |
|---|---|---|
| Home | `index.qmd` | Welcome, mission, events preview |
| Events | `events.qmd` | Upcoming and past chapter events |
| Resources | `resources.qmd` | Journals, funding, databases, career tools |
| About | `about.qmd` | Chapter overview, leadership, contact |

## Local Development

1. Install [Quarto](https://quarto.org/docs/get-started/)
2. Clone this repository
3. Run `quarto preview` to start a local dev server at `http://localhost:4848`

## Deployment

Pushes to the `main` branch automatically trigger the GitHub Actions workflow (`.github/workflows/publish.yml`) which builds and deploys the site to GitHub Pages.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
