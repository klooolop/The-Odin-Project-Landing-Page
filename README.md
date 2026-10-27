# Serial Experiments Lain — Landing Page

A responsive-ish landing page built for the **Flexbox → Project: Landing Page** assignment in [The Odin Project](https://www.theodinproject.com/) curriculum. The page is themed around the anime *Serial Experiments Lain* and its world, "the Wired".

Everything here was written by hand in plain HTML and CSS. No frameworks, no libraries, no AI. Just the lessons, the docs, and a lot of googling.

## Live Preview

> https://klooolop.github.io/The-Odin-Project-Landing-Page/

## What's on the page

- **Header** with the logo and navigation links (Wikipedia, Trailer, Opening)
- **Hero section** with a headline, short blurb, call-to-action button and image
- **Core Concepts of the Wired**: four cards with an image and a short description each
- **Quote block** featuring a line from Lain Iwakura
- **Call-to-action banner** with a sign-up button
- **Footer** with copyright

## What I practiced

- Layouts with **Flexbox** (`justify-content`, `align-items`, `gap`, `flex-direction`)
- Building a page from sections: header, main, aside, section, article, footer
- Sizing and cropping images with `object-fit`
- Styling links and buttons, including hover states and transitions
- Keeping the footer at the bottom of the page with a column flex body and `flex: 1` on `main`
- Importing and using Google Fonts (Roboto)

## Project structure

```
.
├── index.html
├── css/
│   └── lain.css
├── images/
│   ├── Copland.webp
│   ├── cyberia.jpeg
│   ├── knight.jpeg
│   └── laininbari.jpeg
└── README.md
```

## Run it locally

```bash
git clone https://github.com/klooolop/The-Odin-Project-Landing-Page.git
cd The-Odin-Project-Landing-Page
```

Then open `index.html` in your browser.

## Credits

- Assignment and design brief: [The Odin Project](https://www.theodinproject.com/)
- Hero image: [Wallhaven](https://wallhaven.cc/)
- *Serial Experiments Lain* and all related characters and artwork belong to their respective creators. This is a non-commercial, fan-made practice project.
