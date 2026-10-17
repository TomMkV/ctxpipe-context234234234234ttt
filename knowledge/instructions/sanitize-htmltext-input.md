---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:0bb5f31642988ef2ae552cf409231b95
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/@pixi/text-html/README.md"
---

# Sanitize HTMLText input

Always sanitize raw HTML strings before passing them to HTMLText to prevent Cross-site Scripting (XSS) attacks, especially when using user-provided data.

Intent: Prevent security vulnerabilities (XSS) from malicious or unvalidated HTML input.

Source: `node_modules/@pixi/text-html/README.md`

Modality: required

> Because the HTMLText object takes a raw HTML string, it's represents a potential vector for XSS, it's strongly encourage you santize input especially if you're accepting user-strings.
