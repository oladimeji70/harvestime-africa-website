# HIBI Africa — Static Website Package

This folder contains a simple, fast site for **Harvestime International Bible Institute (USA) – African Directorate** (HIBI Africa).

## Pages
- `/index.html` (Home)
- `/about.html`
- `/programs.html`
- `/faculties.html`
- `/admissions.html` (email-based application form)
- `/chapters.html`
- `/leadership.html`
- `/contact.html`

## Quick Deploy on Vercel
1. Go to https://vercel.com → Team: **HIBI Africa** → **Add New Project** → **Upload**.
2. Upload the ZIP (`hibiafrica-site.zip`) or this folder.
3. Visit: `https://hibiafrica.vercel.app` (preview).
4. Connect your domain in Vercel → **Settings → Domains → Add Domain** → `hibiafrica.org`.
5. At your domain registrar, add the DNS records Vercel shows (usually A: 76.76.21.21 and CNAME: cname.vercel-dns.com).

## Emails
Use Google Workspace or Zoho to create:
- info@hibiafrica.org
- admissions@hibiafrica.org
- provost@hibiafrica.org

Add MX/SPF/DKIM/DMARC records as provided by your email provider.

## Admissions (today)
The current Admissions page uses a **mailto** workflow so it works instantly.
When you’re ready, we will connect:
- **Portal (Moodle)** at `/portal` for full online applications and payments (Paystack/Flutterwave).

## Customization
- Edit text in each `.html` file.
- Colors and layout in `/assets/css/style.css`.
- Simple behaviors in `/assets/js/main.js`.

© 2025 HIBI Africa. Under the auspices of Harvestime International Network (USA).
