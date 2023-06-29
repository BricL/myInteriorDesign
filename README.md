# My Interior Design
Practicing lightmapping in Unity. 

"There are many realistic samples of interior design available on Unity and Unreal today. We just need to set up the lightmap properly, and everything will be automatically taken care of. However, that's easier said than done."

# My Workflow
1. Create the lighting asset for the scene.
2. If needed, switch the source of environment lighting to "Color," especially for interior design.
3. Place additional lights and specify which ones are static (baked) and which ones are real-time.
4. Check the static properties of game objects to contribute to global illumination (GI) and reflection probes.
5. Configure the lightmap settings. Firstly, adjust the "size" and "lightmap resolution" to half of their default values. This will speed up the lightmap calculation.
6. Fine-tune the light positions, direct samples, indirect samples, and create reflection probes if necessary for environment reflections.
7. Repeat steps 5 and 6 until you are satisfied with the results.

![](Docs/Imgs/1687025227043.png)
