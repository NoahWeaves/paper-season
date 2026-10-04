# Paper Season

A minimal timeline of submission deadlines and conference dates for the CS conferences you follow, six months either side of today.

Pick conferences on first visit; your choices are saved in your browser (`localStorage`). Flags mark deadlines (outlined for abstracts), dots mark decisions, airplanes mark the conference. Dashed or faded marks are estimates projected from the previous edition.

## Data

Conference dates come from [ccfddl/ccf-deadlines](https://github.com/ccfddl/ccf-deadlines). `build_data.py` downloads that repo and writes `data.js`:

```sh
uv run build_data.py
```

A GitHub Action reruns it daily, commits `data.js` when it changes, and redeploys the site to GitHub Pages.

## Local preview

```sh
python3 -m http.server
```

then open http://localhost:8000.
