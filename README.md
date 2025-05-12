# EPSCH-layer

Pre-configured nuxt layer for speed-up development and less boilerplate code. Includes:

`Eslint, Prettier, Stylelint, CommitLint, Husky`

also installs the latest version of Nuxt

## Setup

Run: `npx nuxi init --template gh:kosolapus/nuxt-epsch-layer`

To init in the current directory:

`npx nuxi init --template gh:kosolapus/nuxt-epsch-layer --force ./`

You should not use this layer as Nuxt layer in config.extends,
because it won't work (it only contains IDE/git instructions)
