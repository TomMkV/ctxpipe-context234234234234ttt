---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:1c6b1d7054ce45eabe9975ef886b7699
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/eventemitter3/README.md"
---

# Contextual Event Listeners

Pass an optional context argument to .on, .once, or .removeListener to set the 'this' value without using .bind().

Intent: Avoid the performance overhead of Function.prototype.bind by using the built-in context argument.

Source: `node_modules/eventemitter3/README.md`

Modality: recommended

> EE.once('event-name', emitted, context);
> EE.on('another-event', emitted, context);
> EE.removeListener('another-event', emitted, context);
