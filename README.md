# Responsive Landing Page

A single-file, responsive landing page for a fictional technology/design studio. Dark, glassmorphic aesthetic with a cyan-to-violet gradient accent, built with plain HTML/CSS and a few lines of vanilla JavaScript.

## Features

- **Sticky, scroll-aware navbar** — starts transparent with a blur backdrop, then condenses (shrinks height, solidifies background, adds shadow) once the page is scrolled past 50px
- **Animated nav underline** — links get a glowing gradient underline and a subtle lift on hover
- **Hero section** — full-viewport intro with a gradient headline, glowing background orbs, a pill-shaped tag, and a call-to-action button
- **Services section** — three glassmorphic cards (Web Development, UI/UX Design, Innovation) that lift and glow on hover
- **About section** — a frosted-glass info panel describing the studio
- **Contact section** — radial-gradient background with a `mailto:` call-to-action button
- **Footer** — copyright and credit line
- **Fully responsive** — breakpoints at 768px and 480px adjust type scale, nav spacing, and card layout for tablet and mobile



## Usage

1. Open `responsive_landing_page.html` in any modern browser.
2. Scroll to see the navbar transition.
3. Click a nav link (Home / Services / About / Contact) to smooth-scroll to that section (`scroll-behavior: smooth` on the `html` element).
4. Click **Get In Touch** to open a pre-addressed email draft (`mailto:hello@example.com`) — update this address before publishing.

No installation, dependencies, or build step required.

## Structure

| Section     | Purpose                                           |
|-------------|---------------------------------------------------|
| `.navbar`   | Fixed top navigation with logo and links          |
| `.hero`     | Full-screen intro with headline, tagline, and CTA |
| `.services` | Three-card grid of offerings                      |
| `.about`    | Studio description in a bordered panel            |
| `.contact`  | Closing CTA with email link                       |
| `footer`    | Copyright and credit                              |



## Credit

Made with ♥ by Devaki
