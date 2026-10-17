---
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/side-channel-map/\
  README.md"
---

# Manual memory management for object keys

Explicitly delete object keys from the side channel to prevent memory leaks, as this implementation uses a Map which holds strong references.

Intent: Prevent memory leaks when using objects as keys in the side channel.

Source: `node_modules/side-channel-map/README.md`

Modality: required

> Warning: if the `key` is an object, this implementation will leak memory until you `delete` it.
