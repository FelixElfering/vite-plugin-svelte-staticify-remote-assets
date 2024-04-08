# vite-plugin-svelte-staticify-remote-assets

Vite plugin for SvelteKit that downloads remote assets to static directory and updates src paths.

```ts
// before
<img src="remote-src.com/img.jpg" alt=... />
```

```ts
// after
<img src="images/img.jpg" alt=... />
```

Inspired by <a href="https://github.com/antfu/vite-plugin-remote-assets">https://github.com/antfu/vite-plugin-remote-assets</a>
