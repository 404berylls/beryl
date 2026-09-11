Images used by the site
=======================

home tab
  beryl-bunny.jpg          -> the picture next to "beryl's commissions"

prices tab — one example per price row
  (portrait)               -> MISSING, shows a dashed "example coming soon" box
  work-mirror-selfie.jpg   -> half body
  work-full-body.jpg       -> full body
  (props)                  -> MISSING
  work-drive-in.jpg        -> custom scene build
  beryl-bunny.jpg          -> gradient / solid background
  (alt character styles)   -> MISSING

prices tab — "more work" grid
  work-midnight-trio.jpg
  work-fortober.jpg
  work-neon-grid.jpg
  work-illustration.jpg

honey2.png is the untouched original of beryl-bunny.jpg (3 MB). The site
does not load it, so you can delete it if you don't want it published.

Adding an example
-----------------
1. Drop the file in this folder (max ~1600 px on the long edge, under
   ~400 KB keeps the page fast).
2. In index.html, find the price row and swap

     <figure class="shot empty">example coming soon</figure>

   for

     <figure class="shot">
       <img src="assets/your-file.jpg" alt="..." loading="lazy" />
       <figcaption>caption shown in the viewer</figcaption>
     </figure>

Every <figure class="shot"> on the page is clickable and opens in the
zoomable viewer, in the order it appears.
