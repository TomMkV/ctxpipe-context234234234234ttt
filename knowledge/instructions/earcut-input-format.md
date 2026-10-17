---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:e6f252cd83d7beb102b5ab63d4538f6f
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/earcut/README.md"
---

# earcut input format

Provide vertices as a flat array of coordinates and holes as an array of indices.

Intent: To ensure the triangulation algorithm correctly interprets vertex and hole boundaries.

Source: `node_modules/earcut/README.md`

Modality: required

> earcut(vertices[, holes, dimensions = 2])
> * `vertices` is a flat array of vertex coordinates like `[x0,y0, x1,y1, x2,y2, ...]`.
> * `holes` is an array of hole indices if any
