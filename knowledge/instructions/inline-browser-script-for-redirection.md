---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:359a84c23e5364659da5463bb27f4b59
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/ismobilejs/README.md"
---

# Inline Browser Script for Redirection

For mobile redirection, include the minified isMobile script inline at the top of the <head> to minimize connection overhead and trigger redirects early.

Intent: To start redirects as soon as possible before downloading other assets.

Source: `node_modules/ismobilejs/README.md`

Modality: recommended

> I include the minified version of the script, inline, and at the top of the <head>. Cellular connections tend to suck, so it would be wasteful overhead to open another connection, just to download ~1.3kb of JS
