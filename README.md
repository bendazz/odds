# odds

A simple front-end only lesson page that visualizes the odds function:

f(p) = p / (1 − p)

Features:
- Interactive Chart.js plot of f(p) for 0 < p < 1
- Slider to pick a specific p and highlight the point
- Toggle between linear and logarithmic y-axis scales

## Run locally

Because this is a single static file (`index.html`), you can open it directly in your browser. For best results (and to avoid any local file restrictions), serve it via a tiny static server:

```bash
# Option A: Python 3
python3 -m http.server 8000

# Option B: Node.js (if you have it)
npx serve -l 8000
```

Then visit:

- http://localhost:8000/

No build or dependencies required—Chart.js is loaded via CDN.