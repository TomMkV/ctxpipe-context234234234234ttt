---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:e0c02eb3bdd560ea0a5a9576137e72b5
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/hasown/README.md"
---

# Use hasown for property checking

Use the hasown package as a robust, ES3-compatible predicate to check if an object has a specific own property.

Intent: To safely check for own properties without relying on Object.prototype.hasOwnProperty which can be shadowed or unavailable on null-prototype objects.

Source: `node_modules/hasown/README.md`

Modality: recommended

> A robust, ES3 compatible, "has own property" predicate.
> 
> ## Example
> 
> ```js
> const assert = require('assert');
> const hasOwn = require('hasown');
> 
> assert.equal(hasOwn({}, 'toString'), false);
> assert.equal(hasOwn([], 'length'), true);
> assert.equal(hasOwn({ a: 42 }, 'a'), true);
> ```
