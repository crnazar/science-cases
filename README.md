# Counternarratives of the Culture of Power in Science

An interactive, self-contained web activity for **pre-service science teachers**, built from the case-study chapter *"Youth Counternarratives of the Culture of Power in Science"* (Restrepo Nazar & Calabrese Barton).

Teachers-in-training explore the identities, science experiences, inventions, and problem/solution work of three youth — **AD** (duct-tape thermometer tie), **Faith** (solar FANcy hat), and **Christopher** (SUSU anti-bullying app) — then connect each case to concrete teaching moves, write reflections, and export a portfolio (PDF or text) for course credit.

The activity also frames the work as a **digital humanities** project in science education, with recommendations for supporting more DH practice in the field.

## Live site

Once GitHub Pages is enabled (see below), the activity is served at:

```
https://crnazar.github.io/science-cases/
```

## Files

- `index.html` — the entire activity. A single, self-contained file: all HTML, CSS, and JavaScript are inline, with no external dependencies. Works offline and hosts anywhere static.

## How it works

- **No backend.** All reflections, checkboxes, and progress autosave to the browser's `localStorage`. Nothing is transmitted or "submitted" automatically.
- **Export for credit.** The *My Reflection Portfolio* page collects every response and exports a clean PDF (via the browser's Print → Save as PDF) or a plain-text file to hand in.
- **Light & dark themes**, responsive layout, keyboard-navigable.

## Enabling GitHub Pages

1. Go to the repository **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Select the branch that contains `index.html` and the `/ (root)` folder, then **Save**.
4. Wait ~1 minute; the site publishes at the URL above.
