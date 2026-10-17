---
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/has-symbols/README.md"
---

# Check Symbol sham support

Use the /shams entry point to determine if the environment has a Symbol sham (like core-js or get-own-property-symbols) that mostly follows the spec.

Intent: To detect if a Symbol polyfill or sham is active in environments lacking native support.

Source: `node_modules/has-symbols/README.md`

Modality: recommended

> var hasSymbolsKinda = require('has-symbols/shams');
> hasSymbolsKinda() === true; // if the environment has a Symbol sham that mostly follows the spec.
