# NIH SRLM — Schedule Performance & S-Curve Analysis

Interactive Quarto report covering updates U29–U51, baseline comparisons, working-day variances, milestone trends and Helix scope analysis.

## Local preview

Install Quarto 1.11.9 or later, open this folder, and run:

```sh
quarto preview index.qmd
```

To build: `quarto render`. Output: `dist/index.html`.

## Publication

GitHub Actions renders the Quarto project and deploys `dist/` to GitHub Pages. Set **Settings → Pages → Source → GitHub Actions**.

## Data scope

This version preserves the content, embedded data and interactive charts of the approved U29–U51 HTML report. Rendering does not recalculate the XER schedules. Raw XER files and credentials are not included.
