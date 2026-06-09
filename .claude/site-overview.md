# Thermostar UK – Site Overview

## Repo / Hosting
- GitHub Pages: thermostaruk.github.io → thermostar.org.uk
- Static site, no backend, no build step

## Company
- **VIRIDIAN ALLIANCE LTD** – registered England & Wales No 08871798
- Cumberland House, 80 Scrubs Lane, London NW10 6RF
- Tel: +44 (0) 203 544 8303
- Email: info@thermostar.org.uk
- Social: facebook.com/thermostar.uk | instagram.com/thermostar.uk | LinkedIn

## Current Tech Stack
- Bootstrap 4 (bootstrap.min.css + bootstrap.min.js)
- jQuery 3.4.1
- Google Analytics G-ET6VCH2915

## Current Color Scheme
- Navbar/accents: #C0BDC9 (grayish-lilac)
- Primary buttons: Bootstrap blue

## Pages
1. `index.html` – main page (~1180 lines)
2. `accessories/index.html` – accessories gallery (own CSS/JS stack)
3. `applications.html` – applications page (duplicates modal content)
4. `contact_form.html`, `index_contact_form.html` – legacy/unused

## Main Page Structure (index.html)
- Sticky navbar with dropdowns (Thermostar, The Company, Videos) + "Buy it now!" CTA
- Full-width autoplay muted video hero (video/thermostar-video.mp4)
- Intro text + Facebook feed widget (iframe)
- "You can clean with Thermostar" section (product image + bullet list)
- Jumbotron CTA "Do you want to know more?" → Contact modal
- Water-hands section (blue bg)
- Advantages list section
- Bootstrap modals for ALL content (triggered from nav dropdowns):
  - DrySteamProducts, DrySteamAdvantage, Warranty, ProductsForLife,
    ThermostarTechnology, UserManual, History, Philosophy
  - ProductVideo, TechnologyVideo, ApplicationVideo, SteamIronVideo, TrainingVideo
  - ContactUs (Google Form iframe, 1550px height – clunky)
  - EnT (Equipment and Tools), Applications (28 tabbed application types)
- Footer: address, phone, email, social icons (SVG Bootstrap Icons)

## Products
- **Thermostar Avantgarde S4**: 6 bar, 160°C, 2.85KW, 9.5kg
- **Thermostar Professional S4**: 8 bar, 190°C+, 2.45KW, 9.5kg
- Both: AISI 304 stainless steel boiler, 1.5L boiler, 2L tank, 64g/min steam

## Images Available
images/: logo.png, thermostar-transparent.png, thermostar-old.png,
Thermostar-Avantgarde-S4.png, Thermostar-Professional-S4.png,
dsa.jpg, pfl.jpg, philosophy.jpg, steam.jpg, technology.png, technology2.jpg,
thermostar-testlabor.png, warranty.png, water-hands.jpg, mop.png,
cd2ea770-...jpg (unused)

## Key Issues to Fix in Modernisation
- Google Form iframe embedded in modal = terrible UX
- Facebook feed widget = slow/janky
- Bootstrap 4 = outdated (Bootstrap 5 or Tailwind)
- All content hidden in modals = poor for SEO and UX
- No CSS animations or modern design
- Commented-out snow script still in head
- Multiple old/unused HTML files cluttering root

## YouTube Videos
- Product: I-EW48uhCjs
- Technology: ulVEkMOlfdk
- Application: k1pI_k0mr-E
- Steam Iron: P5JVIpSZ9t4
- Training: u1yxe7DBXWY

## Planned Modernisation
- TBD – awaiting user answers to design questions
- Form: replace Google Form iframe with custom HTML form in popup (like ritello.github.io)
- User to provide ritello form code
