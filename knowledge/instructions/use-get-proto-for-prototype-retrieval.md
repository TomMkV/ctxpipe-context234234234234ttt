---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:74be2b12685cf132edfc761b1286e180
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/get-proto/README.md"
---

# Use get-proto for prototype retrieval

Import and use the get-proto function to retrieve the [[Prototype]] of an object instead of direct property access.

Intent: To robustly get the [[Prototype]] of an object using the best available method.

Source: `node_modules/get-proto/README.md`

Modality: recommended

> const getProto = require('get-proto');
> 
> const a = { a: 1, b: 2, [Symbol.toStringTag]: 'foo' };
> const b = { c: 3, __proto__: a };
> 
> assert.equal(getProto(b), a);
