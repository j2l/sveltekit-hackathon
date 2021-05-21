export let content = ` (This is the README.md file. This file is a hack too, md seen as JS!)

# THIS IS NOT READY YET!!
I publish it to get some help

# Sveltekit Hackathon based on SvelteKit Demo App with Auth and 2 Supabase tables

Everything you need to build a Svelte project, powered by [\`create-svelte\`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte);

## Creating a local hackathon project

Clone this project from this page, install packages, then run it.

\`npm i\`

\`npm run dev\`

Go to http://localhost:3000

Adapt \`.env\` file to your needs (Only environment variables prefixed with VITE_ are exposed, see \`src/lib/Env.js\`)

## Add stuff & Doc extracts (HackSheet)
Modify svelte compoments from \`/src/routes\` and \`src/lib\`

\`src/routes/index.svelte\` is the root of your site.

\`src/routes/__layout.svelte\` is the layout for every page (like a template) AND the navigation.

A file called either \`src/routes/about.svelte\` or \`src/routes/about/index.svelte\` would correspond to the \`/about\` route.

Dynamic parameters are encoded using [brackets]. \`src/routes/[category]/[item].svelte\` or \`src/routes/[category]-[item].svelte\`.

Underscore: \`src/routes/foo/_Private.svelte\` or \`src/routes/bar/_utils/cool-util.js\`, is hidden from the router, but can be imported by files that are not.

Put your static files (images, video, ...) into \`static/\`.

## CSS
Hackathon is about showing your MVP.
Choose a color scheme you all like, for example from https://coolors.co/

Adapt \`src/style.scss\` accordingly

\`npm run css-build\` to generate \`src/style.css\`

Get some members of your team on building the pages with some "lorem ipsum".

I found Bulma is the most simple and fastest way to make it within svelte component while others are coding.

If you have other faster solutions, feel free to PR.

# Supabase
Visit https://supabase.io
You need to create a free account, an org, a project, and 2 tables within this project.

Once created, your project has an URL identifier, <urlofyourproject>, like mmmkjtghrmfhxfmkjh.

Get your public anonymous key and URL from https://app.supabase.io/project/<urlofyourproject>/settings/api

The public table is a basic table with at least 2 columns : \`permalink\` and \`name\`

The user table is a table where user can only see their inputs (a row belongs to one user), it's made from the Quick Start > Todo List at https://app.supabase.io/project/<urlofyourproject>/editor/sql 

## Read the doc
https://kit.svelte.dev/docs

## Open Svelte CheatSheets
https://sveltesociety.dev/cheatsheet/
https://gist.github.com/peltho/ad6e051b854cd3095f9e7f9d9c550a84

### More useful extracts
There are two types of route — pages and endpoints.
pages are rendered on both the client and server
(-> some stuff can't render on server and you need \`if browser\`)

Endpoints run only on the server (or when you build your site, if prerendering). This means it's the place to do things like access databases or APIs.
Endpoints are modules written in .js (or .ts) files that \`export\` functions.

## Building it to host it
Before creating a production version of your app, install an [adapter](https://kit.svelte.dev/docs#adapters) for your target environment. Then:

\`\`\`bash
npm run build
\`\`\`

You can preview the built app with \`npm run preview\`, regardless of whether you installed an adapter.
`
# More!
This project is based on wonderful work from:
- https://svelte.dev
- https://supabase.io
- https://github.com/joshnuss/ (svelte <-> supabase)
- and others
Feel free to visit, learn and add your hacks as PR (Pull Request) for this project