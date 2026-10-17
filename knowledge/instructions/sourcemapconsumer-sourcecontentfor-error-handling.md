---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:472dc4d4c04f9bd0753133a5a14b20fc
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/source-map-js/README.md"
---

# SourceMapConsumer sourceContentFor Error Handling

Pass true as the second parameter to sourceContentFor to return null instead of throwing an error when a source is missing.

Intent: To allow for graceful handling of missing source content without try-catch blocks.

Source: `node_modules/source-map-js/README.md`

Modality: optional

> If the source content for the given source is not found, then an error is thrown. Optionally, pass true as the second param to have null returned instead.
