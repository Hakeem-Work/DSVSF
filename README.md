# DSVSF static website

Nine independent HTML pages, shared local CSS/JavaScript and a local illustrative image. No build step or backend is required. The community image is AI-generated and illustrative; it does not depict actual DSVSF staff or survivors. The header uses a text-based brand treatment, not the official logo: the official logo could not be obtained from the source in this environment and must be supplied by DSVSF before launch.

## Run and deploy

Serve the folder locally with `python3 -m http.server 8000` and visit `http://localhost:8000`. Upload all HTML files and the `assets` folder to any static host, keeping the folder structure intact. Set `index.html` as the default document. No secrets, server-side components, or sensitive-data forms are used.

For a custom domain, add the domain in the hosting provider's dashboard and follow its specific DNS instructions at your registrar (typically an A/AAAA record or CNAME). Enable HTTPS, verify the certificate and redirect HTTP to HTTPS. DNS propagation can take time.

## Before launch

- DSVSF must confirm ownership of both linked Paystack and Flutterwave accounts and test the live payment pages and receipts. No payment is processed by this website.
- Obtain and install the approved official logo and confirm brand colours and image usage. The local image is illustrative, not documentary evidence.
- Confirm the 24/7 availability, phone and WhatsApp numbers, address, services, impact totals and reporting period with DSVSF. Figures were taken from the live home page (109+, 18+, 8+) on 29 October 2026; indexed search results differed.
- Have DSVSF and qualified privacy counsel review the adapted privacy policy, operational practices, host logs, retention, safeguarding and Nigeria Data Protection Act compliance. Update it if analytics, forms or other features are added.
- Review the linked articles for currency and accuracy, and test all links, mobile navigation, keyboard navigation and screen-reader behaviour on the final host. External services and device/browser histories have their own privacy implications.
- If adding forms or case intake, first commission a secure, properly reviewed backend and safeguarding/privacy assessment; do not collect sensitive survivor information on this static site.

Source: https://dsvsf.org.ng/ and its services, get-involved, donation, and privacy pages, accessed 29 October 2026. The original pages may change.
