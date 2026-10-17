---
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/url/README.md"
---

# url.format host precedence

When using url.format, the 'host' property takes precedence over 'hostname' and 'port'.

Intent: To ensure predictable string serialization when multiple host-related properties are present in the URL object.

Source: `node_modules/url/README.md`

Modality: required

> * `hostname` will only be used if `host` is absent.
> * `port` will only be used if `host` is absent.
> * `host` will be used in place of `hostname` and `port`
