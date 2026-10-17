---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:7113e25b116a5171e236b55b2ca0a9e9
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/@pixi/text-html/README.md"
---

# Explicitly load fonts for HTMLText

Load custom fonts explicitly using text.style.loadFont because <foreignObject> rendering cannot access fonts available in the main document.

Intent: Ensure custom fonts are correctly rendered within the SVG/DOM-based HTMLText component.

Source: `node_modules/@pixi/text-html/README.md`

Modality: required

> Because rendering within a <foreignObject> element does not have access to fonts available in the current document, therefore, you need to load the fonts explicitly.
