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
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/gifs/starryswirl.gif" width="65%">  


### Logo  
Learned to animate a 2D model using a matrix.  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/gifs/logo.gif" width="45%">  

### Orbits   
Learned to send a model once to the GPU and draw that one copy multiple times per frame. Learned to set models at different origins and rotate around other models or axes.  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/Orbit1.png" width="50%">  

<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/gifs/orbits.gif" width="65%">  


### Terrain   
Learned a simple fracture-based fractal. Used diffuse and specular lighting, namely Lambert and Blinn-Phong respectively. Had to use an Earth tone defined by 1>r>g>b>0, which was an unexpectedly cool way to explore color theory through graphics programming. Made sure the lighting was fixed relative to the terrain.   
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/terrain1.png" width="40%">
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/terrain2.png" width="40%">
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/terrain3.png" width="40%">  

<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/gifs/terrain.gif" width="65%">  


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
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/raytracer1.png" width="40%"> 
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/raytracer2.png" width="40%">
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/raytracer3.png" width="40%">  

Elements:  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/raytracer_elements.png" width="50%">  



### Spheres   
Incorporated sphere physics like momentum, gravity, collisions and elasticity to create realistic movement between spheres in a box. Used random colors, and specular and diffuse lighting.  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/spheres1.png" width="40%"> 

<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/gifs/spheres.gif" width="65%">  


## Elective MPs  
### Cliffs  
Colored the terrain differently based on slope steepness.  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/gifs/cliffs.gif" width="65%">   

### CPU Jitter  

<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/gifs/CPUjitter.gif" width="45%">  

### GPU Jitter  

<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/gifs/GPUjitter.gif" width="45%">  

### Drive  
Seen under TV Snow  

### Fog  
Used an exponential fall-off equation to simulate fog.  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/gifs/fog.gif" width="65%">  

### Height Map  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/gifs/height_map.gif" width="65%">   

### Lineograph 
Moved the model based on keys without clearing the canvas.  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/gifs/lineograph.gif" width="45%">  

### Obj  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/obj1.png" width="50%"> 

### Parametric  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/parametric1.png" width="40%">  <img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/parametric2.png" width="40%"> 

### Psychadelics  
Learned to use time, space, and math to color and move each fragment differently and smoothly.  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/gifs/psychadelic.gif" width="65%">  

### Weathering  
Simulated spheroidal weathering by replacing the height of a vertex by the average of itself and its neighbors, repeated a few times.  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/weathering1.png" width="40%"> 
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/weathering2.png" width="40%"> 



### TV Snow  
Built atop the Terrain, Flight, Drive projects. Added a sky and colored it to have a TV snow effect.  

I thought it'd be cool to understand TV snow's orderly randomness. 
Also, its chaos and connotations with "loss of connection" inspire me 
to use it in future projects like visualizing feelings of overwhelmedness, detachment, or numbness.    

<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/TVsnow1.png" width="45%">   

Also showcasing **Blinn-Phong** and **Lambert** lighting techniques as amplified below.  
<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/TVsnow2.png" width="45%">   

<img src="https://github.com/6sannasia/webgl-learning-public/blob/main/media/gifs/TVsnow.gif" width="65%">  
