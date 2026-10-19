# Summit Ridge Outfitters

Summit Ridge Outfitters is a responsive outdoor retail website concept for a Colorado gear shop. It features a gear-focused home page, adventure guide articles, and URL-hash navigation between site sections.

## Project Link

https://in-info-web4.luddy.indianapolis.iu.edu/~ccucuiet/N315/homework-05/

## Features

- Single-page navigation using URL hashes, such as `#home` and `#contact`.
- Home page with featured gear, product categories, adventure inspiration, customer reviews, and an email signup area.
- Adventure Guides page with outdoor skills and trip-planning articles.
- Shared header navigation and footer across the site.
- Sass source files compiled into the stylesheet used by the page.

## Built With

- HTML
- JavaScript modules
- Sass (SCSS)
- `live-server` for local development

## Run Locally

You will need Node.js and npm. From the project directory, install the dependencies:

```sh
npm install
```

The `serve` script uses `live-server`. Install it globally if it is not already available:

```sh
npm install --global live-server
```

Start the Sass compiler in one terminal:

```sh
npm run compile
```

Start the local web server in a second terminal:

```sh
npm run serve
```

Open the local address printed by `live-server`. Keep both commands running while you work. The Sass watcher rebuilds `css/styles.css` when files in `scss/` change.

## Pages

| URL hash | Section |
| --- | --- |
| `#home` | Shop home page |
| `#about` | Adventure Guides |
| `#services` | About Us |
| `#contact` | Contact |

The About Us and Contact routes currently display basic placeholder content.

## Project Structure

```text
app/       Application startup and hash-change navigation
css/       Compiled stylesheet loaded by index.html
images/    Site image assets
model/     Route-to-page rendering
pages/     Home, Adventure Guides, About Us, and Contact content
scss/      Sass source stylesheets
index.html Site shell and shared header/footer
```
