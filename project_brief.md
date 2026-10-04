# NevX Studio — confirmed project brief

## Brand and audience
NevX Studio, a full-service creative, marketing and development studio for mixed business clients. Positioning: premium-quality work at fair prices. Tagline: Premium Creatives for Growing Brands.

## Design
Black and electric blue, silver/cyan accents, supplied logo, premium balanced 3D hero. Mobile-first, usable on phones and computers. English only. Google Fonts with system fallbacks.

## Services
Graphic design, logos, branding, video editing, AI videos, product creatives, scripting, content creation, marketing, SEO, website development, UI/UX and app development. Service categories and filters. Concept portfolio imagery is labelled; no fabricated clients or testimonials.

## Latest build instructions (override earlier choices)
Plain HTML/CSS/vanilla JavaScript. No npm, frameworks or build process. Pages: index, shop, product (URL id), cart, about, contact. Prices shown in PKR (Rs.), using the numeric amounts from the supplied plan PDF. Confirm PKR before launch. Custom services have no invented prices and require a quote.

## Cart and checkout
Add services and plans, update quantity, remove, total priced items, persist using localStorage. Name, phone and address form opens WhatsApp with selection details. Custom-priced items are excluded from the subtotal and flagged as requiring a quote. Monthly and one-time billing labels are explicit. No automatic order confirmation or payment collection. UPI ID and QR are placeholders until provided.

## Contact
WhatsApp: +92 321 5716434 (wa.me/923215716434).
Email: nevxstdudio.official@gmail.com (exact spelling provided).
Inquiry form includes reference URL; files can be attached in WhatsApp. Consultation preferred date/time requests go to WhatsApp.

## Integration requirements
Google Calendar available-slot booking needs an owner-provided public booking URL (NEVX_CONFIG.bookingUrl). Secure admin, shared inquiry storage and booking management need authenticated services and cannot be implemented securely with static browser-only files. No admin page is included; edit js/products.js directly. No client login.

## Hosting
Static GitHub + free hosting; Netlify preferred. No deployment requested in this build. No domain purchased or live calendar/payment configured.
