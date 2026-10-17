---
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/source-map-js/README.md"
---

# SourceMapConsumer Line Numbering

Use 1-based line numbers when querying or providing line information in SourceMapConsumer.

Intent: To ensure compatibility with the library's abstraction of the source map specification.

Source: `node_modules/source-map-js/README.md`

Modality: required

> Line numbers in this library are 1-based (note that the underlying source map specification uses 0-based line numbers -- this library handles the translation).
