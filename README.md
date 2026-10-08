# Hotel Shivai Restaurant Website

A beginner-friendly responsive restaurant website project built with:

- HTML5 semantic structure
- SCSS/SASS organization
- CSS Grid
- Flexbox
- Responsive media queries
- JavaScript mobile navigation
- JavaScript contact-form validation

## Pages
- `index.html` — Home
- `about.html` — About
- `menu.html` — Menu
- `gallery.html` — Gallery
- `contact.html` — Contact

## Folder structure

```text
hotel-shivai/
├── index.html
├── about.html
├── menu.html
├── gallery.html
├── contact.html
├── scss/
│   ├── _variables.scss
│   ├── _mixins.scss
│   ├── _base.scss
│   ├── _header.scss
│   ├── _components.scss
│   └── style.scss
├── css/
│   └── style.css
├── js/
│   └── script.js
└── images/
```

## Compile SCSS

Install Sass:

```bash
npm install -g sass
```

Then run:

```bash
sass scss/style.scss css/style.css --watch
```

Or compile once:

```bash
sass scss/style.scss css/style.css
```

## Important
Menu prices are intentionally shown as `₹ —` because no verified menu prices were supplied. Replace them with actual prices after confirming with the restaurant.

The contact form is front-end validation only. It does not send email until a backend/email service is connected.
