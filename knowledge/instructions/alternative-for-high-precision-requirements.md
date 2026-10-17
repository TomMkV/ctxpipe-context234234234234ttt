---
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/earcut/README.md"
---

# Alternative for high-precision requirements

Use libtess.js if absolute correctness on self-intersecting or extremely bad data is required.

Intent: To ensure data integrity when earcut's speed-optimized algorithm is insufficient for complex edge cases.

Source: `node_modules/earcut/README.md`

Modality: recommended

> If you want to get correct triangulation even on very bad data with lots of self-intersections and earcut is not precise enough, take a look at libtess.js.
