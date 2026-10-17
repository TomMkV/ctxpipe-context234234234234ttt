---
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
