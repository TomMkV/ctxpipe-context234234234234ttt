---
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/qs/README.md"
---

# qs.parse decodeDotInKeys dependency

If 'decodeDotInKeys' is true, 'allowDots' must also be true or the parser will error.

Intent: To maintain internal consistency between dot-notation features.

Source: `node_modules/qs/README.md`

Modality: required

> Note: it implies allowDots, so parse will error if you set decodeDotInKeys to true, and allowDots to false.
