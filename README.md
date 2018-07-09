# Demo svelte hello world

Demonstration of:

  
  * [Svelte](https://svelte.technology]: JavaScript web framework
  * [Svelte REPL](https://svelte.technology/repl)
  * [Rollup](https://rollupjs.org):

GitHub links:

  * [sveltejs](https://github.com/sveltejs)
  * [sveltejs/template](https://github.com/sveltejs/template)
  * [sveltejs/component-template](https://github.com/sveltejs/component-template)


## Preflight

Verify we have Node and NPM:

```
node --version
npm --version
```


## Start

Clone:

```sh
git clone https://github.com/sveltejs/template demo
cd demo

Install:

```sh
npm install
```

Run using Rollup:

```bash
npm run dev
```

Browse [localhost:5000](http://localhost:5000). You should see your app running.

You can edit any component file in `src`, save it, then reload the browser page to see your changes.


## Deploy

To deploy to the web, there are many choices.

This demo shows how to deploy to the web by using a tool named "now".


### With [now](https://zeit.co/now)

Install `now` if you haven't already:

```bash
npm install -g now
```

Then, from within your project folder:

```bash
now
```

As an alternative, use the [Now desktop client](https://zeit.co/download) and simply drag the unzipped project folder to the taskbar icon.


