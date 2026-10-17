---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:fc2a696fad5c641feeda4b9c98281056
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/get-intrinsic/README.md"
---

# Handle missing intrinsics with allowMissing flag

Pass `true` as the second argument to GetIntrinsic to return undefined instead of throwing an error when an intrinsic is missing in the environment.

Intent: To prevent application crashes when checking for features that might not exist in the current JS environment.

Source: `node_modules/get-intrinsic/README.md`

Modality: optional

> assert.equal(undefined, GetIntrinsic('%JSON.parse%', true));
