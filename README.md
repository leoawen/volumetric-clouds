# Scalable Volumetric Cloud Generator

A real-time volumetric cloud generator built with Three.js and GLSL shaders. This project allows for the creation of customizable, high-performance clouds with PBR lighting and post-processing effects like God Rays.

**Live Demo:** [https://seu-nome-de-usuario.github.io/gerador-nuvens-volumetricas/](https://leoawen.github.io/volumetric-clouds/)

![https://github.com/leoawen/volumetric-clouds/blob/main/images/volumetric-clouds-screenshoot-1.png](https://github.com/leoawen/volumetric-clouds/blob/main/images/volumetric-clouds-screenshoot-1.png)
![https://github.com/leoawen/volumetric-clouds/blob/main/images/volumetric-clouds-screenshoot-2.png](https://github.com/leoawen/volumetric-clouds/blob/main/images/volumetric-clouds-screenshoot-2.png)
![https://github.com/leoawen/volumetric-clouds/blob/main/images/volumetric-clouds-screenshoot-3.png](https://github.com/leoawen/volumetric-clouds/blob/main/images/volumetric-clouds-screenshoot-3.png)


## Features

-   **Procedural 3D Texture Baking:** Efficiently generates cloud density maps for real-time performance.
-   **Customizable Cloud Shape:** Control the overall shape, flattening, and noise deformation of the cloud via a simple GUI.
-   **Advanced Volumetric Ray Marching:** Renders realistic light scattering and absorption inside the cloud volume.
-   **PBR Lighting:** Integrates with ambient and directional lights for physically-based shading.
-   **Scene Occlusion:** Clouds correctly interact with and are occluded by other 3D objects in the scene.
-   **God Rays (Crepuscular Rays):** Post-processing effect that simulates light shafts scattering through the clouds.

## How to Use

Simply open the live demo link above. All controls are available in the GUI panel on the top right.

-   **Texture Generation:** Modify parameters like resolution, coverage, and noise scale, then click "Generate New Texture" to bake a new cloud map.
-   **Real-time Controls:** Adjust material, lighting, and animation parameters to see instant changes.

## License

This project is licensed under the MIT License.

---

Developed by **Leonardo Soares Gonçalves** with the assistance of AI vibecoding.
