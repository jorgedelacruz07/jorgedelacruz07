# Repository maintenance

Use Node 26 through mise and `.nvmrc`; install development tools with `npm ci`.

- `npm run format` applies Prettier to the Markdown and JSON files.
- `npm run lint` checks formatting and Git whitespace.
- `npm run quick` runs the same checks without rewriting files.

There is no build artifact or `npm run deploy`. GitHub renders the profile from
the default branch; reviewing and pushing content is a separate action.
