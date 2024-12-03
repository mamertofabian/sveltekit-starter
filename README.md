# sv

Everything you need to build a Svelte project, powered by [`sv`](https://github.com/sveltejs/cli).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npx sv create

# create a new project in my-app
npx sv create my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://svelte.dev/docs/kit/adapters) for your target environment.

## How this was created

npx sv create sveltekit-starter
┌ Welcome to the Svelte CLI! (v0.6.6)
│
◇ Which template would you like?
│ SvelteKit minimal
│
◇ Add type checking with Typescript?
│ Yes, using Typescript syntax
│
◆ Project created
│
◇ What would you like to add to your project? (use arrow keys / space bar)
│ prettier, eslint, vitest, tailwindcss, drizzle, lucia
│
◇ tailwindcss: Which plugins would you like to add?
│ typography, forms, container-queries
│
◇ drizzle: Which database would you like to use?
│ SQLite
│
◇ drizzle: Which SQLite client would you like to use?
│ libSQL
│
◇ lucia: Do you want to include a demo? (includes a login/register page)
│ Yes
│
◇ Which package manager do you want to install dependencies with?
│ npm
│
◆ Successfully setup add-ons
│
◆ Successfully installed dependencies
│
◇ Successfully formatted modified files
│
◇ Project next steps ─────────────────────────────────────────────────────╮
│ │
│ 1: cd sveltekit-starter │
│ 2: git init && git add -A && git commit -m "Initial commit" (optional) │
│ 3: npm run dev -- --open │
│ │
│ To close the dev server, hit Ctrl-C │
│ │
│ Stuck? Visit us at https://svelte.dev/chat │
│ │
├──────────────────────────────────────────────────────────────────────────╯
│
◇ Add-on next steps ──────────────────────────────────────────────────╮
│ │
│ drizzle: │
│ - You will need to set DATABASE_URL in your production environment │
│ - Run npm run db:push to update your database schema │
│ │
│ lucia: │
│ - Run npm run db:push to update your database schema │
│ - Visit /demo/lucia route to view the demo │
│ │
├──────────────────────────────────────────────────────────────────────╯
│
└ You're all set!
