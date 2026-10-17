---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:1d7cfafa08d3ef3b1b0813077643a471
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/es-define-property/README.md"
---

# Check for defineProperty support

Verify if $defineProperty is available before use, as it returns false in IE 8 or ES3 engines.

Intent: Ensure compatibility across environments where Object.defineProperty might be broken or missing.

Source: `node_modules/es-define-property/README.md`

Modality: recommended

> if ($defineProperty) {
>     assert.equal($defineProperty, Object.defineProperty);
> } else if (Object.defineProperty) {
>     assert.equal($defineProperty, false, 'this is IE 8');
> } else {
>     assert.equal($defineProperty, false, 'this is an ES3 engine');
> }
