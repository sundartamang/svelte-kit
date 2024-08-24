# create-svelte

```bash
npm run dev
```

## node version required
22 + 

### Project structure 
- In the package.json file, the type is set to module, which means that .js files are interpreted as native JavaScript modules (supporting import and export keywords).

- The svelte.config.js file exports a config object. By default, we have an adapter configuration (adapters take the built application as input and generate output for deployment).

- vite.config.js is for Vite plugins.

- The .svelte-kit folder is generated when we run or build the project (it is from this folder that our SvelteKit application is served).

- app.html has three placeholders (head, body, and link href).