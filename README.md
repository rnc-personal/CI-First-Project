!CI Poftfolio Project 1

Overall design style inspired by monogramcc.com from https://www.frontendpractice.com/projects/monogram

Logo Generated by: https://looka.com
Some copy generated with: https://app.copy.ai
All Images from Unsplash:

- Add Credits Here
-
-

Card Overlay Idea inspired by: https://stevenstromick.com/css/css-card-overlay/

Responsive iframe tip for YT Video from: https://www.w3schools.com/howto/howto_css_responsive_iframes.asp

24/09/2022 - Bug after adding FontAwesome where changes to CSS didn't register, only HTML changes were being picked up.
Removed Font Awesome but no change. Tried Re-order stylesheet links order in header but again no change..
Had to Rename CSS file and re-link. Confirmed there were no typos/missing characters in the css link. (Resolved)

- Issue with case studies grid with text overflow because of the width of the grid items.(Resolved)



- Gallery Hover Overlay on mobile was a challenge. Tried tip from:
https://time2hack.com/can-i-use-hover-on-touch-devices/ but not widely support so instead set a fixed opacity on the overlay for mobile.


***************************************
**************STILL TO DO**************
***************************************

- Contact Page Footer Subscribe Form is trying to validate the main conact form. names/ids are different...Is it just because those fields are required? (Fixed)

- Tablet Footer Form Wraps

- Lazy Load gallery images at bottom of homepage (done)

- YT Iframe is harming Lighthouse Score on Mobile, tested GIF instead.

- Home Gallery Tablet sized... CAn you tap to hover? Might need to incerase where these cards become opaque?
- Contact Page needs aria IDs to seaprate the forms for screen readers

- Contact Page either needs a new section or just work on styling more? Text is still black