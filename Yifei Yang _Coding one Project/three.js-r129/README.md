# Yifei Yang_Project: Holographic Human Body

Project inspiration：
My project is Threejs html named”Holographic Human Body”. The inspiration for this project came from the fact that I was recently losing weight. I wanted to be able to observe my body objectively and holistically through holographic effects in order to identify the physical areas of my body that needed attention. So I have created a Threejs project with holographic body scanning effects.

Technical methods：
The source code for this Threejs web 3D holographic body effects project is based on the official version on github:https://github.com/mrdoob/three.js with no additional packaging and contains.The project mainly uses the following technical points:
1. Glb model loading
2. Holographic aperture advanced effects
3. body fresnel effects
4. Bottom highlighting and rotation

Production process：
This Three.js project includes the Renderer, Scene, Camera, lights and objects created in the scene.
It is packaged by“webpack”, which packages this file into “js” format and puts it into “Holographic Human Body .html.”

The production starts by determining the camera position and orientation. Next, I set whether it can be rotated and scaled. After that, I Set the dynamic damping factor to change the sensitivity of mouse dragging.
Also, Using the AxisHelper axis object, I added it into the scene we can see the exact position of the world coordinate system.
Next, I set the gloss level of the object.
The surreal holographic effect was created by creating a ground glow, a holographic pillar of light and a vortex.

Project outcomes：
The final outcome is that I can interact with the mouse to achieve the ability to freely zoom and drag the model to see the full 360 degree view of my own body shape. The atmosphere of holographic projection is expressed through special effects such as circles of light and swirls.


Video demonstration：
https://drive.google.com/file/d/1Vm6V_wLOVxPtHQWbppVyyNavNPYfCXaS/view?usp=sharing

