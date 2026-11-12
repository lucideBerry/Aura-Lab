# Aura Lab FAQ (for the Superhive FAQ tab)

**Which Blender versions does it support?**
Blender 5.0 and newer, on Windows, macOS and Linux. It installs as a regular extension from the zip.

**Does it work in both Cycles and Eevee?**
Yes, all 20 auras render in both. Cycles gives the best volumes (fire, smoke, mist) and refraction; Eevee is great for fast previews. Press Optimize Render Settings once per scene for AgX colour, volume quality, ray tracing and bloom.

**Will it work on my rigged, animated character?**
Yes. Auras read the character's evaluated mesh every frame, so armatures (Mixamo, Rigify, Auto-Rig Pro or your own), shape keys and modifiers all work. Wings, halos, tentacles, blood streams and soul wisps stay anchored to the back, head and torso while the character moves.

**Do I need UVs, textures or clean topology?**
No. Everything is procedural Geometry Nodes and shaders. No UVs, no image textures, no flipbooks.

**Can I change the colour?**
Yes. Hue Shift and Saturation recolour every layer, light and particle of an aura with one slider each. Every layer's own colours can be edited too.

**Can I animate the parameters?**
Yes. Every value in Controls and Layers is a normal Blender property you can keyframe or drive. Start Time lets you trigger an aura mid-shot.

**Can I use it on non-human meshes?**
Yes, it works on any mesh. Presets are tuned for human-sized characters; for very large or small objects, adjust Radius, Length and Voxel Size in Layers.

**Can I put several auras on one character?**
Yes. Add as many as you like, to one or several meshes. The Edit field picks which aura the panels control.

**Is it heavy to render?**
Auras with volumes (Inferno, Golden Ascension, Wraith, Crimson Blood mist) are the heaviest, like any volumetric effect. You can hide a volume layer in the viewport while animating and keep it for the render.

**Can I use renders in commercial projects?**
Yes. Anything you render with Aura Lab is yours to use, in commercial work too. The add-on code is GPL-3.0-or-later.

**How do I get updates?**
Download the new zip from your Superhive library and install it over the old one the same way.
