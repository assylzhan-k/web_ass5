# Winx Studio — Assignment 5

Ready-to-open project based on the original `uldanay2008/web_ass4` website.
The original layout, palette, typography, page sections and Assignment 4
behaviour are retained. Assignment 5 is connected on every page already.

## Open

Extract the whole ZIP into a new folder and open `index.html` in a modern
browser. You can also open this folder in VS Code and use Live Server.
Do not merge the folder with either previous archive. No setup scripts,
package installation or build step are needed.

**Internet is required.** Bootstrap 5.3.3 and all images are loaded remotely.
The original local Home/Team images now use their public GitHub URLs, so
there is no old `images` folder to copy. The archive contains the page code,
local styles, scripts and the sound file, not offline copies of photographs.
External resources remain subject to availability at their original sources.

## Pages

- `index.html`: original home page plus a five-star rating.
- `makeup.html`: original makeup cards and guide.
- `products.html`: original catalog, category filters, favorites and carousel.
- `tips.html`: original tips, inspiration gallery and FAQ.
- `team.html`: original team cards and studio gallery carousel.
- `contact.html`: original form, optionally filled in three steps.

## Assignment 5 additions

`js/assignment5.js` handles keyboard navigation, rating, sound, animations and
optional multi-step form controls. `css/assignment5.css` styles the added
controls. The original behaviour remains in `js/script.js`.

The form stores values only in the existing DOM while moving between steps.
It performs client-side validation; it does not send messages, register users
or store passwords. The subscription form is also a validation demonstration.
Favorites attempt to use localStorage and fall back to the current visit if
storage is unavailable.

The required callback option is the multi-step form, not an HTTP submission.
The existing background-change button covers dynamic styling; a second theme
system is deliberately not added.

## Original design

The original CSS selectors, declaration values and cascade order are retained.
Source formatting is normalised. The `Other Products` heading's original
inline colour is moved to `.as5-products-title` with the same value.
Image URLs that previously referred to local files now point to those same
files in the public repository. No replacement photographs were selected.

Original source: https://github.com/uldanay2008/web_ass4

## Testing and limits

See `docs/TEST_RESULTS.json` for static and isolated Chromium interaction checks.
The test environment blocks browser navigation and external resources. Tests
loaded these HTML documents and local CSS/JS in memory; Bootstrap and images
were not loaded. The bundled WAV was tested as a data URL. This is not a full
end-to-end certification of external resources, responsive rendering,
Bootstrap components, cross-page navigation or storage persistence.

This folder is source code only, not a PDF report. Publication and repository
changes have not been performed.
