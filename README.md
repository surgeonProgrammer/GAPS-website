# GAPS Website (Modern Rebuild)

Modern static website for the **Ghana Association of Paediatric Surgeons (GAPS)**.

## What is included

- Modern responsive homepage and section pages
- Registry section removed from primary site navigation
- Contact and membership forms submit via email client to:
  - `gapsghana.gh@gmail.com`

## Project structure

- `index.html` — homepage
- `about.html`, `heroes.html`, `research.html`, `newsevents.html`, `members.html`, `contact.html`
- `register.html` — membership application form

## Form submission behavior

When users submit the contact or membership form, the browser opens the default email app with a pre-filled message addressed to:

- `gapsghana.gh@gmail.com`

If a user does not have a configured email app, they can manually send details to the same address.

## Local preview

```bash
cd "/Users/jessicadei-asamoa/Library/CloudStorage/Dropbox/SOFTWARE ENGINEERING/PAEDIATRIC SURGERY/GAPS/GAPS website New"
python3 -m http.server 5500
```

Then open:

- `http://localhost:5500/index.html`

## Hosting

This is static and can be hosted on:

- Netlify
- Vercel (static)
- GitHub Pages

Make sure all files (including `Images/`) are deployed together.
