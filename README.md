# AE Solutions and Company — React Website

A responsive company-profile website recreated from the supplied 24-page PDF.

## Included sections
- Home / company overview
- About the company
- Transmission, maintenance, substation, solar and infrastructure services
- Selected past and ongoing projects
- Quality assurance, HSE and environmental policy
- Organization chart
- Project gallery photographs extracted from the supplied profile where available
- Company credentials (registration categories only)
- Business contact details

## Privacy exclusions
This website intentionally excludes personal identity and banking information from the PDF:
- Aadhaar details and identity-card scans
- PAN number and PAN-card scan
- Cancelled cheque, bank account information and banking imagery
- Proprietor's personal identity details
- Personal registration identifiers

Business registration categories are shown without exposing registration numbers.

## Run locally
Requires Node.js 18+.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually http://localhost:5173).

## Production build
```bash
npm run build
npm run preview
```
The production website is generated in `dist/`.

## Notes
- Project descriptions and statuses are based on the supplied company profile; verify details before formal publication.
- No backend, CMS, contact-form delivery, analytics or admin login is configured.
- Google Fonts are loaded from Google Fonts when internet access is available; system fonts are fallback.
