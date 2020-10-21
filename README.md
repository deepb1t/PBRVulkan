# Physically based renderer in Vulkan
####  Vulkan real-time path tracer engine

This project is a framework where you can create/test new shaders in real-time physically based ray tracing system.

#### How to run:

1) Download [VulkanSDK](https://vulkan.lunarg.com/sdk/home#windows) and place it in `C:/VulkanSDK/x.x.x.x/`.
2) Run `install.bat` script to download all necessary libraries.
3) For shaders compliation you will need `python` and `glslc` available form the shell level. `glslc` can be found for instance in `C:/VulkanSDK/x.x.x.x/Bin32/glslc.exe`.

#### Environment variables:
Add vulkan path `C:/VulkanSDK/x.x.x.x/Bin32` to the `Path` variable \
System variable needed for the project
1) `VULKAN_SDK`
2) `VK_SDK_PATH`

C++17 is needed to compile the project.

#### Assets
The scene description and assets are taken from [GLSL-PathTracer](https://github.com/knightcrawler25/GLSL-PathTracer) project [4]. The whole dataset can be downloaded from [link](https://drive.google.com/file/d/1UFMMoVb5uB7WIvCeHOfQ2dCQSxNMXluB/view).

Download the assets folder and place it in `PBRVulkan/Assets/Scenes/`. The folder strucutre has to be as follows:

```
PBRVulkan/Assets/Scenes/
    bedroom/
    coffee_cart/
    HDR/
    bedroom.scene
    coffee_cart.scene
    ...
```

#### References/Credits:
[0] [Vulkan Tutorial](https://vulkan-tutorial.com/) \
[1] [Vulkan Ray Tracing Tutorial](https://nvpro-samples.github.io/vk_raytracing_tutorial_KHR/) \
[2] [PBR Book](http://www.pbr-book.org/3ed-2018/contents.html) \
[4] [GLSL-PathTracer](https://github.com/knightcrawler25/GLSL-PathTracer) \
[5] [RayTracingInVulkan](https://github.com/GPSnoopy/RayTracingInVulkan)
