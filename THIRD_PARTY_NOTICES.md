# Razor Squadron — Credits and Third-Party Notices

Razor Squadron is created, designed, and produced by Adam Blue / BlueGamer
Productions. Copyright 2026 BlueGamer Productions.

## Godot Engine

This game uses Godot Engine 4.7.2, available at <https://godotengine.org>.

Copyright (c) 2014-present Godot Engine contributors.
Copyright (c) 2007-2014 Juan Linietsky, Ariel Manzur.

Godot Engine is distributed under the MIT License. The complete license and
current attribution information are available at
<https://godotengine.org/license/>.

## GodotSteam

This game uses GodotSteam for Steamworks client initialization, callbacks,
ownership information, overlay support, and Steam Cloud compatibility. Razor
Squadron does not reuse Epic Space Battles achievement or leaderboard IDs.

Copyright (c) 2015-Current GP Garcia, Chris Ridenour, and Contributors.

GodotSteam is distributed under the MIT License. The complete license is
included at `addons/godotsteam/license.md`, and project information is
available at <https://godotsteam.com/>.

Steam and the Steam logo are trademarks and/or registered trademarks of Valve
Corporation in the United States and/or other countries.

## IBM Plex Sans

Copyright © 2017 IBM Corp. with Reserved Font Name "Plex".

IBM Plex Sans is licensed under the SIL Open Font License, Version 1.1. The
complete license is included at `assets/fonts/IBM_Plex_Sans/OFL.txt`.

## Oxanium

Oxanium is the primary font used by the shipping game interface.

