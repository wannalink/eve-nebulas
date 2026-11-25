# EVE Online Nebula Assets (Web-Optimized)

Web-optimized cubemap skybox assets derived from public EVE Online game resources.

## Structure

Each of the 75 SDE nebula scenes (`a01_cube`–`a18_cube`, `c01_cube`–`c19_cube`, `g01_cube`–`g11_cube`, `m01_cube`–`m17_cube`, `j01_cube`, `j02_cube`, `y01_cube`, `wormhole_class_00`–`wormhole_class_06`) is stored under `nebulas/{scene_id}/` as:

- **RGB cubemap faces**: `px.webp`, `nx.webp`, `py.webp`, `ny.webp`, `pz.webp`, `nz.webp`
- **Alpha mask cubemap faces** (for `background.fx` tiled starfield blending): `alpha_px.webp`, `alpha_nx.webp`, `alpha_py.webp`, `alpha_ny.webp`, `alpha_pz.webp`, `alpha_nz.webp`

Shared assets under `nebulas/common/`:
- `stars01_tile2.webp`: Tiled background starfield texture sampled by the `background.fx` skybox shader.

Legacy non-`_cube` folders (`a01`, `c02`, etc.) remain present for backwards compatibility with older deployments.

## CDN Usage via jsDelivr

You can access any asset directly via jsDelivr:

```text
https://cdn.jsdelivr.net/gh/wannalink/eve-nebulas@main/nebulas/{scene_id}/{face}.webp
https://cdn.jsdelivr.net/gh/wannalink/eve-nebulas@main/nebulas/{scene_id}/alpha_{face}.webp
https://cdn.jsdelivr.net/gh/wannalink/eve-nebulas@main/nebulas/common/stars01_tile2.webp
```

Example for The Forge (`c02_cube`):
```text
https://cdn.jsdelivr.net/gh/wannalink/eve-nebulas@main/nebulas/c02_cube/px.webp
https://cdn.jsdelivr.net/gh/wannalink/eve-nebulas@main/nebulas/c02_cube/alpha_px.webp
```

---

## Legal Disclaimer & Copyright Notice

**EVE Online and the EVE logo are the registered trademarks of CCP hf. / Fenris Creations. All rights are reserved worldwide.**

- All artwork, textures, game assets, and associated intellectual property belong to **Fenris Creations / CCP hf.**
- This repository is an unofficial, non-commercial fan-created asset repository intended exclusively for community-developed tools.
- This project is **not** endorsed by, affiliated with, or sponsored by Fenris Creations, CCP Games, or CCP hf.
- Use of game content is subject to the applicable [Video & Content Creation Terms](https://www.eveonline.com/legal/terms-of-service) and intellectual property guidelines.
