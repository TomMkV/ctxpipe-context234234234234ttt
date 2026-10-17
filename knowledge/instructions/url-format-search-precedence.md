---
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/url/README.md"
---

# url.format search precedence

When using url.format, the 'search' property takes precedence over the 'query' object.

Intent: To ensure predictable string serialization when both raw search strings and parsed query objects exist.

Source: `node_modules/url/README.md`

Modality: required

> * `search` will be used in place of `query`
> * `query` (object; see `querystring`) will only be used if `search` is absent.
