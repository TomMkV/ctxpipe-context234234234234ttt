---
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/source-map-js/README.md"
---

# SourceMapGenerator Validation Skip

Optionally disable mapping validation in SourceMapGenerator for performance, but avoid doing so during tests.

Intent: To maintain data integrity during development and testing while allowing performance tuning in production-like scenarios.

Source: `node_modules/source-map-js/README.md`

Modality: avoid

> skipValidation: Optional. When true, disables validation of mappings as they are added. This can improve performance but should be used with discretion, as a last resort. Even then, one should avoid using this flag when running tests, if possible.
