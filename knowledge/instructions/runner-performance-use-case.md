---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:9583731bddbe1ce6a04abd31d527690d
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/@pixi/runner/README.md"
---

# Runner Performance Use Case

Use Runner instead of standard events or signals for high-frequency operations, such as per-frame updates or collision events.

Intent: To optimize performance in scenarios where speed and low memory footprint are critical.

Source: `node_modules/@pixi/runner/README.md`

Modality: recommended

> if you are dispatching signals/events to a lot of listeners often (like everyframe often), then I would consider using this alternative.
