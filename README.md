# Aurora Gold Membership — Scenario Sets

A collection of self-contained membership-task scenario pages based on a fictional **Aurora Gold Membership Program** for the fictitious **Aurora Hotels**, created for academic research. All pages are pure static HTML/CSS/JS with **no build step and no external dependencies** — open them in any modern browser and they run.

This repository groups the scenario pages into three sets. The root `index.html` links to each set's own index, and each set's index links to its individual scenario pages.

## Structure

```
.
├── index.html      # Root entry page linking to all three sets
├── README.md       # This file
├── anonymous1/     # Four scenario pages
│   ├── index.html
│   ├── x1.html · x2.html · x3.html · x4.html
│   └── README.md
├── anonymous2/     # Two scenario pages
│   ├── index.html
│   ├── y1.html · y2.html
│   └── README.md
└── anonymous3/     # Two scenario pages
    ├── index.html
    ├── z1.html · z2.html
    └── README.md
```

## Usage

- Open `index.html` in a browser to reach the three sets.
- Click a set card to open that set's scenario index, then click any scenario card to enter the corresponding scenario page.
- Alternatively, open any scenario page directly (for example `anonymous1/x1.html`).
- Scenario pages support an optional `return` parameter for redirecting back to the survey after the task is completed; when omitted, the page simply stays on the page.

## Customization

The pages are plain HTML with inline CSS and can be edited directly:

- **Hotel / program name:** edit the `AURORA HOTELS` brand text and the wording inside the Gold membership card.
- **Scenario text:** modify the content inside the `<div class="scenario">`, `<div class="status">`, and adjacent `<p>` blocks.
- **Styling:** colors and layout are controlled by the CSS custom properties in the `:root` block (e.g. `--navy`, `--gold`).

## Disclaimer

These pages are experimental stimuli for academic research. They do not represent any real hotel, loyalty program, or commercial offer, and are provided as-is without warranty.

## License

For research and educational use. Please contact the authors for any commercial use or reproduction.
