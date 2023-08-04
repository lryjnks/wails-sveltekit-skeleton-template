# README

## About

This is a template for a Wails application with a SvelteKit frontend. It is using the popular [Skeleton](https://www.skeleton.dev/) Component Library combined with [TailwindCSS](https://tailwindcss.com/). This template uses [adapter-static](https://kit.svelte.dev/docs/adapter-static) to make generated files embeddable. And [SSR](https://kit.svelte.dev/docs/page-options#ssr) is disabled by default to make it work with Wails.

### Installing pnpm

https://pnpm.io/installation

### Creating a Project

```sh
wails init -n YOUR_PROJECT_NAME -t https://github.com/robin-samuel/wails-sveltekit-skeleton-template
```

`wailsjs` modules is located in `/frontend/src/lib` so that you can call them like `$lib/wailsjs/go/main/App` in svelte files.

## Live Development

To run in live development mode, run `wails dev` in the project directory. In another terminal, go into the `frontend`
directory and run `npm run dev`. The frontend dev server will run on http://localhost:34115. Connect to this in your
browser and connect to your application.

## Building

To build a redistributable, production mode package, use `wails build`.
