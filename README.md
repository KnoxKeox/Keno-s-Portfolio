# Keno Favour — Personal Portfolio

A premium, dark portfolio website built with semantic HTML5 and CSS3 only. There is no JavaScript, framework, package manager, or build step.

## Files

```text
portfolio/
├── index.html
├── css/
│   └── style.css
├── assets/
│   ├── images/
│   └── icons/
└── README.md
```

The `assets/images/` and `assets/icons/` folders are intentionally available for future personal images, project screenshots, a favicon, or social preview image. The current hero illustration and hotel dashboard concept are drawn entirely with CSS, so no external image files are required.

## Open locally

1. Download and extract the `portfolio` folder.
2. Open `index.html` directly in a modern browser.
3. For local testing, navigate through the header and footer links and resize the browser to mobile and desktop widths.

No installation or build process is required.

## Personalise before publishing

Search `index.html` for these items:

- `https://example.com/` — replace with your actual canonical site URL in `og:url`.
- `https://example.com/assets/images/og-preview.jpg` — replace with a real social preview image URL once you create one, or remove the `og:image` metadata until it exists.
- Hotel Management System — verify the exact implemented features, technologies, and project status. The dashboard illustration is a concept preview with illustrative placeholders, not a screenshot or proof of a deployed application.
- GitHub URL — the supplied URL is used as a GitHub portfolio/profile link. If the Hotel Management System has its own repository, replace or supplement the link with that exact repository URL.
- Testimonial placeholder — replace it only with genuine feedback and permission to publish.
- Experience timeline — add verified roles, dates, education, certificates, and achievements as applicable. Do not imply placeholder entries are employment history.
- CV download — add your actual CV PDF, for example `assets/Keno-Favour-CV.pdf`, then add a link with `href="assets/Keno-Favour-CV.pdf"` and the `download` attribute. No CV file was supplied, so no broken download link is included.
- WhatsApp contact — add a verified WhatsApp number/link if you want that option. It was not supplied, so no guessed number or non-working button is included.
- Skills — confirm that the listed skills reflect your current experience and add frameworks or tools only when accurate.
- Availability wording — change the “available” message if it does not reflect your current status.

The email and location currently use the details supplied for this portfolio.

## Design system

- **Base:** deep ink and slate surfaces for a premium technical look.
- **Accent:** electric blue for emphasis, links, and primary actions.
- **Secondary accents:** restrained mint and violet in the CSS code illustration.
- **Typography:** system font stack to avoid external font requests; monospace for technical labels.
- **Layout:** CSS Grid and Flexbox, fluid type, and responsive breakpoints.
- **Accessibility:** semantic landmarks, skip link, visible keyboard focus, descriptive link labels, reduced-motion handling, and a CSS-only mobile navigation toggle.

## HTML/CSS-only limitations

- **Contact form:** no form is included because a static HTML/CSS form cannot send or store messages by itself. The email links open the visitor's configured mail application. A real form requires a backend or trusted form-processing service.
- **Mobile navigation:** the checkbox/label pattern opens and closes the menu without JavaScript. Keyboard users can toggle it. It does not automatically close after selecting a link; this is an honest limitation of this CSS-only implementation.
- **CV:** a download link requires an actual CV file.
- **WhatsApp:** a working link requires the correct phone number or supplied WhatsApp URL.
- **Live project and source code:** only the supplied GitHub URL is linked. Add the exact project repository and live demo URLs when they exist.
- **Dynamic copyright year:** the displayed year is static because JavaScript is prohibited; update it when needed.
- **SEO/social sharing:** update canonical and Open Graph URLs when the website is deployed. Social preview images need to exist at the declared URL.
- **Animations:** CSS transitions and a subtle cursor blink are decorative. Reduced-motion preferences are respected.

## Deploy

This is a static site. Upload the entire `portfolio` folder to any static hosting provider (for example, GitHub Pages, Netlify, Cloudflare Pages, or your own web server). Keep the relative path `css/style.css` intact. No server-side runtime is required for the portfolio itself.

Before deployment:
1. Replace example domain metadata with the production domain.
2. Verify email, social links, project facts, and availability wording.
3. Add the real CV and WhatsApp link only when available.
4. Test navigation, keyboard focus, mobile menu, and all external links.
5. Confirm that the hosting platform serves `index.html` at the site root.

## Quality assurance checklist

- [ ] Open `index.html` directly in a current browser.
- [ ] Confirm all header and footer anchor links reach the correct sections.
- [ ] Test the mobile menu with keyboard and pointer.
- [ ] Check layout at approximately 320px, 375px, 768px, 1024px, and wide desktop widths.
- [ ] Verify no horizontal overflow at narrow widths.
- [ ] Confirm visible focus styles and skip link behaviour.
- [ ] Check contrast and text readability in the browser.
- [ ] Confirm reduced-motion settings disable/shorten animation.
- [ ] Verify every email and external link.
- [ ] Replace all content placeholders and confirm project claims.
- [ ] Add and test real CV, social preview, and project assets if used.
- [ ] Run HTML validation and accessibility/performance audits after final content and assets are in place.

No Lighthouse, Core Web Vitals, automated accessibility, or browser test results are claimed here; run those checks against the final deployed site.
