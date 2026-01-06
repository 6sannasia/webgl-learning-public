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

## MP Highlights
### WebGL2 Warmup  
My edits - Midnight Starry Swirl:   
My first experiments with colors, **vertex and fragment shaders**, mathematical motion equations, and shapes.  
<img width="414" height="234" alt="Screenshot 2026-01-05 at 10 35 17 PM" src="https://github.com/user-attachments/assets/fd69492d-87d9-44cb-b398-84a9086ea7cc" />
![trim BC1E4A7B-D773-4B99-A819-F31592DD7BAB](https://github.com/user-attachments/assets/6d16811b-2268-4d83-b259-1367e6893729)

### Logo  
Learned to animate a 2D model using a matrix.
![trim 90A16EFE-976F-4285-9ECA-0C0AC4E898C6](https://github.com/user-attachments/assets/dc948bdd-0169-4d5b-95e3-80c217a7b274)

### Orbits   
Learned to send a model once to the GPU and draw that one copy multiple times per frame. Learned to set models at different origins and rotate around other models or axes.
<img width="376" height="250" alt="Screenshot 2026-01-05 at 10 45 30 PM" src="https://github.com/user-attachments/assets/94ef6a40-3c6c-4319-a9fe-403d33b0e43c" />  

![trim 7F6FBAC6-5131-4CD8-9585-9C3125A236F6](https://github.com/user-attachments/assets/0322b72d-61ca-4ed6-b95e-ae5f230932f6)


### Terrain   
Learned a simple fracture-based fractal. Used diffuse and specular lighting, namely Lambert and Blinn-Phong respectively. Had to use an Earth tone defined by 1>r>g>b>0, which was an unexpectedly cool way to explore color theory through graphics programming. Made sure the lighting was fixed relative to the terrain.
<img width="328" height="590" alt="Screenshot 2026-01-05 at 10 58 05 PM" src="https://github.com/user-attachments/assets/5d6b6e10-5257-45f6-930a-7d69f5036faa" />
<img width="297" height="540" alt="Screenshot 2026-01-05 at 10 57 55 PM" src="https://github.com/user-attachments/assets/0b93861e-6039-4e2d-a9cd-fdf8fc7a078b" />
<img width="349" height="579" alt="Screenshot 2026-01-05 at 11 02 07 PM" src="https://github.com/user-attachments/assets/c6177ed7-1c88-4a0a-b424-6f32fa34ce54" />  

![trim 10ADEE18-1DA5-496F-9526-BF842B9C249D](https://github.com/user-attachments/assets/ff1e98be-6796-4e87-b1da-965996d9715a)


### Flight 
Learned to control camera movement, rotation, and position using key presses, time, and frame drawing coordination. Example video's shown under TV Snow.  

### Textures   
Learned how to change materials immediately and apply them as a texture, even from a png.  
<img width="248" height="685" alt="Screenshot 2026-01-06 at 12 08 49 AM" src="https://github.com/user-attachments/assets/acbcad19-ae79-494c-8415-fb294a4e53f1" />
<img width="248" height="679" alt="Screenshot 2026-01-06 at 12 11 07 AM" src="https://github.com/user-attachments/assets/3e9e839f-753b-4030-9c27-f682d0a552bf" />
<img width="261" height="664" alt="Screenshot 2026-01-06 at 12 11 30 AM" src="https://github.com/user-attachments/assets/50046242-cc20-40ac-b102-9af2d78702a4" />
<img width="295" height="556" alt="Screenshot 2026-01-06 at 12 12 53 AM" src="https://github.com/user-attachments/assets/351994c6-5374-4797-9173-dfbdd83d056e" />  

### Raytracer in C++
Learned about raytracing, different light sources located in or infinitely far from the scene, how different geometries affect shadows, the intersection math behind shadow ray calculations, incorporating texture maps, etc.   
<img width="300" height="505" alt="Screenshot 2026-01-05 at 11 18 36 PM" src="https://github.com/user-attachments/assets/d9c5e8ae-97e6-4ed8-bc20-ef9dc0d96c13" /> 
<img width="300" height="346" alt="Screenshot 2026-01-06 at 12 00 35 AM" src="https://github.com/user-attachments/assets/5eae23db-e2f9-4dc8-bf5c-d6d77adcf8b6" />
<img width="300" height="640" alt="Screenshot 2026-01-06 at 12 01 40 AM" src="https://github.com/user-attachments/assets/56648081-f56c-4073-8611-7a9742584ff3" />

Elements:  
<img width="378" height="559" alt="Screenshot 2026-01-05 at 11 59 33 PM" src="https://github.com/user-attachments/assets/4642cc69-a23e-41bb-8866-07c4bfb0e6db" />



### Spheres   
Incorporated sphere physics like momentum, gravity, collisions and elasticity to create realistic movement between spheres in a box. Used random colors, and specular and diffuse lighting.
<img width="386" height="350" alt="Screenshot 2026-01-05 at 10 47 34 PM" src="https://github.com/user-attachments/assets/04da2071-b6a0-40a0-8435-074defa651c0" />  

![trim 30CB3D9E-80DD-49FF-9E30-3F42853F4B70](https://github.com/user-attachments/assets/26acfbbf-daad-43a4-8810-0eeedaf29b8f)


## Elective MPs  
### Cliffs  
Colored the terrain differently based on slope steepness.  
<img width="263" height="416" alt="Screenshot 2026-01-06 at 12 22 04 AM" src="https://github.com/user-attachments/assets/0d634dc6-c1d6-4c02-acdf-ab7fc5272099" />

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
<img width="260" height="479" alt="Screenshot 2026-01-06 at 12 25 26 AM" src="https://github.com/user-attachments/assets/5013937c-1767-4834-9ca6-b866327eb59b" />

### Lineograph 
Moved the model based on keys without clearing the canvas.
![trim 48DD8E9D-1869-407F-B192-EFC1967DF6FC](https://github.com/user-attachments/assets/796d899c-ebe4-4617-a7ba-72bf44c64388)

### Obj  
<img width="313" height="537" alt="Screenshot 2026-01-06 at 12 31 33 AM" src="https://github.com/user-attachments/assets/329bc4eb-5355-49bd-a46f-715ebcd28d32" />

### Parametric  
<img width="300" height="574" alt="Screenshot 2026-01-06 at 12 32 43 AM" src="https://github.com/user-attachments/assets/74fe234f-88d4-467d-85d8-40eeaa6dddc0" />
<img width="304" height="579" alt="Screenshot 2026-01-06 at 12 32 35 AM" src="https://github.com/user-attachments/assets/73f5a6d1-c99e-4dcc-9242-726b66d747b2" />

### Psychadelics  
Learned to use time, space, and math to color and move each fragment differently and smoothly.
![trim FC9060BD-9943-422B-986C-55F16B97C1BA](https://github.com/user-attachments/assets/b1b1d865-351a-44be-9ca4-fabb387fcd46)

### Weathering  
Simulated spheroidal weathering by replacing the height of a vertex by the average of itself and its neighbors, repeated a few times. 
<img width="263" height="581" alt="Screenshot 2026-01-06 at 12 35 08 AM" src="https://github.com/user-attachments/assets/c658ab4b-6c89-48a6-954e-0c0e951ed181" />
<img width="233" height="594" alt="Screenshot 2026-01-06 at 12 35 00 AM" src="https://github.com/user-attachments/assets/86008e06-2bb4-4735-b22f-6d9b2b28dd06" />



### TV Snow  
Built atop the Terrain, Flight, Drive projects. Added a sky and colored it to have a TV snow effect.  

I thought it'd be cool to understand TV snow's orderly randomness. 
Also, its chaos and connotations with "loss of connection" inspire me 
to use it in future projects like visualizing feelings of overwhelmedness, detachment, or numbness.    

<img width="526" height="380" alt="Screenshot 2026-01-05 at 9 04 43 PM" src="https://github.com/user-attachments/assets/e09fe378-1100-427a-b767-85c91d3eb8ac" />   

Also showcasing **Blinn-Phong** and **Lambert** lighting techniques as amplified below.
<img width="529" height="395" alt="Screenshot 2026-01-05 at 9 04 57 PM" src="https://github.com/user-attachments/assets/cc40fb56-5b2f-4534-9bfd-445061311494" />  

![trim B73DF5C2-B780-44C4-A4AD-35133E58096E](https://github.com/user-attachments/assets/8df1bf48-db51-4c97-a021-a832813473c3)





