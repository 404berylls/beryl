Images used by the site
=======================

home tab
  beryl-bunny.jpg          -> the picture next to "beryl's commissions"

prices tab — one example per price row
  work-portrait.jpg        -> portrait
  work-mirror-selfie.jpg   -> half body
  work-full-body.jpg       -> full body
  work-props.jpg           -> props
  work-drive-in.jpg        -> custom scene build
  beryl-bunny.jpg          -> gradient / solid background
  work-alt-styles.jpg      -> alt character styles

prices tab — "more work" grid
  work-villa-trio.jpg
  work-midnight-trio.jpg
  work-fortober.jpg
  work-new-year.jpg
  work-neon-grid.jpg
  work-illustration.jpg

Captions describe what each shot includes, using the price-list wording
("full body · custom scene build · 3 skins"), so people can match an
example to a price.

Originals are not kept in this folder — drop one in, it gets resized to
a max of 1600 px on the long edge and the original is removed.

Adding an example
-----------------
1. Drop the file in this folder.
2. In index.html, find the price row and swap

     <figure class="shot empty">example coming soon</figure>

   for

     <figure class="shot">
       <img src="assets/your-file.jpg" alt="..." loading="lazy" />
       <figcaption>caption shown in the viewer</figcaption>
     </figure>

Every <figure class="shot"> on the page is clickable and opens in the
zoomable viewer, in the order it appears.
