# CSresearch
My information technology research repository.
## Current research realm
* Voxel data structure
* Ray tracing

## The candidate topics:

### 1. *The voxel based shader language with ray tracing*

This is the topic that I am most interested in, but this topic is more about implementation than research.

#### Related research or project:
* GLSL, CG language
* Vulkan
* Efficent sparse voxel octree

### 2. *Ray tracing with image upscale*

With image upscale technique, we are able to reduce the number of the rays we cast, and we can also reduce the detail level of the voxel models.

#### Related research or project:
* DLSS Deep Learning Super Sampling
* Foveat rendering

### 3. *Foveat rendering apply to voxel octree in first person view for faster ray travesing*

According to foveat rendering, which is a method that track the user's look point to determine which spot of the screen(or VR headsets) should have greater resolution. Follow the idea, we can show more detailed voxels close to the center of our sight, as for those which are far from the center of our sight, we can ignore the detailed parts when tracing the rays. With this method, we can increase the speed when tracing the rays projecting to the parts far from the center of our sight. 

#### Related research or project:
* Efficient sparse voxel octree
* Foveat rendering

#### Related research or project:
* DLSS Deep Learning Super Sampling
* Foveat rendering

### 4. Some utilities 

Since ray tracing is relatively more "mature" than other realms, so focusing on utilities can give me more topics to research. But I have not thought of any of the topics about utilities(The only thing crossed my mind is making a game engine).

## Papers, tutorials, and books to read
1. Nvidia Efficient Sparse Voxel Octree  
[https://research.nvidia.com/sites/default/files/pubs/2010-02_Efficient-Sparse-Voxel/laine2010i3d_paper.pdf](https://)
2. Physically based rendering  
[https://pbr-book.org/4ed/contents](https://)
3. Vulkan tutorial  
[https://vulkan-tutorial.com/Overview](https://)
4. Brief introduction to foveat rendering  
[https://www.tobii.com/blog/what-is-foveated-rendering](https://)
