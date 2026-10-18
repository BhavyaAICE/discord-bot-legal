Hades MM & Exchange — Netlify-ready static site

Files:
- index.html       Landing page
- terms.html       Terms of Service
- privacy.html     Privacy Policy
- netlify.toml     Basic static publishing and security headers

DEPLOY WITH NETLIFY:
1. Extract this ZIP.
2. Before deploying, open terms.html and privacy.html and replace every
   [ADD A SUPPORT EMAIL OR SUPPORT URL] placeholder with a contact method you control.
3. Review the policy wording so it accurately reflects your bot's real data handling,
   providers, and retention practices.
4. In Netlify, choose Add new site > Deploy manually, then drag the extracted
   folder (or its contents) into the drop area. Keep index.html, terms.html,
   privacy.html, and netlify.toml together at the published root.
5. After deployment, test these URLs:
   https://YOUR-SITE.netlify.app/
   https://YOUR-SITE.netlify.app/terms.html
   https://YOUR-SITE.netlify.app/privacy.html
6. Paste the terms.html URL into Discord Developer Portal > General Information >
   Terms of Service URL, and privacy.html into Privacy Policy URL.

Important: This is a template, not legal advice. Do not publish with the contact
placeholder still present. Netlify deployment does not itself mean Discord has
approved the application for verification.
