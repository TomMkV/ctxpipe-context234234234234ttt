---
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/side-channel/README.md"
---

# Manual key deletion in non-WeakMap environments

Explicitly delete keys from the side channel when they are no longer needed if the environment does not support WeakMap to prevent memory leaks.

Intent: Prevent memory leaks in legacy environments lacking WeakMap support.

Source: `node_modules/side-channel/README.md`

Modality: required

> Warning: in an environment that lacks `WeakMap`, this implementation will leak memory until you `delete` the `key`.
