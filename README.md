# Welcome to Megrez Static Website template repository supported by Astro!

## This is a template to get you started on client projects which empathises on Static Web development using Astro.

The template provides a guide on the file structure, linting rules, formating and libraries used in a typical Static Website development. If there are any specific libraries you would like to swap out (eg redux toolkit / mobx), approach your tech lead to discuss before doing so and only once the template is cloned in your repository. For styling, the template uses tailwind CSS as default however if you prefer other styling choices, discuss with your tech lead and swap out the libraries as required.. For more best practices and Megrez coding style, refer to the readme in Megrez organisation github page.

## Resources

- [Astro Documentation](https://docs.astro.build/en/getting-started/)
- [Tailwind CSS Documentation](https://tailwindcss.com)
- [Tailwind integration with Astro](https://docs.astro.build/en/guides/integrations-guide/tailwind/)
- [Eslint documentation](https://eslint.org/docs/l)

## 🚀 Project Structure

Inside of this template, you'll see the following folders and file:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

As this is an Astro projet, it looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
