# VICE HORIZON: 2026 — Credits & Licenses

Fan-made, non-commercial tribute. Not affiliated with or endorsed by Rockstar Games, Take-Two, Ferrari or any asset author.
All gameplay code, city generation, shaders, HUD and audio synthesis are original and procedural.

## Third-party assets (in `assets/`)

| File(s) | Asset | Author / Source | License | Changes |
|---|---|---|---|---|
| `hdri/kloofendal_48d_partly_cloudy_puresky_1k.hdr` | Kloofendal 48d Partly Cloudy (Pure Sky) | Greg Zaal — [Poly Haven](https://polyhaven.com/a/kloofendal_48d_partly_cloudy_puresky) | CC0 1.0 | none (1k) |
| `hdri/the_sky_is_on_fire_1k.hdr` | The Sky Is On Fire | [Poly Haven](https://polyhaven.com/a/the_sky_is_on_fire) | CC0 1.0 | none (1k) |
| `hdri/satara_night_no_lamps_1k.hdr` | Satara Night (No Lamps) | [Poly Haven](https://polyhaven.com/a/satara_night_no_lamps) | CC0 1.0 | none (1k) |
| `textures/asphalt_05_*` | Asphalt 05 (diffuse / normal GL / roughness) | [Poly Haven](https://polyhaven.com/a/asphalt_05) | CC0 1.0 | 1k JPG; 2k diffuse + normal re-encoded (mozjpeg) for High/Ultra |
| `textures/concrete_pavers_02_*` | Concrete Pavers 02 | [Poly Haven](https://polyhaven.com/a/concrete_pavers_02) | CC0 1.0 | 1k JPG; 2k diffuse + normal re-encoded (mozjpeg) for High/Ultra |
| `textures/red_brick_03_*` | Red Brick 03 (brick facade variant) | Rob Tuytel — [Poly Haven](https://polyhaven.com/a/red_brick_03) | CC0 1.0 | none (1k JPG) |
| `textures/coast_sand_01_*` | Coast Sand 01 | [Poly Haven](https://polyhaven.com/a/coast_sand_01) | CC0 1.0 | none (1k JPG) |
| `textures/beige_wall_001_*` | Beige Wall 001 (stucco) | [Poly Haven](https://polyhaven.com/a/beige_wall_001) | CC0 1.0 | none (1k JPG) |
| `models/ferrari_lod0.glb`, `models/ferrari_lod1.glb`, `models/ferrari_ao.png` | "Ferrari 458 Italia" | **vicent091036** — originally [Sketchfab](https://sketchfab.com/models/57bf6cc56931426e87494f554df1dab6), distributed with the [three.js examples](https://threejs.org/examples/webgl_materials_car.html) (license provenance: [three.js #23089](https://github.com/mrdoob/three.js/issues/23089)) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | interior parts removed, mesh simplified (meshoptimizer) into two LODs, UVs/normals stripped, Draco-compressed; recoloured paint, replaced glass/chrome/lamp materials, added police light bar at runtime |
| `characters/ual_mannequin.glb` | Universal Animation Library — mannequin character (humanoid rig) + Idle_Loop / Walk_Loop / Jog_Fwd_Loop / Pistol_Aim_Neutral animations | **Quaternius** — [quaternius.com/packs/universalanimationlibrary.html](https://quaternius.com/packs/universalanimationlibrary.html) (glTF obtained from the CC0 mirror [Papyszoo/CC0-Public-Domain-Models](https://github.com/Papyszoo/CC0-Public-Domain-Models/tree/main/packs/quaternius-universalanimationlibrary), `ual1_standard.glb`) | [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) | kept 4 of 43 animations (renamed Idle/Walk/Run/Aim), root-bone translation tracks removed, textures & UVs stripped (flat colours), welded + Draco-compressed; tinted per pedestrian at runtime, aim pose sampled from Pistol_Aim_Neutral and blended onto both arms |
| `props/fire_hydrant.glb` | Fire Hydrant | Gonçalo Felício — [Poly Haven](https://polyhaven.com/a/fire_hydrant) | CC0 1.0 | 1k textures (JPG), simplified (meshoptimizer), Draco-compressed |
| `props/street_lamp_01.glb` | Street Lamp 01 | Josh Dean — [Poly Haven](https://polyhaven.com/a/street_lamp_01) | CC0 1.0 | 1k textures, simplified, Draco-compressed; glass glows at night (runtime) |
| `props/metal_trash_can.glb` | Metal Trash Can | GurJas Studios — [Poly Haven](https://polyhaven.com/a/metal_trash_can) | CC0 1.0 | 1k textures, simplified, Draco-compressed |
| `props/street_bench.glb` | Modular Street Seating (one bench assembled from the kit) | Stuart Attenborrow — [Poly Haven](https://polyhaven.com/a/modular_street_seating) | CC0 1.0 | single bench extracted, 1k textures, simplified, Draco-compressed |
| `draco/*` | Draco 3D decoder (WASM) | Google — via three.js | Apache 2.0 | none |

## Runtime libraries (loaded from CDN)
- [three.js](https://threejs.org) r160 — MIT License (unpkg.com).

## Notes
CC0 assets need no attribution; Poly Haven and Quaternius are credited anyway as thanks.

## Required attribution (CC BY 4.0)
"Ferrari 458 Italia" by vicent091036, licensed under CC BY 4.0 — modified (simplified, recoloured, re-materialed).
This credit is also shown in-game on the title/pause menu.
