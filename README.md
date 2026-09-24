# Catchhub Landing Page

A responsive front-end recreation of the Catchhub marketing landing page, built with plain HTML and CSS from a provided design mock-up and image assets.
you can check it thorugh this link (https://hanif-builds.github.io/Landing_page01-using--html-css/)

## 

## Project Structure

```
catchhub/
├── index.html          # Page markup (hero, Channels, Messages, In future, footer)
├── style.css            # Layout, typography, colors, decorative shapes
└── images/
    ├── logo.png          # Catchhub wordmark
    ├── favicon.jpg
    ├── top\_screens.png   # Hero section phone screens
    ├── sec\_screens.png   # Channels section phone screens
    ├── thhh\_screens.png  # Messages section phone screens
    ├── for\_screens.png   # In future section phone screens
    ├── vectors.png        # Faded category icon row
    ├── peratude.png       # Footer brand mark
    ├── app\_store.png      # App Store badge
    └── play\_store.png     # Google Play badge
```

## Sections

|Section|Content|
|-|-|
|Hero|Logo, tagline "Watch. Communicate. Create.", subtext, store badges, hero phone mockups|
|Channels|Phone mockups + heading/copy describing channel creation|
|Messages|Heading/copy + phone mockups describing group chat|
|In future|Faded icon row, phone mockups + heading/copy for upcoming features|
|Footer|Download call-to-action, store badges, contact line, Peratude credit|

## Tech Notes

* **Fonts:** Poppins (Google Fonts), loaded via `<link>` in `index.html`.
* **Layout:** CSS Flexbox for all section rows; alternating image/copy order via `.feature--reverse`.
* **Decorative shapes:** Soft blurred "blob" backgrounds built with `border-radius` and gradients, positioned with `absolute` inside each `relative` section — no extra images used for these.
* **Responsive breakpoints:**

  * `900px` — feature rows stack vertically and center-align
  * `520px` — tighter spacing, smaller logo/headings/badges
* All images are the originals supplied in the design package; none were regenerated.

## Customizing

* **Colors:** body text color, heading color, and blob background colors are set directly in `style.css` — search for `#3d3d3d`, `#262626`, and the `.blob` rules.
* **Copy:** all section text lives directly in `index.html` inside `<h2>`/`<p>` tags under `.feature\_\_copy`.
* **Links:** the App Store / Google Play buttons and "Contact us" link currently point to `#` — swap in real URLs when ready.

## Browser Support

Modern evergreen browsers (Chrome, Firefox, Safari, Edge). Uses Flexbox and CSS gradients only — no experimental features.

