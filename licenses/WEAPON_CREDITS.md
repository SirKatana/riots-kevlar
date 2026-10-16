# Weapon asset credits — Riots: Kevlar Edition

## Existing rifle and pistol

- Mateusz Sadek / Poly Haven, **Service Pistol**: https://polyhaven.com/a/service_pistol
- Mateusz Sadek / Poly Haven, **Bolt Action Rifle 7.62**: https://polyhaven.com/a/bolt_action_rifle_7_62
- License: CC0. Imported models with authored base-color, normal and ARM maps.

## Replacement AK-47, M4A1, shotgun, M3 SMG and scoped rifle

- Author: **3dmodelscc0**, Guns & Explosives Pack.
- Original release and CC0 license declaration: https://3dmodelscc0.itch.io/free-cc0-guns-explosives-pack
- GLB conversion distribution: https://github.com/BoQsc/cc0-guns-explosives-pack-glb/releases/tag/0
- License: CC0 1.0 Universal, https://creativecommons.org/publicdomain/zero/1.0/
- Modified for this game: transforms baked, grip origin aligned, muzzle markers added, magazines retained as separate meshes; AK DirectX normal converted to OpenGL. Source textures retained.
- Reproducible adapter: `../import_pbr_weapons.py`; original downloads retained outside the exported project in `../weapon_sources/`.

## Minigun

**Minigun M-134** by **Nik Vega**, licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

- Original model: https://sketchfab.com/3d-models/minigun-m-134-2961cd5d09844921b045761108956470
- Author: https://sketchfab.com/nik_vega
- License: https://creativecommons.org/licenses/by/4.0/
- Downloaded through Sketchfab's authorized GLB download, retaining the 4K base-color, normal, occlusion and metallic/roughness textures.
- Changes: baked the rigid skin at its reference pose, separated the authored barrel group for lightweight gameplay rotation, transformed to the game's +X-forward coordinates, added grip/muzzle anchors and fitted the game's existing anatomical hand source. Original mesh/UV surface detail retained.
- Adaptation script: `../import_m134.py`. Original download retained in `../weapon_sources/minigun_m-134.glb`.
- Attribution must accompany redistributions. No endorsement by the author is implied.

No Polyy model is included in the game.

## Original gunsmith attachments (v0.9.2)

The 4× optic, two-port brake, suppressor and magazine extension in `assets/attachments/` were authored for this project using Blender. Beveled mechanical geometry, PBR metal/rubber/lens materials and preview icons are original; they contain no third-party stock model or texture. Source generator: `../build_attachment_models.py`.

## Reverse dagger and grip (v0.9.3)

Original reverse-oriented steel blade, tang, guard, grip and pommel, generated in `../create_dagger_hand.py`. The closed bare hand is a new pose/baked derivative of the same CC0 anatomical source credited above for existing hands. Forearm extension and third-person wrist version authored for this project.

## Grenades and pistol attachments (v0.9.4)

Frag/EMP models, olive enamel texture, pistol reflex sight, ported brake, suppressor and baseplate authored for this project in `../build_ordnance094.py`. Inventory/attachment icons rendered from these models. Grenade hand is a newly posed derivative of the existing CC0 anatomical hand, generated with `../create_grenade_hand094.py`. No new third-party stock assets. Blast effects reuse the project's original smoke-volume texture.

## Tabloit and RL-84 (v0.9.5)

Original launcher, rocket, puzzle-fragment, steel cage/gate and terminal models authored in `../build_tabloit095.py`, with project metal/olive materials. Tactical puzzle atlas is original SVG artwork. Icons rendered from the models. Launcher grips reuse the previously credited CC0 anatomical hand derivatives. No new stock model or sound license is introduced.
