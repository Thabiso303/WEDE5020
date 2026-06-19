# WEDE5020
Web development project

## Project Title
warm hearts Community
This project involves designing and developing a professional five-page website for Thabiso Barber School, South Africa's leading warehouse retailer, which is part of the Massmart group. The website is built using HTML5, CSS, and embedded external services (Google Forms, Google Maps, YouTube, and Instagram). It is designed to give Thabiso's Barber school a credible digital presence, showcase its product categories, allow customers to submit enquiries online, and provide branch location information.

---
## Website Goals and Objectives
- Increase Thabiso's barber digital visibility and brand awareness across South Africa
- Enable customers to browse product categories (Groceries, Household Items, Outdoor Items) online
- Provide clear contact information, trading hours, and six branch location maps
- Allow customers to submit product or service enquiries via an embedded Google Form
- Establish a professional, responsive website that works on desktop, tablet, and mobile devices

---

## Key Features
- Responsive design for desktop (1366px+), tablet (768px), and mobile (480px) screens
- Three product category sections with styled images and hover effects
- Native HTML enquiry and contact forms with client-side JavaScript validation (replacing the Part 2 Google Form embeds)
- Enquiry form processes input asynchronously (AJAX via the Fetch API) and displays a generated availability/pricing response
- Product search bar and category filter buttons (Groceries/Household/Outdoor) for instant client-side filtering
- Image gallery lightbox — click any product image for a full-screen view with keyboard and click navigation
- FAQ accordion with four expandable questions on the Products page
- Scroll-triggered fade-in animations on product and FAQ sections (IntersectionObserver)
- Interactive Leaflet.js map plotting all six branch locations, with a dropdown to fly to any branch
- Three embedded Google Maps showing Thabiso's Barber School branch locations across the world
- Embedded YouTube video and Instagram reel on the Products page
- Consistent header (logo + brand name + red nav bar) and footer across all five pages
- Active page indicator on all navigation links
- CSS hover effects on navigation links, product images, and CTA buttons
- Google Fonts typography (Montserrat headings, Roboto body text)
- SEO meta description, meta keywords, descriptive image alt text, hyphenated image file names, robots.txt, and sitemap.xml on all five pages
- loading="lazy" applied to below-the-fold product images for improved page speed
- HTML comments explaining every section on all five pages
---

## Responsive Design Screenshots


### Desktop View (1366px+)
![Desktop view of Thabiso's Barber School website](images/desktop.png)
The full two-column intro grid, horizontal navigation bar, and 2-column branch map grid display at desktop width.

### Tablet View (768px)
![Tablet view of Thabiso's Barber School website](images/tablet.png)
The intro grid stacks to a single column, navigation font reduces, and maps stack to one column.

### Mobile View (480px)
![Mobile view of Thabiso's Barber school website](images/mobile.png)
The navigation collapses to a vertical list, hero image height reduces, and product images stack to a single column.

---

## Sitemap


Thabiso'Barbae school Website
├── Homepage          (index.html)
├── About Us          (about_us.html)
├── Products          (services_or_products.html)
├── Enquiry           (enquiry.html)
└── Contact Us        (contact_us.html)


All five pages are accessible directly from the main navigation bar on every page.

