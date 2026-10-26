# Winx Studio — Assignment 5

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
