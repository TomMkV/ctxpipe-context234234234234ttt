---
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/eventemitter3/README.md"
---

# Error Event Handling

Be aware that EventEmitter3 does not throw an error if an 'error' event is emitted without listeners.

Intent: Understand the difference in error handling behavior compared to Node.js core EventEmitter.

Source: `node_modules/eventemitter3/README.md`

Modality: optional

> We do not `throw` an error when you emit an `error` event and nobody is listening.
