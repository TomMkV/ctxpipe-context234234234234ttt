---
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/@pixi/colord/README.md"
---

# Plugin Extension

Use the extend function to add plugin functionality to Colord.

Intent: To enable non-core features like color names, a11y, or advanced color spaces.

Source: `node_modules/@pixi/colord/README.md`

Modality: required

> import { colord, extend } from "colord";
> import namesPlugin from "colord/plugins/names";
> 
> extend([namesPlugin]);
