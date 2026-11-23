# Dot Type

Type text and turn it into dotted, dithered lettering on a field of ring dots. Animate each layer, then export the result as a looping video, a PNG or an SVG.

Everything runs in one file, `index.html`, with no build step and no dependencies beyond the Montserrat web font.

## Use it

Open `index.html` in a browser, or serve the folder with any static host (GitHub Pages works).

## Controls

- **Text:** one line per row. Drag any word on the canvas, nudge it with the arrow keys, or set its position, size and color in the Text panel.
- **Type and dots:** typeface, weight, size, spacing, dot size, ring thickness and opacity, solid, ring or ring plus core text dots.
- **Noise and dither:** blob, gradient or even noise field, with random, Bayer or hard-edge dithering, a halo around the text, and edge grain.
- **Color:** background, text and ring colors, with presets.
- **Animate layers:** noise field, text dots, halo and word motion each have their own seamless loop (drift, shimmer, grain crawl, scan sweep, breathe, size wave, wobble, flicker, pulse, float, orbit, slide).
- **Export:** MP4 or WebM video of one or more loops, plus PNG and SVG of the current frame.

## Notes

- Video export uses the browser's `MediaRecorder`. MP4 needs a recent Chromium browser. Other browsers fall back to WebM where supported.
- Very small dot spacing (5 to 7 px) is heavy on phones. Use 9 px or more for smooth animation there.
