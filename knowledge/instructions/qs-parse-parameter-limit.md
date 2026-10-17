---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:48914b624ff1bcd4afbe8e04736cfe61
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/qs/README.md"
---

# qs.parse parameter limit

By default, qs parses up to 1000 parameters. Use 'parameterLimit' to change this threshold.

Intent: To prevent Denial of Service (DoS) attacks via large numbers of query parameters.

Source: `node_modules/qs/README.md`

Modality: recommended

> by default qs will only parse up to 1000 parameters. This can be overridden by passing a parameterLimit option
