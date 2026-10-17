---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:88e48a468c7aeffba9342919dc4be08e
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/side-channel-list/README.md"
---

# Prefer side-channel over side-channel-list

Use the main 'side-channel' package instead of 'side-channel-list' to ensure the most efficient storage strategy is used.

Intent: To utilize the most optimized side-channel implementation available.

Source: `node_modules/side-channel-list/README.md`

Modality: recommended

> Use [`side-channel`](https://npmjs.com/side-channel) for the best available strategy.
