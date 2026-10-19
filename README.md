# Grid landing page

A static landing page built with HTML and Tailwind CSS v4.

## Getting started

Install the project dependencies:

```sh
npm install
```

Build the stylesheet once:

```sh
npm run build
```

For development, keep the Tailwind CLI running so it rebuilds the stylesheet
whenever the source styles or HTML change:

```sh
npm run watch
```

Open `index.html` in a browser. It loads the generated `src/output.css`.

## Working with styles

- Edit `src/input.css` for Tailwind imports and project-wide theme values.
- Define or update design tokens in the `@theme` block. For example, the
  `--color-blue-*` variables define the project's custom blue palette and can
  be used through Tailwind color utilities such as `bg-blue-600`.
- Add Tailwind utility classes to elements in `index.html`; the CLI scans the
  project for used classes and includes their styles in the build.
- Treat `src/output.css` as generated output. Do not edit it directly; rebuild
  it with `npm run build` or let `npm run watch` regenerate it.
