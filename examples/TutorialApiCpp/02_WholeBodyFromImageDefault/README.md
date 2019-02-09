# Whole Body From Image Default

## Quick Start

#### 1. Build OpenPose

````dos
> cd <OpenPoseDotNet_dir>
> BuildWindowsVS2015.bat <Debug/Release>
````

#### 2. Build OpenPoseDotNet.Native

````dos
> cd <OpenPoseDotNet_dir>\src\OpenPoseDotNet.Native
> BuildWindowsVS2015.bat <Debug/Release>
````

#### 3. Try Tutorial

````dos
> cd <OpenPoseDotNet_dir>\examples\TutorialApiCpp\02_WholeBodyFromImageDefault
> CopyOpenPose.bat <Debug/Release>
> dotnet run -c Release  -i "<OpenPoseDotNet_dir>\openpose\examples\media\COCO_val2014_000000000241.jpg"
````

<img src="images/example_turorial_2.png"/>