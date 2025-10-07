# Walnut

Walnut is a simple application framework built with Dear ImGui and designed to be used with Vulkan.
Basically this means you can seemlessly blend real-time Vulkan rendering with a great UI library to build desktop applications. 

Originally forked from [StudioCherno/Walnut](https://github.com/StudioCherno/Walnut), now includes features such as:

- Minimum and Maximum window size.
- Logo size control.
- Updated output dir to be output/...
- The ability to disable Walnuts logging system.
- Titlebar icon customisation.
- Titlebar button colour customisation.
- Titlebar size and y padding customisation.

All from your own file, so you dont have to modify Walnut whenever you want to change the logo of your application.

## Requirements
- [Visual Studio 2022](https://visualstudio.com) (not strictly required, however included setup scripts only support this)
- [Vulkan SDK](https://vulkan.lunarg.com/sdk/home#windows) (preferably a recent version)

## Getting Started
Once you've cloned, run `scripts/Setup.bat` to generate Visual Studio 2022 solution/project files. Once you've opened the solution, you can run the WalnutApp project to see a basic example (code in `WalnutApp.cpp`). I recommend modifying that WalnutApp project to create your own application, as everything should be setup and ready to go.

### 3rd party libaries
- [Dear ImGui](https://github.com/ocornut/imgui)
- [GLFW](https://github.com/glfw/glfw)
- [stb_image](https://github.com/nothings/stb)
- [GLM](https://github.com/g-truc/glm) (included for convenience)

### Additional
- Walnut uses the [Roboto](https://fonts.google.com/specimen/Roboto) font ([Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0))