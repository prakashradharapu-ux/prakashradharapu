# Prakash Radharapu — Professional Portfolio

A fully responsive, accessible, dark-mode portfolio website built with **HTML, CSS, and vanilla JavaScript**. It has **no build step and no npm dependencies**; open `index.html` to view it, or deploy the folder to any static host (Netlify, Cloudflare Pages, GitHub Pages, or Vercel).

## Run locally

From this folder, run:

```bash
python -m http.server 8000
```

Open http://localhost:8000 in a browser. You can also open `index.html` directly.

## Publish free with Vercel

1. Create a GitHub repository and upload the **contents** of this folder.
2. Import that repository into Vercel.
3. Choose **Other** as the framework preset. Leave the build command empty and set the output directory to `.` (project root) if asked.
4. Deploy. Vercel will give you an HTTPS URL.

## Before making it public

- **Confirm your work history.** The latest resume version supplied lists WSFS Bank, Lloyds Bank, and Optum. Previous resume versions showed a different third employer; the website now reflects the requested correction. Validate client names, dates, locations, technical stacks, and what is safe to disclose.
- **Review your email and LinkedIn.** They are populated from your resume and linked from Contact.
- **Add GitHub only when you have the actual URL.** The placeholder is intentionally not clickable.
- **Project verification.** The real-time analytics project is described in a resume but no public repo was provided. Other projects are explicitly labeled *build blueprints* (not completed work). Add actual code, tests, demos, architecture diagrams, and reproducible metrics before relabeling them.
- **Resume button.** Intentionally omitted until you provide a verified, sanitized final resume PDF you want public.
- **Certification wording.** Excluded because the provided resumes mix certifications and course completions. Add credentials only after verification.
- **Privacy.** A portfolio is public by design; do not publish internal banking code, architecture, data, screenshots, secrets, credentials, or non-public metrics.

## Site features

- Responsive navigation and accessible section links
- Functional project filters and expandable architecture summaries
- Contact email, LinkedIn, email-copy action
- Semantic HTML, keyboard focus styles, reduced-motion support, metadata, favicon
- No analytics, third-party tracking, or backend

## Files

- `index.html` — content and site structure
- `styles.css` — visual design and responsive layout
- `script.js` — interaction logic
- `assets/favicon.svg` — browser favicon

Google Fonts are optional and fall back to system fonts if blocked.
