# Blender FBX Import/Export
This project is a fork of Blender's official FBX scene import/export addon.
The original addon comes with some inconveniences when working with game
engines like Unity and Unreal Engine. The purpose of this fork is to fix these.

Changes to the upstream code base include:
- There is no additional root bone created from the armature, ever
- The export option "Add Leaf Bones" is disabled by default
- The export option "Selected Objects" is enabled by default
- The export option "Smoothing" is set to "Face" by default