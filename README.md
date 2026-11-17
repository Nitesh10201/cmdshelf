# CommandShelf

A personal, portable cheatsheet, config and troubleshooting reference.
Built with [Starlight](https://starlight.astro.build) and deployed to GitHub Pages.

## Setup

Requires [mise](https://mise.jdx.dev).

1. Install the pinned tools:

   ```bash
   mise install
   ```

2. Install dependencies:

   ```bash
   pnpm install
   ```

3. Start the dev server:

   ```bash
   pnpm dev
   ```

4. Create the local scratch folder for trials. It ignores itself (the `*` rule), so nothing inside is ever committed:

   ```bash
   mkdir -p Scratch && echo '*' > Scratch/.gitignore
   ```

## License

MIT
