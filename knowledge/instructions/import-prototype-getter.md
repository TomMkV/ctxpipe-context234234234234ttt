---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:77d5abe42e1bc13a723a6aef67029670
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/dunder-proto/README.md"
---

# Import prototype getter

Import the call-bound Object.prototype.__proto__ getter from the /get entry point.

Intent: To safely retrieve the prototype of an object using a call-bound accessor.

Source: `node_modules/dunder-proto/README.md`

Modality: recommended

> const getDunder = require('dunder-proto/get');
