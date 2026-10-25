GAGU FITNESS CENTER — STATIC CPANEL WEBSITE
===========================================

CONTENTS
- index.html          Main responsive website
- styles.css          Black, orange and gold visual styling and responsive layouts
- script.js           Navigation, reveal effects, form submission and optional analytics
- config.js           Business contact details and Google Analytics setting
- contact.php         Contact form email handler for PHP-enabled cPanel hosting
- assets/gagu-logo.jpg  Uploaded Gagu logo reference
- robots.txt / sitemap.xml  SEO starter files

DEPLOY TO STANDARD CPANEL
1. Download and extract the ZIP on your computer.
2. In cPanel, open File Manager and enter public_html (or the chosen domain's document root).
3. Upload the website files and assets folder contents. index.html should be directly inside the document root, not nested inside another folder.
4. Open config.js and fill in phoneDisplay, phoneLink, whatsappNumber, email, address, and analyticsId as needed.
5. The contact form recipient is set to info@gagufitnescentre.co.za. Confirm this mailbox exists and receives email before launch.
6. Replace YOUR-DOMAIN.co.za in sitemap.xml and robots.txt with the actual live domain.
7. Test the site on desktop and mobile, and submit a test enquiry. Your hosting account must support PHP mail() for the form to send email. Some hosts disable or restrict PHP mail; if so, use the host's authenticated SMTP details or a trusted form service.
8. Configure SSL/HTTPS in cPanel and test every link after deployment.

IMPORTANT BUSINESS DETAILS TO ADD
- Phone / WhatsApp: 066 315 2537
- Email: info@gagufitnescentre.co.za
- Street address / town and map location
- Opening hours
- Confirmed training services and equipment
- Actual membership rates, joining fees, duration and benefits
- Real trainer names, qualifications and photos, if you want a trainer section
- Social media URLs
- Google Analytics measurement ID, if used

CONTACT FORM
The form validates fields in the browser and on the server, uses a honeypot field, and submits to contact.php. It intentionally will not send until you configure a real recipient email address. PHP mail() delivery depends on the hosting provider's mail setup; SMTP may be needed.

WHATSAPP
WhatsApp is configured for 066 315 2537 (international format 27663152537). The contact section includes a direct WhatsApp link; the floating button takes visitors to the enquiry form.

IMAGES / LOGO
The Gagu logo supplied in this conversation is included. Gym photography is loaded from Unsplash over the internet and requires a connection. Replace image URLs in index.html and styles.css with owner-approved gym photos before launch. Current photos are illustrative and are not represented as actual Gagu facilities or members.

BRANDING NOTE
The supplied logo uses black, white and yellow-gold. The website keeps a black base and uses orange for buttons/highlights while retaining the logo unchanged. If you want exact logo-matched yellow instead of orange accents, change --orange in styles.css to #F5C928.

SEO
Update title, description, Open Graph details and sitemap domain before launch. Add real business details and a privacy notice suitable for the gym's data collection practices.

No Node.js or build step is required on the live server.
