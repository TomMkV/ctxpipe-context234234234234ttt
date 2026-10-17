---
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/qs/README.md"
---

# qs.parse allowPrototypes warning

Avoid enabling 'allowPrototypes' as it allows user input to overwrite object prototype properties.

Intent: To prevent prototype pollution and unexpected behavior in application logic.

Source: `node_modules/qs/README.md`

Modality: avoid

> WARNING It is generally a bad idea to enable this option as it can cause problems when attempting to use the properties that have been overwritten.
