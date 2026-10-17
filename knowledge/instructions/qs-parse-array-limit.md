---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:b66cc3b37a88de077a53a87f4727feaa
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/qs/README.md"
---

# qs.parse array limit

qs limits arrays to 20 elements by default; indices 20+ become object keys unless 'arrayLimit' is adjusted.

Intent: To prevent performance degradation when iterating over sparse or massive arrays.

Source: `node_modules/qs/README.md`

Modality: recommended

> qs will also limit arrays to a maximum of 20 elements.
> Any array members with an index of 20 or greater will instead be converted to an object with the index as the key.
