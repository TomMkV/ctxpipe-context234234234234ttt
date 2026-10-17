---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:175f8c249c79817fe8f60f34e128d5cb
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
