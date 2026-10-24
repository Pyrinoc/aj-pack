# ajpack

Minecraft Bedrock add-on: a behavior pack (`behavior_packs/ajpack`) and a resource pack (`resource_packs/ajpack`), with TypeScript scripts in `scripts/`.

On Windows, run `Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass` first if PowerShell blocks the npm scripts.

- `npm install`: install dependencies
- `npm run build`: type check and bundle `scripts/main.ts` into `dist/scripts/main.js`
- `npm run local-deploy -- --watch`: deploy both packs to your local Minecraft and rebuild on changes
- `npm run mcaddon`: create `dist/packages/ajpack.mcaddon`
- `npm run lint`: lint the scripts

Use the `aj:` prefix for custom identifiers. Pack names live in each pack's `texts/en_US.lang`.
