# CircNex Technologies — Website (Draft 01)

Modern, responsive static marketing site for CircNex Technologies.

## Pages
- `index.html` — homepage
- `services.html` — service details
- `about.html` — company introduction
- `contact.html` — project inquiry form
- `privacy.html` — draft privacy notice

## Development
No build system is required. Open `index.html` in a browser or serve this directory with any local static server (for example, `python -m http.server 8000`).

## Contact form — IMPORTANT
The form is intentionally in **demo mode**. It validates fields but **does not send inquiries or retain submissions** until a real backend is configured. It never falsely displays “message sent.”

For launch, connect a secure form handler (e.g., a Cloudflare Pages Function with server-side email service and spam protection) in `assets/main.js`. Do not put API keys, passwords, or private email credentials into browser JavaScript or a public GitHub repository. Add spam protection, server-side validation, privacy policy, and delivery testing before launch.

## Launch checklist
- Confirm company contact email, phone, actual service area, policies, and approved services.
- Replace placeholder vector mark with approved CircNex logo, if desired.
- Verify all service statements, insurance/certifications, and any process claims.
- Connect and test inquiry form.
- Review accessibility on mobile, test browser layouts, improve SEO.
- Remove the temporary `noindex` meta tags when the website is ready for production.
- Link Cloudflare Pages to this GitHub repository and optionally attach `circnex.com`.

This project is a draft: it does **not** claim certifications or client results that have not been verified.
