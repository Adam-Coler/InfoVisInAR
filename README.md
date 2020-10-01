# InfoVisInAR
Environment for InfoVis Experiments on Multimodal Interactions

## Requires:
[Unity 2018.4.9f1](https://unity3d.com/get-unity/download/archive)

[DXR InfoVis Library](https://github.com/ronellsicat/DxR/tree/standalone)

[Microsoft MRTK](https://microsoft.github.io/MixedRealityToolkit-Unity/Documentation/Installation.html)

Visual Studio

Microsoft Hololens 2

## Steps

1. Add DXR Standalone - drag and drop all files in assets folder into unity project assets folder
2. [Start a project, don't deploy](https://docs.microsoft.com/en-us/windows/mixed-reality/develop/unity/tutorials/mr-learning-base-02)
* This will have a few issues because it is written for unity 2019
* For the build settings choose deply to hololens, and ARM (Not ARMX64, X64, X86)
3. To test navigate to DxRExamples-> paperplanes
* Mixed Reality Toolkit -> Add to Scene
4. Build project
*File -> Build and Run
* While it builds turn on the HoloLens 2
* Settings -> Network and Internet -> Advanced (on logged in WiFi) -> IPv4 Address (192.168.1.40 NuiLab)
5. Launch build .SLR from build folder
6. Change build settings to Release, ARM, Remote Machine
7. PRoject -> Properties -> Debugging -> Machine Name -> Hololens 2 IPv4 
8. Debug -> Start without debuging