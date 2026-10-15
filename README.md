# Parma Pizzeria - website concept

An independent website concept for Pizzeria Parma in Warsaw and Łomianki. The website is in **Polish**; project documentation and code comments are in **English or Polish**.

This is a portfolio demonstration, not an official restaurant website or a commissioned project.

## Preview

Open `index.html` in a modern browser. No installation, dependencies or build step are required. Keep the complete folder, including `assets`, together.

For a local HTTP preview, run this command from the project directory:

```sh
python -m http.server 8080
```

Then visit http://localhost:8080.

## Features

- Responsive desktop and mobile layout.
- Searchable menu with 39 pizzas, pasta, salads, starters and drinks.
- Pizza size selection with corresponding prices, extras and sauces.
- Category filters, expandable lists and a helpful empty state.
- Location selection for Żoliborz and Łomianki with telephone order links.
- Opening hours, contact details, directions and restaurant history.
- Keyboard access, visible focus states and reduced-motion support.
- Locally bundled images and fonts.

## Structure

```text
index.html          Page, menu data and browser interactions
styles.css          Responsive styles and font license notices
assets/             Images and fonts
FONT-LICENSES.txt   Original SIL Open Font License texts
ASSETS.md           Image sources and third-party notices
```

The delivery version intentionally keeps menu data and JavaScript inside `index.html`, so it also works when opened directly from disk. It uses plain HTML, CSS and JavaScript without a framework.

## Project status

The restaurant information and prices reflect a project snapshot from 8 October 2026. They have not been approved by the restaurant owner and should be confirmed before an official launch. This demonstration has no checkout, payment processing, backend or order database. Order buttons open telephone links; no order is submitted automatically.

The independent-concept label and noindex directive remain visible. The original restaurant website is https://pizzeriaparma.pl/.

## Assets and licensing

See [ASSETS.md](ASSETS.md) and [FONT-LICENSES.txt](FONT-LICENSES.txt). Restaurant branding and third-party photographs retain their owners' rights. No blanket license to those assets is granted by this repository.
