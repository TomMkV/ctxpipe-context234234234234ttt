---
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/pixi.js/README.md"
---

# PixiJS Namespace Import

Import PixiJS using the namespace syntax because the library does not provide a default export.

Intent: To correctly reference the library in environments that do not support default exports.

Source: `node_modules/pixi.js/README.md`

Modality: required

> There is no default export. The correct way to import PixiJS is:
> 
> ```js
> import * as PIXI from 'pixi.js';
> ```
