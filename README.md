# Power BI Wavy Animation Backgrounds (No Title)

Two lightweight, CSS-only animated backgrounds for use in Power BI **HTML Viewer** visuals (no JavaScript).  
- **Dark Blue** – deep ocean vibe with a dark centre glow  
- **Fire** – warm orange/red gradient with a dark centre glow  
Both are **title-free** so they can sit behind other visuals or act as transition screens.

## Preview
Open the static HTML files in a browser:
- `wavy-dark-blue.html`
- `wavy-fire.html`

## Use in Power BI
1. Import an **HTML Viewer** custom visual (e.g., “HTML Content”).
2. Create a **Measure** and paste one of the DAX snippets:
   - `WavyBlueDark`
   - `WavyFireDark`
3. Bind the measure to the visual.

> Notes  
> - These animations are pure CSS.  
> - No external fonts or scripts required.  
> - Uses large rotating, rounded shapes to create a smooth “wavy” effect.

## Files
- `wavy-dark-blue.html` — Standalone HTML (dark blue)
- `wavy-fire.html` — Standalone HTML (fire)
- DAX snippets in this README for Power BI usage

## Attribution / Source
This work is an adaptation of a **user-supplied CSS snippet** (inline wave animation with rotating rounded spans).  
The approach (rotating border-radius blobs over a gradient) is a common CSS technique used across many demos.  
If you reuse or remix, please credit:  
**“Based on CSS provided by Guy Orlov (project adaptation).”**

## License
MIT — do what you like, just keep a credit note if you share publicly.
