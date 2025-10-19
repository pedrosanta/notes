# pedrosanta/notes AGENTS.md

## Project overview

This repository holds the code for a small personal notes blog built with Eleventy and based on the eleventy-base-blog starter project.

## Dev and build commands

- The development command is `npm start` which runs Eleventy development server.

- A build can be achieved with the `npm run build` command, which outputs the built static website for this blog to `_site` folder.

## Deployment

Deployment is done automatically to GitHub Pages with [a GitHub Actions workflow](.github/workflows/gh-pages.yml) as the publishing source, and on each push to the main branch.

The live URL of this blog is [notes.pedrosanta.com](https://notes.pedrosanta.com).

## Next development steps

These are the things Pedro, the author, is thinking about adding to this project:

- Update the theme of the notes blog to a custom theme to the authors liking. He would like to keep the light and dark modes of the theme. A reference for that might be yinkakun/eleventy-duo theme, which doesn't have a dark mode, but shouldn't be hard to add.

- Maybe experiment and use Tailwind CSS on this project.

- Check Vite and also experiment with it. There is [the official Vite plugin](https://github.com/11ty/eleventy-plugin-vite) to help with that, and [the official Eleventy documentation on Vite](https://www.11ty.dev/docs/server-vite/).
