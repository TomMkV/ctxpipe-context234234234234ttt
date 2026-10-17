---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:dc1ff7ec1e7635b97c5f0ec026ba5e04
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/gopd/README.md"
---

# Check gopd availability

Verify that gopd is truthy before calling it as a function, as it may be null or undefined in environments that do not support property descriptors at all.

Intent: Prevent runtime errors in legacy environments that lack descriptor support.

Source: `node_modules/gopd/README.md`

Modality: required

> if (gOPD) {
> 	assert.equal(typeof gOPD, 'function', 'descriptors supported');
> 	// use gOPD like Object.getOwnPropertyDescriptor here
> } else {
> 	assert.ok(!gOPD, 'descriptors not supported');
> }
