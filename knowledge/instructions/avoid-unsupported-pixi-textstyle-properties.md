---
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/@pixi/text-html/R\
  EADME.md"
---

# Avoid unsupported PIXI.TextStyle properties

Do not use fillGradientStops, fillGradientType, lineJoin, miterLimit, textBaseline, trim, or leading with HTMLText as they are not supported.

Intent: Prevent the use of style properties that have no effect on HTMLText rendering.

Source: `node_modules/@pixi/text-html/README.md`

Modality: forbidden

> Unsupported
> 
> * fillGradientStops
> * fillGradientType
> * lineJoin
> * miterLimit
> * textBaseline
> * trim
> * leading
