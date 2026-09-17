# CV source

`cv.html` is the source for `../CV_Aldas.pdf`. Editing the text and regenerating
the PDF needs no tooling — just a browser.

## Editing

Open `cv.html` in a text editor and change the text. Each sheet is a
`<div class="page">` sized to exactly A4, so content that grows past the bottom
is clipped rather than silently pushed onto a third page. If a page overflows,
move an entry to the other page instead of letting it spill.

## Regenerating the PDF

1. Open `cv.html` in Chrome or Edge.
2. Print (`Ctrl`/`Cmd` + `P`).
3. Destination **Save as PDF**, paper **A4**, margins **None**,
   and tick **Background graphics** — without it the gradient bar and the
   tag pills come out blank.
4. Save over `../CV_Aldas.pdf`.

## Fonts

Inter and Space Grotesk, subset to Latin + Latin Extended-A so the Lithuanian
diacritics render. Both are licensed under the SIL Open Font License 1.1; the
license texts sit next to the font files in `fonts/`.
