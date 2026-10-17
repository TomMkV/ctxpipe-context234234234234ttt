---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:638a111d02d0dd175570b3959b0d4c0e
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/has-symbols/README.md"
---

# Check native Symbol support

Use the main entry point to determine if the environment has native, non-polyfillable Symbol support.

Intent: To verify the presence of native ECMAScript Symbol support in the current JS environment.

Source: `node_modules/has-symbols/README.md`

Modality: recommended

> var hasSymbols = require('has-symbols');
> 
> hasSymbols() === true; // if the environment has native Symbol support. Not polyfillable, not forgeable.
