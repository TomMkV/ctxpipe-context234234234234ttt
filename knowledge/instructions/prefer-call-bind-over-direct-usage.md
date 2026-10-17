---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:d4b5cc3bebe2e6e1e4cf816a14327baf
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/call-bind-apply-helpers/README.md"
---

# Prefer call-bind over direct usage

Use the call-bind package instead of call-bind-apply-helpers directly unless there is a specific, justified reason to do otherwise.

Intent: To ensure developers use the higher-level, more stable abstraction provided by call-bind.

Source: `node_modules/call-bind-apply-helpers/README.md`

Modality: recommended

> The only packages that should likely ever use this package directly are `call-bind` and `get-intrinsic`.
> Please use `call-bind` unless you have a very good reason not to.
