# Computing Society Workshops

A collection of workshops designed to teach practical skills that aren't covered in the standard CS curriculum.

## What Is This?

Quick-paced, hands-on workshops covering tools and techniques that will actually save you time as a developer.

## Workshops

| Workshop | Topic | What You'll Learn |
|----------|-------|-------------------|
| [01_tools/](01_tools/) | Productivity Tools | gemini-cli, Quarto basics |
| [02_git/](02_git/) | Git | Version control, collaboration |
| [03_api/](03_api/) | APIs | HTTP, cURL, DevTools, automation |
| [04_bash/](04_bash/) | Bash Basics | Terminal navigation, scripting |
| [05_catchup_n_quarto/](05_catchup_n_quarto/) | Term 1 Recap | How these slides work, Q&A |

## How to Use These Materials

### View a Presentation

Each workshop has a `main.qmd` file. Render it with:

```bash
quarto render workshop_name/main.qmd
```

This generates `main.html` - open it in your browser.

### Fork and Modify

1. Fork this repository
2. Clone your fork
3. Edit the `.qmd` files
4. Render your own copies

## Requirements

- [Quarto CLI](https://quarto.org/docs/get-started/)
- A terminal (Bash recommended)
- git

## Suggested Order

If you're new, start with:

1. **01_tools/**    - Productivity tools (gemini-cli is a game-changer)
2. **02_git/**      - Version control before you break things
3. **03_api/**      - Automation and understanding how the web works
4. **04_bash/**     - You need the terminal
5. **05_catchup_and quarto/** - Recap of term 1 and quarto slides

## Contributing

See something wrong? Want to add a workshop?

1. Create a new folder `workshop_name/`
2. Add `main.qmd` with the standard YAML header
3. Include a `README.md`
4. Submit a PR

## Standard Workshop Structure

```
workshop_name/
├── main.qmd          # Presentation slides
├── main.html         # Generated output (gitignored)
└── main_files/       # Images, assets (gitignored)
```

## License

MIT. Use it, break it, learn from it.

## Questions?

Open an issue or ask at the next workshop.
