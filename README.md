# The Little Dot

A tiny story about finding your purpose, told in 16 pages in about 60 seconds, inside a page-turning book.

Press play and the book turns itself, each page arriving at its moment in the story. Drag a page to turn it by hand (that pauses the read-through), drag the brass glass across a page to look closer, or pick any page from the list below the book. The space bar plays and pauses.

## What is here

- `index.html` holds everything: layout, the page-turn geometry, the magnifier, and the autoplay.
- `pages/` holds the 16 spreads as WebP images (story text on the left page, an ink-and-watercolour illustration of the dot on the right).
- `sketchbook/` holds the fonts, the desk wash and the botanical ornaments.

Page timings live in the `PAGES` list in `index.html` (`t` is the second each page appears). Add `?play` to the URL to start reading as soon as the page loads.

## Run locally

```
python3 -m http.server
```

Then open http://localhost:8000.

## Credit

The book, page-turn and magnifier come from Meng To's [Sketchbook](https://github.com/MengTo/sketchbook).
