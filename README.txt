Pages URL: https://gu-computer-graphics.github.io/team-project-team-rammus/

Our team's scene contains Rammus, a character from League of Legends, and a turret from the same game on a flat plane with a sun. 
Rammus can roll around said turret with a button press(G) and the turret can shoot at him(C).

---------------------
Implemented Features
---------------------
Curved Lines and Surfaces: A Bezier curve is defined so that Rammus follows a path for the animation.

Animation: Rammus follows a path defined by a Bezier curve whilst in his ball form. We also have a turret shot animation, the turret shoots at Rammus with a ball of light.

Materials, Shading and Lighting: Rammus and the scene uses Phong materials and the scene has ambient lighting, with color interpolation working. The turret also uses different colors and shades to represent different materials.

Shadows: Rammus and the scene utilize shadows in their implementation, as designated by a spotlight shining on the scene with a sun model.

Hierarchical Modeling: Both Rammus and the turret are objects with multiple parts and objects in the makeup.

User Interaction: There are multiple ways for the user to interact...
- G to start Rammus rolling.
- a GUI to change turret size...
- ...and the ability to change the camera location with 1-4.
- Hold C to have the turret shoot at Rammus.

---------------------
Resources Used
---------------------

Three.JS: https://threejs.org/