# UnityHDRPSpeedTreeShaders
Material replacements for getting SpeedTree models to work on HDRP Terrain. Highly experimental. Can't seem to get the normal map to work in any kind of way. Still trying though. Might have bugs and might not work as expected in evey project. Tested with HDRP 4.9.0 with Terrain.

# How-to
You'll need to assign the shaders contained in this repository to the materials used by the SpeedTree prefab. Beware though, you should not use the shaders which have "Optimized" in their name. The SpeedTree automatically uses them upon generation of the tree. Just go select Tree Creator Bark and Tree Creator Leaves for your bark and leaves materials and you should be good to go.
