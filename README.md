# TedStack Legacy Portfolio

Clean static deployment copy recovered from the former Hostinger site.

## Deployment
This version is intended as a temporary static portfolio while TedStack v2 is developed in Next.js.

- Entry point: `index.html`
- Static assets: `assets/`
- Resume: included at project root
- Contact form: temporarily replaced with a LinkedIn contact button because the original form depended on PHP/Hostinger mail.
- Removed from deployment: PHP mail handlers and PHPMailer.

## Local preview
Run a simple static server from this directory, for example:

    python3 -m http.server 8000

Then open http://localhost:8000.
