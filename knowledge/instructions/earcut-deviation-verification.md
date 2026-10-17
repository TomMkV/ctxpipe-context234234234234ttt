---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:31d5e862c18e553d09e4481b1db18341
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/earcut/README.md"
---

# earcut.deviation verification

Verify the correctness of a triangulation by checking the area deviation.

Intent: To validate that the resulting triangles accurately represent the input polygon area.

Source: `node_modules/earcut/README.md`

Modality: optional

> After getting a triangulation, you can verify its correctness with earcut.deviation:
> var deviation = earcut.deviation(vertices, holes, dimensions, triangles);
