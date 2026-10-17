---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:c9e91ca990cfe043b5050ee7876e04ce
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/qs/README.md"
---

# qs.parse plainObjects for safety

Use 'plainObjects: true' to return a null-prototype object, preventing prototype method conflicts.

Intent: To ensure the parsed object is a clean data container without inherited methods.

Source: `node_modules/qs/README.md`

Modality: recommended

> When using the plainObjects option the parsed value is returned as a null object, created via { __proto__: null }
