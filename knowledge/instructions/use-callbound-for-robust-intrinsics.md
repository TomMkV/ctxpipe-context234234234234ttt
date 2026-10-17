---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:40b975f28867f58a9988cc11d5602fd4
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/call-bound/README.md"
---

# Use callBound for robust intrinsics

Import call-bound and use it to create bound versions of JavaScript intrinsics that remain functional even if the original prototypes are modified or deleted.

Intent: To ensure code reliability by using call-bound intrinsics that are immune to prototype pollution or deletion.

Source: `node_modules/call-bound/README.md`

Modality: recommended

> const callBound = require('call-bound');
> 
> const slice = callBound('Array.prototype.slice');
