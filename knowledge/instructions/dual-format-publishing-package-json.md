---
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/rollup/README.md"
---

# Dual-Format Publishing (package.json)

Point the 'main' field to a CJS/UMD bundle and the 'module' field to an ES module bundle for maximum compatibility.

Intent: To ensure libraries are usable by both legacy CommonJS tools and modern ES-module-aware bundlers.

Source: `node_modules/rollup/README.md`

Modality: recommended

> compile to UMD or CommonJS format, and then point to that compiled version with the `main` property in your `package.json` file. If your `package.json` file also has a `module` field, ES-module-aware tools like Rollup and [webpack](https://webpack.js.org/) will [import the ES module version](https://github.com/rollup/rollup/wiki/pkg.module) directly.
