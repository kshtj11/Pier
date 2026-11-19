# Pier

**Pier is a web prototype only. The AI hats are scripted, not a working AI. The PDF reader works, and you can open your own PDFs. (Drag and Drop them onto any board)**

**Try it:** https://kshtj11.github.io/Pier/

## What Pier is

Pier is a literature-review thinking environment. You collect papers on a board, really read them, pull out quotes, and build an argument in your own words. A small set of AI "hats" (MINER, PROSPECTOR, ARCHITECT, SHADOW and CONDUCTOR) react after you act, with questions and counter-evidence quoted from your own papers. Their job is constructive friction: to make you think, not to think for you.

Created by Kshitij Ghag, IDC School of Design, as his P1 project, Autumn 26

## How to open it

- **Online:** the GitHub Pages link above.
- **On your computer:** download this repository and serve the folder with any static server, for example `npx serve` in the folder, then open the address it prints.
- Opening `index.html` straight from the disk may not load the PDFs, because the browser blocks local files. Use a server.

## Controls

The same list opens when Pier starts, and again with **?** at the top right.

| To | Do this |
|---|---|
| Move around | Scroll, or swipe with two fingers. Or hold Space and drag. |
| Zoom | Ctrl/⌘ + scroll, or pinch on a trackpad. |
| Open a paper or note | Zoom into it, or double-click it. |
| Back to the board | Esc, or zoom out. |
| Read from a peek line | Click the quoted line on a faded paper. The reader opens at that line. |
| Make a quote | In the reader, select text, then Highlight. |
| Put a quote in a note | Drag the quote card onto the note. |
| New note | Double-click the empty board, or press N. |
| Ask a hat | **?** on a card (Bounce). H opens the Hats pane. |
| Why did a hat say that? | Right-click any hat line: "Why are you saying this?" |
| Your own PDFs | Ctrl/⌘ + O, or drop a PDF on the board. |
| Undo, redo | Ctrl/⌘ + Z, Ctrl/⌘ + Y. |
| Find papers, timeline | ☰ at the top left opens the sidebar. |
| Writing room | Write to just write. Argue marks your claims and lets the hats question them. |

## The example papers

The example review asks "Does sunlight make people happier?" and uses four open-access papers, all under a Creative Commons Attribution (CC BY) licence:

- Boubekri et al. (2020), *International Journal of Environmental Research and Public Health*
- Crouse et al. (2025), *European Psychiatry*
- Zhang & Li (2025), *Frontiers in Public Health*
- Peng et al. (2016), *PLOS ONE*

Full citations, DOIs, licences and what was changed: [papers/LICENSES.md](papers/LICENSES.md). The notes on the board, the drafts and the hats' lines are a made-up example built on these papers.

## Known limits

- **The hats are scripted.** Their lines come from fixed rules and from the four example papers. With your own PDFs they fall back to general lines. Every quote they show is checked against the paper's text.
- **Nothing is saved.** Every reload starts the example again, and papers or notes you add are gone.
- **Find needs the internet.** It searches OpenAlex live. Everything else runs offline once the page has loaded.
- The timeline's earlier weeks and the older reviews are sample data, labelled "sample".
- PDFs with no text layer (scanned pages) can't be read or highlighted.
- Built and tested in desktop Chrome with a mouse or trackpad. It is not made for phones.

## Credits

- PDF rendering: [pdf.js](https://mozilla.github.io/pdf.js/) 3.11.174 (Apache License 2.0), in `vendor/`, with its standard fonts (licences in `vendor/standard_fonts/`).
- Fonts: Inter and Source Serif 4 (SIL Open Font License 1.1), in `vendor/fonts/`.
