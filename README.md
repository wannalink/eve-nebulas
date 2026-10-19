# EVE Online Nebula Assets (Web-Optimized)

Web-optimized, DirectXTex-processed cubemap skybox assets derived from public EVE Online game resources for use in community 3D visualization applications (such as [DSuit](https://github.com/wannalink/DSuit)).

## Structure

Each nebula is stored as 6 cubemap faces in `.webp` format at 1024×1024 resolution:
- `px.webp`: Positive X (+X)
- `nx.webp`: Negative X (-X)
- `py.webp`: Positive Y (+Y)
- `ny.webp`: Negative Y (-Y)
- `pz.webp`: Positive Z (+Z)
- `nz.webp`: Negative Z (-Z)

Processed using Microsoft DirectXTex with HDR tone-mapping, anti-banding dithering, and coordinate un-mirroring for authentic in-game visual representation.

## CDN Usage via jsDelivr

You can access any asset directly via jsDelivr:

```text
https://cdn.jsdelivr.net/gh/wannalink/eve-nebulas@main/nebulas/{nebula_id}/{face}.webp
```

Example for The Forge (`c02`):
```text
https://cdn.jsdelivr.net/gh/wannalink/eve-nebulas@main/nebulas/c02/px.webp
```

---

## Legal Disclaimer & Copyright Notice

**EVE Online and the EVE logo are the registered trademarks of CCP hf. / Fenris Creations. All rights are reserved worldwide.**

- All artwork, textures, game assets, and associated intellectual property belong to **Fenris Creations / CCP hf.**
- This repository is an unofficial, non-commercial fan-created asset repository intended exclusively for community-developed tools.
- This project is **not** endorsed by, affiliated with, or sponsored by Fenris Creations, CCP Games, or CCP hf.
- Use of game content is subject to the applicable [Video & Content Creation Terms](https://www.eveonline.com/legal/terms-of-service) and intellectual property guidelines.
