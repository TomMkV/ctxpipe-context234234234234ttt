---
import_key: inu:repo_agoxzdwbvj275ggqmm4k4lg3um:./:ed9a6ac8d35545188e5dfc1ad588a5d1
kind: InstructionUnit
confidence: 0.62
generated_by: ctxpipe
source: "https://github.com/tommkv/stillwood.git#node_modules/@pixi/compressed-textures/README.md"
---

# Avoid cubemap or 3D textures in .ktx files

Do not use .ktx files that contain cubemaps or 3D textures as they are not supported by this loader.

Intent: To prevent runtime errors or loading failures caused by unsupported .ktx features.

Source: `node_modules/@pixi/compressed-textures/README.md`

Modality: avoid

> Support for cubemap, 3D textures not included
