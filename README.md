<h1 align="center">💨 Add Tailwind CSS to Svelte</h1>

This is an adder for `svelte-add`; you should [read its `README`](https://github.com/svelte-add/svelte-add#readme) before continuing here.
&nbsp;  
&nbsp;  
&nbsp;  

## ➕ Adding Tailwind CSS

This adder's codename is `tailwindcss`, and can be used like so:

```sh
npx svelte-add@latest tailwindcss
```
&nbsp;  
### 🏞 Supported environments

This adder supports SvelteKit and Vite-powered Svelte apps (all the environments `svelte-add` currently supports).

&nbsp;  
### ⚙️ Options

&nbsp;  
- `forms` (default `false`): whether or not to install and set up the [Tailwind CSS Forms plugin](https://github.com/tailwindlabs/tailwindcss-forms).

```sh
npx svelte-add@latest tailwindcss --forms
```

&nbsp;  
- `typography` (default `false`): whether or not to install and set up the [Tailwind CSS Typography plugin](https://github.com/tailwindlabs/tailwindcss-typography).

```sh
npx svelte-add@latest tailwindcss --typography
```

&nbsp;  
- `daisyui` (default `false`): whether or not to install and set up [daisyUI](https://github.com/saadeghi/daisyui) as a Tailwind plugin.

```sh
npx svelte-add@latest tailwindcss --daisyui
```

&nbsp;  
### ⚙️ Don't forget do run npm install after that.

```sh
npm install
```

&nbsp;  
&nbsp;  
&nbsp;  
## 🛠 Using Tailwind CSS

After the adder runs,

- You can use Tailwind utility classes like `bg-blue-700` in the markup (components, routes, `app.html`).

- You can use [Tailwind directives like `@apply` and `@screen` or use the `theme` function](https://tailwindcss.com/docs/functions-and-directives) in Svelte `style lang="postcss"` blocks or the `src/app.postcss` file.

- You can [configure Tailwind](https://tailwindcss.com/docs/configuration) in the `tailwind.config.cjs` file.

- Your Tailwind CSS will be purged for production builds.
