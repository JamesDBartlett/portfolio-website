# Portfolio Website
This website is just a placeholder for now, but my plan is to eventually make it the centerpiece of my online presence -- an in-depth, interactive CV / portfolio for potential employers and/or business partners to peruse and find answers to most questions they might have about my skills / experience.

# Table of Contents
* [Current Features](#current-features)
* [Planned Features](#planned-features)

## Current Site
* Mish-mash of categories on front page
* Single page format with links to external resources
* Somewhat graceful responsive design via Bootstrap CSS
* Relies heavily on JavaScript
  * Degrades poorly if JS is disabled (a la NoScript)
  * Still looks OK without JS, but stuff breaks.
* Has NOT been analyzed for or tested against any design standards
* No touch-specific features

## Planned Site
* Simplified front page
* "Flat" design
* Embedded Twitter box
* Make JS optional, but encouraged
  * Entire website should work without JS by default
    * Static content
    * Screenshot & external link to anything that doesn't look nice embedded
    * Small hovering iframe nag: "JavaScript is disabled" w/ link to enable
  * Use JS to toggle "js-enabled" mode
    * Hide "JS is disabled" iframe
    * Upgrade features
      * Static -> Dynamic
      * External -> Inline
      * Screenshot -> Live
* 3 Links on main page
  * Each link is a "category"
    * Clicking a link either:
      * Opens a new page (better for external websites), or
      * Modifies the DOM live (better for content that can be integrated seamlessly)
  * Categories:
    * Software Dev / Design Portfolio
      * Sub-Categories:
        * Front-End Web
          * 3-5 embedded, expandable examples of clever/elegant original code w/ short explanation
          * Each embedded snippet should have an option to see it in context on GitHub
          * Feature HTML, (S)CSS, & (T/)JS, etc.
          * Carousel of full GitHub repo list
        * Back-End Web
          * 3-5 ...
          * ...
          * Feature PHP, MySQL, Apache, etc.
        * Graphic Design
          * 3-5 ...
          * ...
          * Feature Vector, Raster, etc.
        * ...
    * Interactive Functional CV
      * One-page executive overview w/ downloadable PDF link
      * Expandable sections -- Examples:
        * Education history initially lists only (nano)degrees
          * Expands to display institutions, majors, minors, certs, extracurriculars, etc.
        * Work history initially lists only key positions & organization names
          * Expands to display skills, responsibilities, examples of excellence, etc.
    * Personal
      * Bio
      * Blog
      * "Side Hustles"
* Standards Compliance -- Optimized & Fully Compliant With:
  * A11y Standards
  * W3C Standards
  * ...
* Touch-specific features
  * Parallax effect on all photos
  * Carousels should pan smoothly with touch
  * ...
