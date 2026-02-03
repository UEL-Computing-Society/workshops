# Computing Society Workshops

A collection of workshops designed to teach practical skills that aren't covered in the standard CS curriculum.

## What Is This?

Quick-paced, hands-on workshops covering tools and techniques that will actually save you time as a developer.

## Workshops

| Workshop | Topic | What You'll Learn |
|----------|-------|-------------------|
| [01/](01/) | Productivity Tools | gemini-cli, Quarto basics |
| [api/](api/) | APIs | HTTP, cURL, DevTools, automation |
| [bash/](bash/) | Bash Basics | Terminal navigation, scripting |
| [git/](git/) | Git | Version control, collaboration |
| [05_03_feb_2026/](05_03_feb_2026/) | Term 1 Recap | How these slides work, Q&A |

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

1. **01_tools/** - Productivity tools (gemini-cli is a game-changer)
2. **02_bash/** - You need the terminal
3. **03_git/** - Version control before you break things
4. **04_api/** - Automation and understanding how the web works
5. **05_quarto/** - Recap of term 1 and how

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
├── main_files/       # Images, assets (gitignored)
├── README.md         # Workshop overview
└── .gitignore       # Quarto outputs
```

## License

MIT. Use it, break it, learn from it.

## Questions?

Open an issue or ask at the next workshop.
