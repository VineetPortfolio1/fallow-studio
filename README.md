# Fallow Studio

Single-file landing site for a boutique wellness studio. Open `index.html` in a browser; no build step.

## Replace before launch
- Studio name, tagline and copy
- Hero image, teacher portraits and class images (currently CSS gradient slots)
- `[PRICE]`, `[Day] · [Time]`, `[Teacher name]`, testimonial names and FAQ policies
- Social and legal links (currently `#`)
- Newsletter form: connect it to your email service (it is a demo)

Fonts: Instrument Serif and Jost via Google Fonts.

## Design source
`design/` holds the editable design canvas export from Claude Design:
- `fallow-landing.dc.html`: the landing page artboard (design component source)
- `canvas.json`: canvas layout (artboard size and settings)

The `.dc.html` file needs the Claude Design editor to render and edit it. `index.html` is the standalone website built from it.
