# Site index · format 2
Structure and the names of what each page offers. Values that change often — prices, hours, phone,
address — and body copy are deliberately not recorded here; read the page itself for those.

## index.html → /
title: Namels Matebeto – Tradional Fresh Food, Friendly faces.
purpose: The home page of Namels Matebeto presenting the menu, opening hours, location, and a contact form.
sections:
- `#hero` "Namels Matebeto" — hero introduction with featured dish price and links: Nshima served with Relish
- `#offerings` "Menu" — dish list with priced main item: Nshima Served with Relish, Fried Fish, Boiled Fish, Smoked Fish, Dry Fish, T-bone, Beef stew, Beef Sausage, Goat Meat, Vimbombo, Offals, Kapenta, Water(s), Water(B)
- `#hours_location` "Open every day" — opening hours table for all days of the week: Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday
- `#story` "The Best Food You can Eat." — quote and story statement: nakonde
- `#contact` "Write to the kitchen." — contact form with inputs for name, email, and message
also: The restaurant description appears in the meta description and the schema restaurant block.
also: The location Nakonde appears in the meta description, schema restaurant block, schema faq block, and story section.
also: The telephone number appears in the schema restaurant block, schema faq block, and contact form error handler.
also: The email address appears in the schema restaurant block, schema faq block, and contact form error handler.
also: The list of menu dishes appears in the schema menu section name, schema faq block, offerings section ul aria-label, and offerings section list items.
also: The dish list aria-label holds the same comma-separated string of dishes as the JSON-LD menu section name and the FAQ answer, all of which mirror the visible list items.

## support files
Files that are not pages. A line marked [content] holds words or data a visitor reads, so a
change to the site's content can land there; the rest only make the site work or look right.
- `llms.txt` — 105 bytes — too small to hold content
- `robots.txt` — 45 bytes — too small to hold content
- `sitemap.xml` — 160 bytes — too small to hold content

## shared (every page)
The header, navigation, mobile menu and footer are propagated from index.html to every other page by
`shell_propagation`. A change to any of them is made on index.html alone and copied automatically.
