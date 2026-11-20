# CircNex Technologies — Website redesign (Draft 02)

Official website development repository for CircNex Technologies.

> **Development only.** The contact form is in demo mode; the website is not yet connected to an inquiry-processing backend. Pages currently include a `noindex,nofollow` robots instruction.

## Pages
- `index.html` — homepage (four technical services, vendor field support, company overview, equipment purchasing, process)
- `services.html` — four distinct technical services and separate vendor field-support arrangements
- `about.html` — company introduction, mission, vision
- `faq.html` — common questions, including candid certification/security information
- `contact.html` — contact information and inquiry form
- `privacy.html` — **draft** privacy notice, not a finished legal policy

## Brand
- Site style: premium dark navy, deep teal, blue and green accents.
- Tagline: **Install. Retire. Recycle.**
- Homepage headline: **From Installation to Retirement — CircNex Keeps Technology Moving.**
- `assets/approved-mark.svg` contains a cropped/optimized version of the **actual logo provided by CircNex's owner**. The mark is optimized for web navigation; the owner-provided high-resolution source remains the master.
- Main site styles/scripts: `assets/redesign.css` and `assets/redesign.js`. The earlier `assets/styles.css` and `assets/main.js` are retained temporarily as a first-draft archive and are not loaded by these pages.

## Photography (illustrative images)
The draft loads photographs directly from Unsplash's image CDN. Images illustrate a type of service; they are **not** CircNex team, equipment, customers, locations, or completed projects. Attribution isn't legally required under the Unsplash License but is recorded here for transparency.

- Deployment/service laptop: Albert Vinas — https://unsplash.com/photos/F3t-AzyTbyU
- Refurbishment/CPU: JESHOOTS.COM — https://unsplash.com/photos/DQBHliTwIaU
- Retired used computers: Hugo Clément — https://unsplash.com/photos/IvUCu_u5hjI
- Workstation/monitors: Huy Phan — https://unsplash.com/photos/IO3_vOUwjVs
- Network rack/cabling: Yuriy Vertikov — https://unsplash.com/photos/c-lSQecD9oI
- Hero office desk: Deliberate Directions — https://unsplash.com/photos/ieDXimQcLeM

Source license: https://unsplash.com/license

For production, consider downloading and optimizing appropriately licensed images as local assets to avoid dependencies on third-party image hosting.

## Contact form: demo mode only
The Contact page form provides required fields and browser-side validation. Submitting it intentionally **does not send or save** data and displays an accurate warning. **Do not claim inquiries are being delivered before connecting the production form service.**

Production options:
- Cloudflare Pages Functions with Turnstile + a transactional mail service, or
- another well-supported form backend with server-side validation and spam protection.

Configure mail delivery to **info@circnex.com** after the business mailbox is active. Never expose private API keys or mail credentials in frontend JavaScript or in a public repository.

## Before launching at circnex.com
1. Confirm real email mailbox, phone number (if public), service area, business registration and actual service capability.
2. Confirm the current Facebook, Instagram, and LinkedIn business-profile links remain accurate.
3. Connect and test the contact form (delivery, privacy, spam prevention, accessibility, data retention).
4. Confirm any third-party downstream processing relationships and claims before referencing them as actual partners.
5. Replace stock photography with approved CircNex project photos when available.
6. Have the privacy policy reviewed for the actual data flows.
7. Test mobile, desktop, performance and keyboard accessibility.
8. Remove `noindex,nofollow` only when the website is ready for indexing.
9. Deploy to a business-friendly host such as Cloudflare Pages and attach the domain.

## GitHub Pages preview
This is a static HTML/CSS/JS site, so GitHub Pages can preview it when enabled in repository settings under branch `main`, folder `/(root)`. GitHub Pages should be used here for **development preview**, not as a long-term commercial website host.
