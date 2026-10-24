SALONE FARMERS MARKET
Website Project - Technical Overview
======================================================================

1. PROJECT SUMMARY
----------------------------------------------------------------------
Salone Farmers Market is an eight-page website concept that connects
Sierra Leone's farmers and cooperatives with buyers. It lets visitors
browse produce, compare indicative market prices, discover farmers and
cooperatives, learn about the support services offered, and get in touch.

The site follows the approved wireframes page by page, so the layout,
navigation and content areas on screen match the original design.


2. TECHNOLOGY
----------------------------------------------------------------------
The site is built with plain HTML5 and CSS3. No JavaScript, frameworks
or external libraries are used. This keeps every page lightweight, quick
to load, and compatible with any modern browser (Chrome, Edge, Firefox,
Safari), on desktop and mobile.

All pages share a single stylesheet (style.css), so colours, spacing and
typography stay consistent across the whole website.


3. PAGES
----------------------------------------------------------------------
index.html                 Home. Welcome banner with a call to action,
                           four key benefits (better prices, more buyers,
                           more information, stronger communities), a
                           featured produce strip and a "Support Local
                           Farmers" section.

marketplace.html           Marketplace. Search bar with category and
                           district selectors, a category sidebar and a
                           grid of available produce (rice, cassava,
                           cocoa beans, palm oil, maize and plantain).

market-prices.html         Market Prices. Crop and district selectors
                           and a table of current prices by district,
                           bag and kilogram.

produce-details.html       Produce Details. A single product page showing
                           a large photo, description, price, seller
                           button and contact information.

farmers-cooperatives.html  Farmers & Cooperatives. Featured farmers and
                           cooperatives, each with a photo and name.

services.html              Services. Market access, aggregation,
                           transport and logistics, and market
                           information, plus a support call to action.

about.html                 About. Mission, vision, the four values
                           (fairness, transparency, sustainability and
                           community) and who the platform serves.

contact.html               Contact. Contact details, a map image and a
                           "Send Us a Message" section.


4. DESIGN APPROACH
----------------------------------------------------------------------
Colour palette
  - Teal header (#26d4b9) and mauve page banners (#9a8585), taken from
    the wireframes
  - Deep green (#054c1f) for buttons and the footer
  - Sky blue (#4fc8ff) for the produce areas

Layout
  - CSS Grid is used for the multi-column areas such as the produce
    grids, value cards and service cards.
  - Flexbox is used for the header, navigation and search bar.
  - The content is centred in a container with a maximum width of
    1100px, which keeps lines readable on wide screens.

Images
  - Every photo sits inside a fixed-ratio frame (mostly 4:3, with wider
    ratios for banners and the home page hero).
  - Photos are cropped to fill their frame instead of being stretched,
    so people and produce never look distorted, whatever the original
    photo size.
  - The frames scale with the page, so images stay large and clear on
    desktop and shrink sensibly on tablets and phones.

Footer
  - Every page ends with the same footer: the copyright notice
    "(c) 2026 Salone Farmers Market. All rights reserved.", a short
    tagline and quick links to all pages. On short pages the footer
    stays at the bottom of the screen.

Responsive behaviour
  - Two breakpoints (820px and 480px) adapt the layout to tablets and
    phones. Multi-column sections collapse to two columns or one, the
    header stacks, and the footer links move below the copyright text.

Navigation
  - The logo, the site name and the "Home" link return the visitor to
    the home page.
  - Each page lists links to every other page, so any section is one
    click away.
  - The current page is shown in the header label.


5. FOLDER STRUCTURE
----------------------------------------------------------------------
  index.html
  marketplace.html
  market-prices.html
  produce-details.html
  farmers-cooperatives.html
  services.html
  about.html
  contact.html
  style.css
  README.txt
  Human Images/    Photographs and logo used across the pages
  images/          Supporting icons (search and user icons, map)

The HTML pages, the stylesheet and both image folders must stay
together in one folder, because the pages load their images and styling
by relative path.


6. ACCESSIBILITY AND SEARCH FRIENDLINESS
----------------------------------------------------------------------
  - Every image has descriptive alternative text for screen readers.
  - Form fields have labels (hidden visually where the design does not
    show them), and the main navigation is marked up as a navigation
    landmark.
  - Pages use proper headings and descriptive titles, for example
    "Marketplace | Salone Farmers Market".
  - A viewport setting makes every page display correctly on mobile
    devices.


7. CURRENT LIMITATIONS
----------------------------------------------------------------------
This version is a front-end prototype, and the following items are
placeholders by design:

  - Search, category, district and sort controls show the interface but
    do not filter results yet, because that needs scripting or a
    database.
  - Prices on the Market Prices page read "Confirm locally". The
    produce details page shows an example price (Le 220/bag). Both must
    be replaced with verified market data before the site goes live.
  - The contact email address, phone number and office hours need the
    organisation's official details.
  - The "Email us" button opens the visitor's own email application. It
    does not send messages through the website.
  - The Login/Sign up link on the home page is a visual element only.
    There is no account system yet.
  - Produce details are shown for one product (rice). Other items link
    to the same page as a layout example.
##Website Screenshot
###Home page
[Salone's Farmers Market] (HOME.png)


8. SUGGESTED NEXT STEPS
----------------------------------------------------------------------
  1. Connect the search and filters to a live listings database.
  2. Add a working login and registration system for farmers and
     buyers.
  3. Provide a server-based contact form with email delivery.
  4. Add a separate detail page for each product, with live prices.
  5. Publish the site on a hosting service with its own domain name.

Author: Ishmail.Junior.Kamara
(c) 2026 Salone Farmers Market. All rights reserved.
