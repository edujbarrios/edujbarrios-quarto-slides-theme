# Contributing

Thanks for helping improve the edujbarrios Quarto Revealjs Theme.

## Development

Install Quarto 1.4 or newer, then render the example deck:

```bash
quarto render example.qmd
```

The generated `example.html` file and `example_files/` directory are ignored by
git. Keep source changes in `example.qmd`, `_extensions/edujbarrios/_extension.yml`,
and `_extensions/edujbarrios/edujbarrios.scss`.

## Pull Requests

- Keep changes focused and describe the visible presentation impact.
- Include a screenshot when changing layout, typography, colors, or helpers.
- Run `quarto render example.qmd` before opening a pull request.

## Style

- Prefer small, reusable helper classes over one-off slide styling.
- Keep the theme readable on dark backgrounds.
- Avoid committing private decks, generated HTML, extracted assets, or large
  local presentation exports.
