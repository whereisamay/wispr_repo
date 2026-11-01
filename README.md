# Amay's Product Run

An interactive portfolio: a rap-video hero, a journey map of four playable retro-platformer worlds (Finmo, Code & Theory, StepSetGo, LiveAltLife), side quests and links.

Everything lives in a single self-contained `index.html` (HTML, CSS and JavaScript, with the beat synthesised in the browser and the vocal track embedded). No build step.

## Run locally
Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Publish with GitHub Pages
Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / root. The site appears at `https://whereisamay.github.io/wispr_repo/`.

## Editing content
The content sits in plain config objects near the top of the script in `index.html`:
`ABOUT`, `RAP_LINES`, `WORLDS` (projects per company), `SIDE_QUESTS`, `TOOLS` and `SOCIALS`.

Note: the vocal track (`VOCALS_B64`) was generated from `RAP_LINES` with an open-source text-to-speech voice and time-fitted to the beat; changing the lyrics means regenerating it.
