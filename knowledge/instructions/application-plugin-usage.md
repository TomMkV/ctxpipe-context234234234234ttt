---
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/@pixi/ticker/README.md"
---

# Application plugin usage

Import @pixi/ticker as a side-effect to enable the ticker property on PixiJS Application instances.

Intent: To integrate the ticker functionality directly into the PixiJS Application lifecycle.

Source: `node_modules/@pixi/ticker/README.md`

Modality: optional

> import '@pixi/ticker';
> import { Application } from '@pixi/app';
> 
> const app = new Application();
> app.ticker.start();
