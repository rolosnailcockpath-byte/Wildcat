# WILDTRACK VR — Reforged (v0.4.0)

Major upgrade of the multiplayer WebXR wilderness prototype.

## What’s new in 0.4
- **In-VR Field Pad**: grabable tablet + controller menu button (Y / menu) so you can open shop, biome, locomotion mode and status without leaving the headset.
- **Locomotion modes**: Walk (with procedural leg animation) ↔ Gorilla Tag arm-swing. Toggle with the MODE button or from the Field Pad.
- **Better player**: body + hands with finger curl driven by trigger/grip.
- **24 working weapons** with distinct stats, procedural models, fire + reload (R on desktop, secondary button in VR). All entries are functional.
- **32 animal variants** across many species with different sizes, speeds, values and simple death reactions.
- Improved bait and fishing feedback (Lakeshore biome).
- Cleaner UI, better lighting/materials, expanded shop, credits and harvest tracking.
- Multiplayer WebSocket + proximity voice foundation kept.

## Run
```bash
npm install
npm start
```
Open http://localhost:8080

## Quest
Deploy behind HTTPS, open the page in the Quest Browser, press **ENTER VR**.

## Controls
**Desktop:** WASD · mouse look · click fire · R reload · G bait · F fish · Tab Field Pad · M locomotion mode

**VR:** Trigger fire · Grip grab pad / interact · Y/Menu toggle Field Pad · Secondary button reload · Arm-swing (Gorilla mode) or stick + arm assist (Walk mode)

## Honest limits
This is still a procedural prototype, not a commercial asset-packed game. Models are generated in code. True photoreal guns, full skeletal animation, and 32 unique high-poly assets are outside the scope of a single-file WebXR prototype. The systems (reload, menu in VR, locomotion toggle, expanded catalog, multiplayer) are now solid foundations you can keep building on.
