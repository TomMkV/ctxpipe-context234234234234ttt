---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:a692c13b661880dbda3f46d9c99f2719
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/source-map-js/README.md"
---

# SourceMapGenerator applySourceMap Pathing

Provide sourceMapPath when applying a SourceMap from a different directory that contains relative paths.

Intent: To ensure relative source paths are correctly rewritten when merging source maps from different locations.

Source: `node_modules/source-map-js/README.md`

Modality: required

> sourceMapPath: Optional. The dirname of the path to the SourceMap to be applied. If relative, it is relative to the SourceMap. This parameter is needed when the two SourceMaps aren't in the same directory, and the SourceMap to be applied contains relative source paths.
