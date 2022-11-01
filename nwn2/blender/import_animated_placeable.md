---
layout: default
---

# Importing an animated complex placeable into Blender

To convert an animated multipart placeable to FBX you must pass to **nw2fbx**
all the parts of the placeable and an animation. We are going to take as
example the placeable **Weather Vane**. Drag & drop these files to **nw2fbx**:

- **PLC_MC_WVANE01.mdb**
- **PLC_MC_WVANE01_01.MDB**
- **PLC_MC_Wvane01_idle.GR2**

We are going to analyze the generated FBX. This is a screenshot of Blender with
the FBX imported into it.

![](img/weather_vane.jpg)

- The attached part **PLC_MC_WVANE01_01** is child of the main part.
- If you play the animation, you will see that each part has a different
  animation. The main part, which is the base part, remains still, while the
  attached part rotates erratically as a consequence of the wind.
