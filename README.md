---
page_type: sample
languages:
- cpp
products:
- windows
- windows-uwp
statusNotificationTargets:
- codefirst@microsoft.com
---

<!---
  category: Gaming GraphicsAndAnimation
  samplefwlink: http://go.microsoft.com/fwlink/?LinkId=624011
--->

# DirectX marble maze game sample

This is a mini-app that shows how to build a basic 3D game using DirectX on the Universal Windows Platform (UWP). 
It's a simple labyrinth game where the player is challenged to roll a marble through a maze of pitfalls using tilt, mouse, or gamepad controls.

> Note - This sample is targeted and tested for Windows 10, version 2004 (10.0; Build 19041, also known as the Windows 10 May 2020 Update), and Visual Studio 2019. If you prefer, you can use project properties to retarget the project(s) to Windows 10, version 1903 (10.0; Build 18362, also known as the Windows 10 May 2019 Update).

![MarbleMaze app in action](MarbleMaze.png)

This sample is written in C++ and requires some experience with graphics programming and DirectX. 
Complete content that examines this code can be found at 
[Developing Marble Maze, a UWP game in C++ and DirectX](https://docs.microsoft.com/windows/uwp/gaming/developing-marble-maze-a-windows-store-game-in-cpp-and-directx).

## Features

- Incorporating the Windows Runtime into your DirectX game 
- Using DirectX to render 3D graphics for display in a game 
- Implementing simple vertex and pixel shaders with HLSL 
- Developing simple physics and collision behaviors in a DirectX game 
- Handling input from accelerometer, touch, mouse, and game controller with the Windows Runtime
- Playing and mixing sound effects and background music with XAudio2 

## Related topics

* [Developing Marble Maze, a UWP game in C++ and DirectX](https://docs.microsoft.com/windows/uwp/gaming/developing-marble-maze-a-windows-store-game-in-cpp-and-directx)
* [Create a simple UWP game with DirectX](https://docs.microsoft.com/windows/uwp/gaming/tutorial--create-your-first-uwp-directx-game)
* [Game programming](https://docs.microsoft.com/windows/uwp/gaming/index)
* [DirectX programming](https://docs.microsoft.com/windows/uwp/gaming/directx-programming)
* [Direct3D Graphics Learning Guide](https://docs.microsoft.com/windows/uwp/graphics-concepts/)
* [Direct2D](https://docs.microsoft.com/windows/desktop/Direct2D/direct2d-portal) 
* [HLSL](https://docs.microsoft.com/windows/desktop/direct3dhlsl/dx-graphics-hlsl)
* [XAudio2 APIs](https://docs.microsoft.com/windows/desktop/xaudio2/xaudio2-apis-portal)

## Universal Windows Platform development

### Prerequisites

- Windows 10. Minimum: Windows 10, version 1809 (10.0; Build 17763, also known as the Windows 10 October 2018 Update).
- [Windows 10 SDK](https://developer.microsoft.com/windows/downloads/windows-10-sdk). Minimum: Windows SDK version 10.0.17763.0 (Windows 10, version 1809).
- [Visual Studio 2019](https://visualstudio.microsoft.com/downloads/) (or Visual Studio 2017). You can use the free Visual Studio Community Edition to build and run Windows Universal Platform (UWP) apps.

To get the latest updates to Windows and the development tools, and to help shape their development, join 
the [Windows Insider Program](https://insider.windows.com).

## Build the sample

1. Unzip the archive.
2. Start Microsoft Visual Studio 2017 and select **File** \> **Open** \> **Project/Solution...**
3. Starting in the folder where you unzipped the sample, go to the **C++** subfolder. Double-click **MarbleMaze_VS2017.sln**.
4. Press Ctrl+Shift+B, or select **Build** \> **Build Solution**.

## Run the sample

The next steps depend on whether you just want to deploy the sample or you want to both deploy and run it.

### Deploying the sample

Select **Build > Deploy Solution**. 

### Deploying and running the sample

To run the sample with debugging, press F5 or select **Debug > Start Debugging**. To run the sample without debugging, press Ctrl+F5 or select **Debug > Start Without Debugging**.



