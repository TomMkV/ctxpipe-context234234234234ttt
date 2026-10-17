---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:7830c2e0581118656a09c18e80731c57
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/url/README.md"
---

# url.parse slashes denote host

Pass true as the third argument to url.parse to treat double-slash URLs as having a host (e.g., //foo/bar as host 'foo').

Intent: To correctly handle protocol-relative URLs during parsing.

Source: `node_modules/url/README.md`

Modality: optional

> Pass `true` as the third argument to treat `//foo/bar` as
> `{ host: 'foo', pathname: '/bar' }` rather than
> `{ pathname: '//foo/bar' }`. Defaults to `false`.
