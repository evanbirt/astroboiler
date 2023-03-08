# astroboiler

Default blog template, the expected out-of-box behavior

## Getting Started

Clone and run:

```
$ git clone https://github.com/evanbirt/astroboiler.git
$ cd astroboiler
$ npm run dev
```

Update `/src/data/const.ts` with your info, that's it!

See Astro docs, [here](https://docs.astro.build/).

## Project Structure

```
├── public/
├── src/
│   ├── components/
│   ├── content/
│   ├── data/
│   ├── layouts/
│   ├── pages/
│   └── styles/
├── astro.config.mjs
├── LICENSE
├── package.json
├── README.md
└── tsconfig.json
```

## Commands

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build production site to `./dist/` w/typchecking |
| `npm run preview`      | Preview build locally, before deploying          |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |
| `npm run format`       | Run Prettier formatting                          |

## Credit

Stylesheet by [Bear Blog](https://github.com/HermanMartinus/bearblog/).
