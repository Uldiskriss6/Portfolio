ULDIS KRISS GÓMEZ R. — UX/UI & Product Design Portfolio

Publish this whole folder on GitHub (GitHub Pages: Settings > Pages > Deploy from branch > main / root).

  index.html               <- the whole site: home + the four case studies, global nav, EN/ES switch
  asistente-digital.html   <- Asistente Digital case, loaded inside index.html (keep it next to index.html)
  atomic-design.html       <- redirects to index.html#case-atomic
  pet-center.html          <- redirects to index.html#case-pet-center
  credicrea.html           <- redirects to index.html#case-credicrea

Language: the EN / ES switch is in the top bar on every page. The choice is remembered; the first visit follows the browser language.
To add or fix a translation, edit the I18N_PAIRS list in the <script> of index.html (English, Spanish) and,
for the Asistente case, the PAIRS list at the end of asistente-digital.html.


Rojas Travels case: rojas-travels.html (+ rojas-*.jpg images) is loaded inside index.html like asistente-digital.html. Translations: PAIRS inside rojas-travels.html. Keep all .jpg files next to index.html.

Credicrea case: credicrea-case.html (+ credicrea-*.jpg) loads inside index.html. Translations: PAIRS inside credicrea-case.html.


FOLDERS: index.html at the root; case-study pages in pages/; images in assets/. Paths inside pages/ use ../assets/ and ../index.html.

Friendly case: pages/friendly-case.html loads inside index.html (#case-friendly). Translations: PAIRS inside friendly-case.html. Its images are hosted links (lh3.googleusercontent.com); to self-host them, save them in assets/ and replace the src values.
