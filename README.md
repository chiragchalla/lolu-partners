# Lolu partner pages

Static site. No build step, no dependencies.

## Structure

    /wakingup/index.html   -> partners.lolulife.com/wakingup
    /wakingup/images/
    /wakingup/logos/

To add a partner, copy the `wakingup` folder, rename it, and edit:
- the CTA `href` (the Brandbot checkout URL)
- the partner logo in `logos/`
- the lede and the offer line

## Before shipping a partner page

- [ ] Mariana Tek discount created and use-capped
- [ ] Brandbot checkout page built with the discount pre-attached
- [ ] Checkout verified in a logged-out incognito window
- [ ] Post-purchase redirect pointed at the schedule
- [ ] CTA `href` updated from the placeholder
