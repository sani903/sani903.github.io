# Sanidhya Vijayvargiya — research website

Static academic website ready for GitHub Pages.

## Pages
- `index.html` — homepage, research interests, recent projects, news
- `research.html` — retrospective research overview connecting public projects across grounding, interaction/context, and evaluation
- `publications.html` — full publication list
- `cv.html` — embedded CV with open/download actions

## Assets
- `assets/profile.jpeg` — profile photo
- `assets/Sanidhya_Vijayvargiya_CV.pdf` — CV
- `assets/favicon.svg` — favicon

## Deploy to GitHub Pages
1. Create a repository named `sani903.github.io` (for a root personal site) or any repository for a project site.
2. Copy this folder's contents to the repository root.
3. In GitHub: Settings → Pages → Deploy from branch → `main` / root.

Light/dark mode follows the OS initially and remembers a visitor's manual choice.

## Responsive behavior
- Desktop: two-column profile + bio, two-column project grid, embedded CV.
- Mobile: stacked profile/bio, single-column projects/publications, scroll-safe navigation, larger touch targets.
- The embedded CV is hidden on narrow screens in favor of direct PDF open/download links, which render more reliably on mobile browsers.
