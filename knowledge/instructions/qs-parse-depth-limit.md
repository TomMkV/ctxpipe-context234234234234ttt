---
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/qs/README.md"
---

# qs.parse depth limit

By default, qs parses nested objects up to 5 children deep. This can be overridden using the 'depth' option.

Intent: To mitigate abuse when parsing user input by limiting object recursion.

Source: `node_modules/qs/README.md`

Modality: recommended

> By default, when nesting objects qs will only parse up to 5 children deep.
> This depth can be overridden by passing a depth option to qs.parse(string, [options])
