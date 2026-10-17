---
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/gopd/README.md"
---

# Use gopd for property descriptors

Use the gopd package instead of Object.getOwnPropertyDescriptor to ensure compatibility with environments like IE where the native implementation may be broken.

Intent: Ensure cross-environment compatibility for retrieving object property descriptors.

Source: `node_modules/gopd/README.md`

Modality: recommended

> `Object.getOwnPropertyDescriptor`, but accounts for IE's broken implementation.
