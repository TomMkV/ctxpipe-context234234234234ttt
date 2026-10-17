---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:238f083e88d23258290cb5e5856b052f
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/@pixi/runner/README.md"
---

# Runner Listener Implementation

Ensure that any object added to a Runner instance implements a method with the exact name provided to the Runner constructor.

Intent: To ensure the Runner can execute the target function directly on the listener object without errors.

Source: `node_modules/@pixi/runner/README.md`

Modality: required

> listenerObject needs to have a 'onComplete' function
> // ...
> All listeners / items in the runner must have the correct function name specified within the runners constructor.
