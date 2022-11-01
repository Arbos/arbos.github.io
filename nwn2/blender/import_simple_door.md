---
layout: default
---

# Blender Add-on for *Neverwinter Nights 2*

## Tutorial: Import door

### Basics

- By **simple placeable** we mean a placeable without animated parts.
- Placeables are stored in MDB files.
- This tutorial uses Blender 3.3.1.

How to know what skeleton uses a door?

1. Open **doortypes.2da**.
2. Search the row corresponding to the door. It should be the row that has
the name of the MDB in the column **NWN2_ModelName**.
3. The name of the skeleton should be in the column **NWN2_Skeleton**.

### Steps

1. Go to **File** > **Import** > **Neverwinter Nights 2 (MDK) (.mdb/.gr2)**

   ![Import MDB/GR2](import.png)

2. Select the desired MDB file from the file browser and click **Import
   MDB/GR2** or double click the file.

   You can select more than one file by holding `SHIFT` while clicking.

### Example

We are going to take `PLC_MC_BARREL01.MDB` as an example. This is how it
should look when imported into Blender.

- `PLC_MC_BARREL01` is the placeable model.
- `PLC_MC_BARREL01_C2` is the collision mesh type 2. It's a coarse collision
  mesh.
- `PLC_MC_BARREL01_C3` is the collision mesh type 3. It's a detailed collision
  mesh.
