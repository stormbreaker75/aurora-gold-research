# Aurora Gold Membership — Scenario Pages

A set of self-contained membership-task scenario pages based on a fictional **Aurora Gold Membership Program** for the fictitious **Aurora Hotels**, created for academic research. All pages are pure static HTML/CSS/JS with **no build step and no external dependencies** — open them in any modern browser and they run.

## Files

| File | Description |
|---|---|
| `index.html` | Entry page that shows four scenario cards and links to each scenario page |
| `x1.html` | Scenario page 1 |
| `x2.html` | Scenario page 2 |
| `x3.html` | Scenario page 3 |
| `x4.html` | Scenario page 4 |
| `README.md` | This file |

Each scenario page presents a short membership task. After the participant finishes, the page shows a completion notice and prompts them to return to the survey.

## Usage

- Open `index.html` in a browser and click any scenario card to enter the corresponding scenario page.
- Alternatively, open any scenario page directly (for example `x1.html`).
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
