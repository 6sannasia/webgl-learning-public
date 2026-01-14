# Learning WebGL   
Adding whimsy to projects from [CS 418](https://cs418.cs.illinois.edu/website/mp/)!    

````
My Current Favorites (for their textures, movement, & creative potential)
- TV Snow
- Psychadelics 
- Raytracer in C++
- Obj with Textures
- WebGL2 Warmup - Starry Swirl
  ````

To run WebGL files, use:  ```python3 -m http.server```  
To run Raytracer's C++ files, here's an example command: 
```
make clean
make build
make run file=raytracer-files/ray-shadow-plane.txt
```

## Core MPs
### WebGL2 Warmup  
My edits - Midnight Starry Swirl:   
My first experiments with colors, **vertex and fragment shaders**, mathematical motion equations, and shapes.  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/starry_swirl1.png" width="55%">  
![trim BC1E4A7B-D773-4B99-A819-F31592DD7BAB](https://github.com/user-attachments/assets/6d16811b-2268-4d83-b259-1367e6893729)

### Logo  
Learned to animate a 2D model using a matrix.  
![trim 90A16EFE-976F-4285-9ECA-0C0AC4E898C6](https://github.com/user-attachments/assets/dc948bdd-0169-4d5b-95e3-80c217a7b274)

### Orbits   
Learned to send a model once to the GPU and draw that one copy multiple times per frame. Learned to set models at different origins and rotate around other models or axes.  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/Orbit1.png" width="50%">  

![trim 7F6FBAC6-5131-4CD8-9585-9C3125A236F6](https://github.com/user-attachments/assets/0322b72d-61ca-4ed6-b95e-ae5f230932f6)


### Terrain   
Learned a simple fracture-based fractal. Used diffuse and specular lighting, namely Lambert and Blinn-Phong respectively. Had to use an Earth tone defined by 1>r>g>b>0, which was an unexpectedly cool way to explore color theory through graphics programming. Made sure the lighting was fixed relative to the terrain.   
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/terrain1.png" width="40%">
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/terrain2.png" width="40%">
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/terrain3.png" width="40%">

![trim 10ADEE18-1DA5-496F-9526-BF842B9C249D](https://github.com/user-attachments/assets/ff1e98be-6796-4e87-b1da-965996d9715a)


### Flight 
Learned to control camera movement, rotation, and position using key presses, time, and frame drawing coordination. Example video's shown under TV Snow.  

### Textures   
Learned how to change materials immediately and apply them as a texture, even from a png.  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/textures1.png" width="35%">
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/textures2.png" width="35%">
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/textures3.png" width="35%">
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/textures4.png" width="55%">

### Raytracer in C++
Learned about raytracing, different light sources located in or infinitely far from the scene, how different geometries affect shadows, the intersection math behind shadow ray calculations, incorporating texture maps, etc.   
<img width="300" height="505" alt="Screenshot 2026-01-05 at 11 18 36 PM" src="https://github.com/user-attachments/assets/d9c5e8ae-97e6-4ed8-bc20-ef9dc0d96c13" /> 
<img width="300" height="346" alt="Screenshot 2026-01-06 at 12 00 35 AM" src="https://github.com/user-attachments/assets/5eae23db-e2f9-4dc8-bf5c-d6d77adcf8b6" />
<img width="300" height="640" alt="Screenshot 2026-01-06 at 12 01 40 AM" src="https://github.com/user-attachments/assets/56648081-f56c-4073-8611-7a9742584ff3" />

Elements:  
<img width="378" height="559" alt="Screenshot 2026-01-05 at 11 59 33 PM" src="https://github.com/user-attachments/assets/4642cc69-a23e-41bb-8866-07c4bfb0e6db" />



### Spheres   
Incorporated sphere physics like momentum, gravity, collisions and elasticity to create realistic movement between spheres in a box. Used random colors, and specular and diffuse lighting.  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/spheres1.png" width="40%"> 

![trim 30CB3D9E-80DD-49FF-9E30-3F42853F4B70](https://github.com/user-attachments/assets/26acfbbf-daad-43a4-8810-0eeedaf29b8f)


## Elective MPs  
### Cliffs  
Colored the terrain differently based on slope steepness.  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/cliffs1.png" width="40%"> 

### CPU Jitter  

![trim 28320DE2-C508-47CF-AF4D-E7ADE05C7798](https://github.com/user-attachments/assets/3fb29baa-c60e-4b84-a8c4-25ce645fc0ba)

### GPU Jitter  

![trim DEF49291-6891-4FA9-9532-9B5C1C30CC75](https://github.com/user-attachments/assets/e721d2a7-469f-4a24-a8ae-0179f315e7de)

### Drive  
Seen under TV Snow  

### Fog  
Used an exponential fall-off equation to simulate fog.  
![trim 3B915841-3767-43B1-A220-6757CD70245D](https://github.com/user-attachments/assets/fb157cfc-0b94-44ab-b57c-fbb403a1ad4c)

### Height Map  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/height_map1.png" width="40%"> 

### Lineograph 
Moved the model based on keys without clearing the canvas.  
![trim 48DD8E9D-1869-407F-B192-EFC1967DF6FC](https://github.com/user-attachments/assets/796d899c-ebe4-4617-a7ba-72bf44c64388)

### Obj  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/obj1.png" width="50%"> 

### Parametric  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/parametric1.png" width="40%"> 
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/parametric2.png" width="40%"> 

### Psychadelics  
Learned to use time, space, and math to color and move each fragment differently and smoothly.  
![trim FC9060BD-9943-422B-986C-55F16B97C1BA](https://github.com/user-attachments/assets/b1b1d865-351a-44be-9ca4-fabb387fcd46)

### Weathering  
Simulated spheroidal weathering by replacing the height of a vertex by the average of itself and its neighbors, repeated a few times.  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/weathering1.png" width="40%"> 
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/weathering2.png" width="40%"> 



### TV Snow  
Built atop the Terrain, Flight, Drive projects. Added a sky and colored it to have a TV snow effect.  

I thought it'd be cool to understand TV snow's orderly randomness. 
Also, its chaos and connotations with "loss of connection" inspire me 
to use it in future projects like visualizing feelings of overwhelmedness, detachment, or numbness.    

<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/TVsnow1.png" width="40%">   

Also showcasing **Blinn-Phong** and **Lambert** lighting techniques as amplified below.  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/TVsnow2.png" width="40%">   

![trim B73DF5C2-B780-44C4-A4AD-35133E58096E](https://github.com/user-attachments/assets/8df1bf48-db51-4c97-a021-a832813473c3)
