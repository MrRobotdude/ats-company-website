# ATS Company Website

Public company presentation for PT. Alam Tehnik Semesta: HVAC products, services, project references, and company information.

**Live website:** https://mrrobotdude.github.io/ats-company-website/

This standalone repository owns the React source and GitHub Pages deployment. Doddie Prawarjito’s personal portfolio only links to this site. Prepared current source was transferred from the private ats-kit-react repository; its historical commits and local environment files were deliberately excluded. Template and company attribution remain in the source and license.

## Run locally

Node.js 22 and npm are used by CI.

```powershell
npm ci
npm start
# Production build
npm run build
```

Configuration is documented in .env.example. React environment values are public browser configuration; never place server secrets in them. Static hosting does not run ats-back-go. Contact submission needs an owned API and public CAPTCHA site key; it remains disabled without that configuration.

## Deployment

GitHub Actions builds the source and publishes build/ to this repository’s GitHub Pages site on pushes to main. HashRouter supports direct page links without a server-side router.

## Credits

Now UI Kit React / Creative Tim attribution and third-party licenses are retained. Company identity, catalogue imagery and brand content belong to their respective owners.
