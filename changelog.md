## Changelog

### Part 1 — April 2026
- Created full file and folder structure (css, images folders)
- Built semantic HTML5 structure for index.html (header-top flex row, nav, hero image, two-column intro, footer)
- Built semantic HTML5 structure for about_us.html (history, mission, vision, team sections)
- Built semantic HTML5 structure for services_or_products.html (three product category sections with images, lists, YouTube and Instagram embeds)
- Built semantic HTML5 structure for enquiry.html (embedded Google Form with grocery background)
- Built semantic HTML5 structure for contact_us.html (contact info, trading hours, Google Form, six Google Maps)
- Added navigation menu linking all five pages across all pages with active page highlighting
- Added descriptive HTML comments to all five pages explaining each section and each element
- Added alt text to all images across all five pages for accessibility
- Added SEO meta description and keywords to all five pages
- Added Google Maps iframes for Three Thabiso's Barber School branches (Cape Town, Centurion, Manchester)
- Embedded Google Form on enquiry.html and contact_us.html
- Embedded YouTube video and Instagram reel on services_or_products.html
- Created README.md with project overview, sitemap, file structure, and changelog

### Part 2 — May 2026
- Created css/style_sheet.css as a single external stylesheet linked to all five pages
- Imported Google Fonts: Montserrat (headings) and Roboto (body text) for a professional typographic hierarchy
- Applied CSS reset using the universal selector (*) to normalise default browser margins, padding, and box-sizing across all browsers
- Set body background to neutral light grey (#f4f4f4) and base text colour to near-black (#222222)
- Styled all heading levels (h1–h4) with the Montserrat font, Makro red (#CC0000), and appropriate size/weight hierarchy
- Restructured the header to use a flex row (.header-top) so the Makro logo and h1 sit side by side cleanly
- Styled the navigation bar with a full-width Makro red (#CC0000) background, white uppercase text, and smooth 0.25s hover transitions to a darker red (#990000)
- Added a gold (#FFD700) bottom border on the active navigation link to clearly indicate the current page
- Built the homepage hero section as a relative-positioned div with a full-width cover image and an absolutely positioned dark overlay; centred heading, tagline, and CTA button displayed using flexbox
- Created responsive two-column CSS Grid (.intro-grid) for homepage introduction cards with hover lift effect and left red border accent
- Styled the CTA button with Makro red background, white uppercase text, and a translateY(-2px) hover effect for interactivity
- Styled all product images (.style) with a red border, border-radius, box-shadow, and a scale(1.04) hover transform
- Wrapped product images in a flexbox .product-images row that wraps naturally on smaller screens
- Styled the contact info card (.contact-info-card) in Makro red with white text and gold accent headings
- Styled the response time notice (.response) as a highlighted left-border box for visual attention
- Built a two-column CSS Grid (.maps-grid) for branch location maps, each in a white card with a red header band
- Styled the enquiry page with a grocery store background image (background-attachment: fixed) and a white semi-transparent .form-card overlay for readability
- Styled the footer with a dark (#1a1a1a) background, light grey text, and a 4px red top border
- Implemented tablet responsive design at max-width 768px: intro-grid and maps-grid collapse to single column, heading sizes reduce, navigation font reduces to fit five links on one row
- Implemented mobile responsive design at max-width 480px: navigation stacks vertically, hero image height reduces, CTA button fills full width, product images stack to a single column
- Pushed all Part 2 changes to GitHub repository with descriptive commit messages

### Part 3 — June 2026
- Replaced the Google Form embed on enquiry.html with a native HTML form (text, email, tel, two select menus, textarea) including HTML5 and JavaScript validation
- Replaced the Google Form embed on contact_us.html with a native HTML form, validated client-side and submitted via a generated mailto: link addressed to Thabiso's Barber School customer care inbox
- Built js/forms.js: shared validation helpers (required fields, email regex, SA phone number regex, minimum message length), inline error messages, and aria-invalid attributes for accessibility
- Implemented AJAX form submission on the Enquiry form using the Fetch API (asynchronous POST request), followed by a dynamically generated response message reflecting the visitor's selected category and enquiry type
- Built js/script.js: product search bar and category filter buttons (Groceries/Household/Outdoor) that show/hide sections in real time without a page reload
- Added an image gallery lightbox to the Products page — clicking any product image opens a full-screen viewer with next/previous navigation, keyboard support (Escape/Arrow keys), and focus management for accessibility
- Added a four-question FAQ accordion section to the Products page using ARIA aria-expanded attributes for accessibility
- Added scroll-triggered fade-in animations to product and FAQ sections using the IntersectionObserver API
- Built js/map.js: an interactive Leaflet.js map (open-source, no API key) plotting all six branch locations as clickable markers with popups, plus a dropdown that flies the map to the selected branch
- Renamed images/cleaning supplies.jpg and images/dry goods.png to hyphenated file names (cleaning-supplies.jpg, dry-goods.png) for SEO-friendly URLs and updated all references
- Added loading="lazy" to all below-the-fold product images for improved page load speed
- Added robots.txt and sitemap.xml at the project root for search engine crawling and indexing
- Reviewed existing meta description, meta keyword, and image alt text coverage across all five pages (already in place from Part 1/2 and confirmed accurate for Part 3 SEO requirements)

---
