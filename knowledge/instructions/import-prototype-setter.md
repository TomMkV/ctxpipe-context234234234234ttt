---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:67a6782025fb8a5b64cecf46dcd68512
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/dunder-proto/README.md"
---

# Import prototype setter

Import the call-bound Object.prototype.__proto__ setter from the /set entry point.

Intent: To safely mutate the prototype of an object using a call-bound mutator.

Source: `node_modules/dunder-proto/README.md`

Modality: recommended

> const setDunder = require('dunder-proto/set');
