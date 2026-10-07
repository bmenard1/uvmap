"The full sky in the ultraviolet" — the public / astronomer article page of the full-sky ultraviolet map, packaged for an
external static web host (built October 7, 2026).
Author: Brice Ménard (Anthropic · Johns Hopkins University · Santa Fe Institute).
Licence: page text and figures CC BY 4.0; the data products CC BY 4.0 and the code MIT, as stated on the page.

WHAT IS INSIDE (28 files, about 56 MB; the zip has no top-level folder)
  index.html   the page: Part 1 for everyone, Part 2 for astronomers (technical summary, downloads, paper);
               dark mode by default with the dark/bright switch at the top right
  img/         its figures and images (23 files)
  docs/        the 2 documents the page links: buildup_sequence.pdf, uvsky_paper_DRAFT_2026-10-07.pdf
  README.txt   this file
  .nojekyll    an empty marker that tells GitHub Pages to serve the files as they are (harmless on any other host)

TO PUBLISH
  Upload everything in this folder to the web root of the site, or to any sub-folder of it: all links are
  relative. Nothing to build and nothing is fetched from elsewhere: the page loads only files from this folder.
  Note: GitHub Pages refuses files over 100 MB; the largest file here is the paper PDF (26 MB).

HOME ADDRESS OF THE PAGE
  http://menard.pha.jhu.edu/uvmap — the only external address the page mentions (section 8). Section 6 says download
  links for the maps (FITS and HiPS) and their documentation will be added to the page; section 8 cites the paper as
  "in preparation".

LOCAL PREVIEW
  In this folder run:  python3 -m http.server   then open http://localhost:8000/