Copyright 2019 The Oxanium Project Authors
(<https://github.com/sevmeyer/oxanium>).

Oxanium is licensed under the SIL Open Font License, Version 1.1. The complete
license is included at `assets/fonts/Oxanium/OFL.txt`.

## 2D Motion Blur shader reference

The fighter motion-blur shader adapts the sampling approach from **2D Motion
Blur** by Hayden, published on Godot Shaders:
<https://godotshaders.com/shader/2d-motion-blur/>.

The shader code and snippets on that page are dedicated to the public domain
under CC0 1.0.

## NASA Moon visualization

The in-game Moon is derived from frame `path.0002.tif` of **Apollo 13 Moon
View Using LRO Data**, NASA Scientific Visualization Studio visualization
4791, released February 24, 2020:
<https://svs.gsfc.nasa.gov/4791>.

Original `path_comp` frame set:
<https://svs.gsfc.nasa.gov/vis/a000000/a004700/a004791/frames/3840x2160_16x9_30p/path_comp/>.

Please credit this item to **NASA's Scientific Visualization Studio**.

- Visualizer: Ernie Wright (USRA)
- Scientist: Noah Petro (NASA/GSFC)
- Producer: David Ladd (USRA)
- Technical support: Laurence Schuler (ADNET Systems, Inc.)
- Technical support: Ian Jones (ADNET Systems, Inc.)

The visualization uses color and elevation mapping from the Lunar
Reconnaissance Orbiter mission, including LRO Camera color data and LOLA
elevation data. The local conversion record is at
`assets/environment/moon/SOURCE.md`.

## NASA Earth imagery

The supplied Earth source imagery is derived from **Blue Marble: Next
Generation**, produced by Reto Stöckli of NASA Earth Observatory at NASA
Goddard Space Flight Center:
<https://science.nasa.gov/earth/earth-observatory/blue-marble-next-generation/>.

Please credit this item to **NASA Earth Observatory**. Blue Marble: Next
Generation uses MODIS observations to present monthly true-color global Earth
imagery at 500 meters per pixel. The source imagery was adapted into the
game's surface, cloud, and night presentation.

## Production tools and assistance

- Godot Engine — game development and rendering.
- Adobe Firefly with Google Gemini 2.5 Flash Image (Nano Banana) — AI-assisted
  spacecraft source imagery.
- The original Razor Squadron score was created and directed by Adam Blue.
  Current gameplay music includes "Main Menu Music," "Invasion,"
  "Destruction," "Vanguard," "Razor Squadron," "Assault," "Warlust," and
  "Boss Music." AI-assisted music production tools include Suno. The source
  project also retains "Chase" and "Midnight Airship," created and directed by
  Adam Blue with Suno under a paid subscription.
- OpenAI Codex — development and programming assistance.

Original engine, weapons, impact, destruction, and interface audio was created
and directed by Adam Blue using Adobe Firefly audio tools.

Original explosion, spark, smoke, and combat effects are procedural effects
created in Godot Engine; there is no external explosion frame library to
attribute.

## Other bundled fonts

The source project also contains the following font packages, each with its
own included SIL Open Font License 1.1 text. They are not currently used by the
shipping interface but their notices are retained with the source distribution:

- Geist — Copyright 2024 The Geist Project Authors.
- Inter — Copyright 2020 The Inter Project Authors.
- Press Start 2P — Copyright 2012 The Press Start 2P Project Authors.
- Roboto Condensed — Copyright 2011 The Roboto Project Authors.

## Binbun3D VFX packs

`assets/BinbunVFX/` and `assets/BinbunVFX_Vol2/` -- GPU-particle effect
scenes, spatial shaders and helper scripts by Binbun3D (bun3d.com), all
released under Creative Commons Zero (CC0). No attribution is required;
credited here by request. Original licence texts are retained alongside each
pack. Rendered through `scripts/world/vfx_3d_layer.gd`.

Packs included:

- `BinbunVFX_Vol2/ExplosionFX` -- explosions (wired: enemy and boss kills)
- `BinbunVFX_Vol2/StylizedHitFX` -- impacts (wired: non-fatal weapon hits)
- `BinbunVFX/muzzle_flash` -- muzzle flashes (wired: player/wingman fire)
- `BinbunVFX/loot_effects` -- pickup glows (imported, not yet wired)
- `BinbunVFX/magic_projectiles` -- projectile effects (imported, not yet wired)
- `BinbunVFX_Vol2/FlameFX` -- fire (imported, not yet wired)
- `BinbunVFX_Vol2/BattleFX` -- shields, charges, slashes (imported, not yet wired)
- `BinbunVFX_Vol2/ElementalMagicFX` -- elemental effects (wired: the fire area is the kill shockwave ring; CC0)

## Sound effects

Explosion and heavy beam sounds from "Superior Sound FX: Lasers and
Explosions" by Soiree Games (<https://soiree.info>), free for use in all
projects. Thank you, Soiree Games.

Beam charge, hull hit, alarm and power-up sounds from the
sfx pack by Nancy Gold (<https://nancygold.itch.io/>), used under its
license: usable in commercial projects; the sounds are not resold or
redistributed as standalone assets.

## Shaders

The coin glint (`shaders/coin_glint.gdshader`) is adapted from
"Highlight CanvasItem" on Godot Shaders
(<https://godotshaders.com/shader/highlight-canvasitem/>), released under
CC0. No attribution is required; credited here anyway.

## Kill explosions

Enemy kill explosions use "Simple Explosion VFX" by Duarte David
(<https://github.com/drcd1/GodotSimpleExplosionVFX>), Godot 4.2 port by
memo1918 (<https://github.com/memo1918/GodotExplosionVFX>), in
`assets/vfx/simple_explosion/`, under the MIT License. `shaders/explosion_detail.gdshader`
is a modified copy of its shader (per-particle rotation enabled, a layer
alpha added), covered by the same license:

Copyright 2020 Duarte David

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
# Microsoft Xbox native integration

The Windows GDK bridge uses the MIT-licensed wrapper from
https://github.com/microsoft/XBOX-Godot-Sample at revision
`c25758a85e88ec5b91081b63ff5a59fc1583d5ba`.
Its license is retained at `platform/xbox/native/MICROSOFT_SAMPLE_LICENSE.txt`.
Microsoft GDK runtime dependencies retain their separate Microsoft license;
the wrapper's MIT license does not relicense the GDK.
