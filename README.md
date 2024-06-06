# CSresearch
My information technology research repository.
## Current research realm
* Voxel data structure
* Ray tracing

## The candidate topics:

### 1. ~~*The voxel based shader language with ray tracing~~

This is the topic that I am most interested in, but this topic is more about implementation than research. And I think the shader language isn't necessary since there is a similar library which allows us to use GPU for voxel process.

#### Related research or project:
* GLSL, CG language
* Vulkan
* Efficent sparse voxel octree

### 2. ~~*Ray tracing with image upscale~~

With image upscale technique, we are able to reduce the number of the rays we cast, and we can also reduce the detail level of the voxel models.

#### Related research or project:
* DLSS Deep Learning Super Sampling
* Foveat rendering

### 3. *Foveated-rendering-like method apply to voxel octree for faster ray traversing*

According to foveat rendering, which is a method that track the user's look point to determine which spot of the screen(or VR headsets) should have greater resolution. Follow the idea, we can show more detailed voxels close to the center of our sight, as for those which are far from the center of our sight, we can ignore the detailed parts when tracing the rays. With this method, we can increase the speed when tracing the rays projecting to the parts far from the center of our sight. 

#### Related research or project:
* Efficient sparse voxel octree
* Foveat rendering  
[https://youtu.be/lNX0wCdD2LA](https://)

#### Module I will use
* OpenCV
* * For image process and screen create.
* OpenGL
* * For 3D render
* OpenVDB / NanoVDB
* * For Voxel data process
* glm / Eigen(Optional)
* * Math library
* OpenCL
* * GPU calculation

#### Repository
[https://github.com/TurtleJayWang/FRSVO.git](https://)

## Papers, tutorials, and books to read
1. Nvidia Efficient Sparse Voxel Octree  
[https://research.nvidia.com/sites/default/files/pubs/2010-02_Efficient-Sparse-Voxel/laine2010i3d_paper.pdf](https://)
2. Physically based rendering  
[https://pbr-book.org/4ed/contents](https://)
3. Foveated Ray Tracing for VR Headsets  
[https://link.springer.com/chapter/10.1007/978-3-030-05710-7_9](https://)
5. Brief introduction to foveat rendering  
[https://www.tobii.com/blog/what-is-foveated-rendering](https://)
6. Image Upscaling for Ray Traced Foveated Rendering  
[https://lup.lub.lu.se/luur/download?func=downloadFile&recordOId=9091182&fileOId=9091183](https://)
7. An integrative view of foveated rendering  
[https://dl.acm.org/doi/abs/10.1016/j.cag.2021.10.010](https://)
8. An integrative view of foveated rendering  
[https://www.sciencedirect.com/science/article/pii/S0097849321002211?via%3Dihub#sec1](https://)
