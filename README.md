# Trillo

<p align="center">Github Pages: <img src="https://img.shields.io/github/deployments/jorgeyza/trillo/github-pages" alt="github-pages deployment status" /></p>

Website for a fictional all-in-one booking app (hotel, flight, car, tours).

Project based on the Udemy course [Advanced CSS and Sass: Flexbox, Grid, Animations and More!](https://www.udemy.com/course/advanced-css-and-sass/).

To run the project just open the index.html file with your preferred browser.

Deployed with GitHub pages. You can view the [live version here](https://trillo.jorgeyza.com/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command             | Action                                                                                   |
| :------------------ | :--------------------------------------------------------------------------------------- |
| `pnpm watch:sass`   | Watch changes made to sass files. Generates `css/style.css` AND `css/style.css.map`      |
| `pnpm compile:sass` | Compile `sass/main.scss`. Generates `css/style.comp.css` AND `style.comp.css.map`        |
| `pnpm concat:css`   | Concatenate `css/icon-font.css` AND `css/style.comp.css` into `css/style.concat.css`     |
| `pnpm prefix:css`   | Add vendor prefixes to `css/style.concat.css` and output into `css/style.prefix.css`     |
| `pnpm compress:css` | Compile and compress `css/style.prefix.css` into `css/style.css` AND `css/style.css.map` |
| `pnpm build:css`    | Run `compile:sass` AND `concat:css` AND `prefix:css` AND `compress:css` sequentially     |

## Highlights of the project

- Animations with @keyframes, animation, and transition;

- Use of selectors, pseudo-classes, and pseudo-elements;

- Use of Sass features for setting global variables, building for reusability, architecting CSS (7-1 rule), and managing media queries;

- Setting up a development process to compile Sass and automatic browser reload, and creating a build process to concatenate, prefix, and compress CSS files;

- Responsive design. Flexbox.
