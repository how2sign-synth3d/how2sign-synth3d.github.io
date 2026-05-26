# How2Sign-Synth3D — Dataset Website

This repository hosts the website for the **How2Sign-Synth3D** dataset.

🌐 **Live site:** `https://<your-github-username>.github.io/<repo-name>/`

## What's in this repo

| File | Purpose |
|---|---|
| `index.html` | The full single-page website |
| `.nojekyll` | Tells GitHub Pages to serve the HTML directly (no Jekyll processing) |

## Enabling GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under *Source*, select **Deploy from a branch** → `main` (or `master`) → `/ (root)`.
4. Click **Save**. Your site will be live at `https://<username>.github.io/<repo>/` within a minute or two.

## Updating download links

Search for `Link coming soon` in `index.html` and replace each placeholder with the real URL. Each download cell looks like:

```html
<span class="placeholder-text">Link coming soon</span>
```

Replace with an anchor tag once links are available:

```html
<a href="YOUR_LINK" class="dl-link active" target="_blank">⬇ Download</a>
```

## Updating the publication details

- **Venue** — search for `[Venue — placeholder]` (appears in the pub card and the BibTeX block).
- **Paper links** — find the `pub-link placeholder` buttons and add the real `href` + remove the `placeholder` class.

## Citation

```bibtex
@inproceedings{Tempfli_How2SignSynth3D,
  title     = {How2Sign-Synth3D: Markerless Holistic Sign Language Performance Capture
               and Synthetic Data for Dense Landmark Tracking},
  author    = {Tempfli, Levente and Huber, Stephan and Koller, Oscar and Duarte, Amanda},
  booktitle = {[Venue — placeholder]},
  year      = {2025}
}
```
