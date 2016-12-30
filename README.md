# gltf-test

Status of [glTF loader](https://github.com/KhronosGroup/glTF#webgl-engines) in some WebGL libraries.

## All Tests

[All Tests]( https://cx20.github.io/gltf-test/ )
- glTF Sample Test of 21 models x 3 formats x 7 libraries
- glTF 1.1 Test of 10 models x 2 formats x 7 libraries


## Windows + Chrome

glTF 1.0 Sample Models

| Model                                              | Screenshot                                                   |[Three.js r84dev](https://github.com/mrdoob/three.js/tree/dev/examples/js/loaders/GLTFLoader.js)                           |[Babylon.js 2.6dev](https://github.com/BabylonJS/Babylon.js/tree/master/loaders/src/glTF)                                                         |[Cesium.js 1.28](https://github.com/AnalyticalGraphicsInc/cesium/)                                               |[xeogl 2016.12.13](https://github.com/xeolabs/xeogl/tree/master/src/models/gltf)                                               |[GLBoost 2016.12.30](https://github.com/emadurandal/GLBoost/blob/master/src/js/middle_level/loader/GLTFLoader.js)                  |[Grimoire.js 2016.12.28](https://github.com/GrimoireGL/grimoirejs-gltf)                                                               |
|----------------------------------------------------|--------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|
|[Box](sampleModels/Box)                             |![](sampleModels/Box/screenshot/screenshot.png)               |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=Box&scale=1)                |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=Box&scale=1)                                     |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=Box)               |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=Box&scale=1)                      |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=Box&scale=1)                        |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=Box&scale=1)                        |
|[BoxWithoutIndices](sampleModels/BoxWithoutIndices) |![](sampleModels/BoxWithoutIndices/screenshot/screenshot.png) |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=BoxWithoutIndices&scale=1)  |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=BoxWithoutIndices&scale=1)                       |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=BoxWithoutIndices) |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=BoxWithoutIndices&scale=1) glTF-Embedded not work|:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=BoxWithoutIndices&scale=1)          |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=BoxWithoutIndices&scale=1)          |
|[Box Textured](sampleModels/BoxTextured)            |![](sampleModels/BoxTextured/screenshot/screenshot.png)       |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=BoxTextured&scale=1)        |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=BoxTextured&scale=1)                             |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=BoxTextured)       |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=BoxTextured&scale=1)              |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=BoxTextured&scale=1)                |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=BoxTextured&scale=1)                |
|[Box Semantics](sampleModels/BoxSemantics)          |![](sampleModels/BoxSemantics/screenshot/screenshot.png)      |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=BoxSemantics&scale=1)       |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=BoxSemantics&scale=1)                            |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=BoxSemantics)      |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=BoxSemantics&scale=1)             |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=BoxSemantics&scale=1)               |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=BoxSemantics&scale=1)               |
|[Duck](sampleModels/Duck)                           |![](sampleModels/Duck/screenshot/screenshot.png)              |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=Duck&scale=1)               |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=Duck&scale=1)                                    |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=Duck)              |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=Duck&scale=1)                     |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=Duck&scale=1)                       |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=Duck&scale=1)                       |
|[2 Cylinder Engine](sampleModels/2CylinderEngine)   |![](sampleModels/2CylinderEngine/screenshot/screenshot.png)   |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=2CylinderEngine&scale=0.005)|:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=2CylinderEngine&scale=0.005)                     |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=2CylinderEngine)   |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=2CylinderEngine&scale=0.005)      |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=2CylinderEngine&scale=0.005)        |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=2CylinderEngine&scale=0.005)        |
|[Reciprocating Saw](sampleModels/ReciprocatingSaw)  |![](sampleModels/ReciprocatingSaw/screenshot/screenshot.png)  |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=ReciprocatingSaw&scale=0.01)|:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=ReciprocatingSaw&scale=0.01)                     |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=ReciprocatingSaw)  |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=ReciprocatingSaw&scale=0.01)      |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=ReciprocatingSaw&scale=0.01)        |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=ReciprocatingSaw&scale=0.01)        |
|[Gearbox Assy](sampleModels/GearboxAssy)            |![](sampleModels/GearboxAssy/screenshot/screenshot.png)       |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=GearboxAssy&scale=1)        |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=GearboxAssy&scale=1)                             |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=GearboxAssy)       |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=GearboxAssy&scale=1)              |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=GearboxAssy&scale=1)                |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=GearboxAssy&scale=1)                |
|[Buggy](sampleModels/Buggy)                         |![](sampleModels/Buggy/screenshot/screenshot.png)             |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=Buggy&scale=0.02)           |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=Buggy&scale=0.02)                                |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=Buggy)             |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=Buggy&scale=0.02) only partial (glTF-Embedded)   |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=Buggy&scale=0.02)                   |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=Buggy&scale=0.02)                   |
|[Box Animated](sampleModels/BoxAnimated)            |![](sampleModels/BoxAnimated/screenshot/screenshot.gif)       |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=BoxAnimated&scale=1)        |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=BoxAnimated&scale=1)                             |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=BoxAnimated)       |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=BoxAnimated&scale=1) animation not support       |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=BoxAnimated&scale=1)                |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=BoxAnimated&scale=1)                |
|[Cesium Milk Truck](sampleModels/CesiumMilkTruck)   |![](sampleModels/CesiumMilkTruck/screenshot/screenshot.gif)   |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=CesiumMilkTruck&scale=0.5)  |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=CesiumMilkTruck&scale=0.5)                       |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=CesiumMilkTruck)   |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=CesiumMilkTruck&scale=0.5) animation not support |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=CesiumMilkTruck&scale=0.5)          |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=CesiumMilkTruck&scale=0.5)          |
|[Rigged Simple](sampleModels/RiggedSimple)          |![](sampleModels/RiggedSimple/screenshot/screenshot.gif)      |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=RiggedSimple&scale=0.2)     |:x: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=RiggedSimple&scale=1) has rotation problem                      |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=RiggedSimple)      |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=RiggedSimple&scale=0.2) animation not support    |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=RiggedSimple&scale=0.2)             |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=RiggedSimple&scale=0.2)             |
|[Rigged Figure](sampleModels/RiggedFigure)          |![](sampleModels/RiggedFigure/screenshot/screenshot.gif)      |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=RiggedFigure&scale=1)       |:x: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=RiggedFigure&scale=1) animation not work                        |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=RiggedFigure)      |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=RiggedFigure&scale=1) animation not support      |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=RiggedFigure&scale=1)               |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=RiggedFigure&scale=1)               |
|[Cesium Man](sampleModels/CesiumMan)                |![](sampleModels/CesiumMan/screenshot/screenshot.gif)         |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=CesiumMan&scale=1)          |:x: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=CesiumMan&scale=1) has rotation problem                         |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=CesiumMan)         |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=CesiumMan&scale=1) animation not support         |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=CesiumMan&scale=1)                  |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=CesiumMan&scale=1)                  |
|[Monster](sampleModels/Monster)                     |![](sampleModels/Monster/screenshot/screenshot.gif)           |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=Monster&scale=0.05)         |:x: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=Monster&scale=1) has nightmare dragon problem                   |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=Monster)           |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=Monster&scale=0.05) animation not support        |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=Monster&scale=0.05)                 |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=Monster&scale=0.05)                 |
|[BrainStem](sampleModels/BrainStem)                 |![](sampleModels/BrainStem/screenshot/screenshot.gif)         |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=BrainStem&scale=1)          |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=BrainStem&scale=1)                               |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=BrainStem)         |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=BrainStem&scale=1) only partial                  |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=BrainStem&scale=1)                  |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=BrainStem&scale=1)                  |
|[Virtual City](sampleModels/VC)                     |![](sampleModels/VC/screenshot/screenshot.gif)                |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=VC&scale=0.2)               |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=VC&scale=0.2)                                    |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=VC)                |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=VC&scale=0.2) animation not support              |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=VC&scale=0.2)                       |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=VC&scale=0.2)                       |
|[WalkingLady](sampleModels/WalkingLady)             |![](sampleModels/WalkingLady/screenshot/screenshot.gif)       |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=WalkingLady&scale=1)        |:x: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=WalkingLady&scale=1) has animation problem                      |:x: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=WalkingLady) has nightmare dragon problem |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=WalkingLady&scale=1) animation not support|:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=WalkingLady&scale=1)               |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=WalkingLady&scale=1)                |
|[Avocado](sampleModels/Avocado)                     |![](sampleModels/Avocado/screenshot/screenshot.png)           |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=Avocado&scale=0.5)          |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=Avocado&scale=0.5)                               |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=Avocado)           |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=Avocado&scale=0.5)                |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=Avocado&scale=0.5)                  |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=Avocado&scale=0.5)                  |
|[BarramundiFish](sampleModels/BarramundiFish)       |![](sampleModels/BarramundiFish/screenshot/screenshot.png)    |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=BarramundiFish&scale=0.05)  |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=BarramundiFish&scale=0.05)                       |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=BarramundiFish)    |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=BarramundiFish&scale=0.05)        |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=BarramundiFish&scale=0.05)          |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=BarramundiFish&scale=0.05)          |
|[SmilingFace](sampleModels/SmilingFace)             |![](sampleModels/SmilingFace/screenshot/screenshot.png)       |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?model=SmilingFace&scale=1.0)      |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?model=SmilingFace&scale=1.0)                           |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?model=SmilingFace)       |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?model=SmilingFace&scale=1.0)            |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?model=SmilingFace&scale=1.0)              |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?model=SmilingFace&scale=1.0)              |

glTF 1.1 Tutorial models

|Model                                                                     |Screenshot                                                                     |[Three.js r84dev](https://github.com/mrdoob/three.js/tree/dev/examples/js/loaders/GLTFLoader.js)                                                           |[Babylon.js 2.6dev](https://github.com/BabylonJS/Babylon.js/tree/master/loaders/src/glTF)                                                                    |[Cesium.js 1.28](https://github.com/AnalyticalGraphicsInc/cesium/)                                                                                        |[xeogl 2016.12.13](https://github.com/xeolabs/xeogl/tree/master/src/models/gltf)                                                                         |[GLBoost 2016.12.30](https://github.com/emadurandal/GLBoost/blob/master/src/js/middle_level/loader/GLTFLoader.js)                                                         |[Grimoire.js 2016.12.28](https://github.com/GrimoireGL/grimoirejs-gltf)                                                                                       |
|--------------------------------------------------------------------------|-------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
|[Triangle Without Indices](TriangleWithoutIndices)                        |![](tutorialModels/TriangleWithoutIndices/screenshot/screenshot.png)           |:x: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?category=tutorialModels&model=TriangleWithoutIndices&scale=1&type=glTF)          |:x: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?category=tutorialModels&model=TriangleWithoutIndices&scale=1&type=glTF)          |:x: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?category=tutorialModels&model=TriangleWithoutIndices&scale=1&type=glTF)          |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?category=tutorialModels&model=TriangleWithoutIndices&scale=1&type=glTF)          |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?category=tutorialModels&model=TriangleWithoutIndices&scale=1&type=glTF)          |:x: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?category=tutorialModels&model=TriangleWithoutIndices&scale=1&type=glTF)          |
|[Triangle](Triangle)                                                      |![](tutorialModels/Triangle/screenshot/screenshot.png)                         |:x: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?category=tutorialModels&model=Triangle&scale=1&type=glTF)                        |:x: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?category=tutorialModels&model=Triangle&scale=1&type=glTF)                        |:x: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?category=tutorialModels&model=Triangle&scale=1&type=glTF)                        |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?category=tutorialModels&model=Triangle&scale=1&type=glTF)                        |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?category=tutorialModels&model=Triangle&scale=1&type=glTF)                        |:x: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?category=tutorialModels&model=Triangle&scale=1&type=glTF)                        |
|[Animated Triangle](AnimatedTriangle)                                     |![](tutorialModels/AnimatedTriangle/screenshot/screenshot.gif)                 |:x: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?category=tutorialModels&model=AnimatedTriangle&scale=1&type=glTF)                |:x: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?category=tutorialModels&model=AnimatedTriangle&scale=1&type=glTF)                |:x: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?category=tutorialModels&model=AnimatedTriangle&scale=1&type=glTF)                |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?category=tutorialModels&model=AnimatedTriangle&scale=1&type=glTF)                |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?category=tutorialModels&model=AnimatedTriangle&scale=1&type=glTF)                |:x: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?category=tutorialModels&model=AnimatedTriangle&scale=1&type=glTF)                |
|[Triangle With Simple Material](TriangleWithSimpleMaterial)               |![](tutorialModels/TriangleWithSimpleMaterial/screenshot/screenshot.png)       |:x: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?category=tutorialModels&model=TriangleWithSimpleMaterial&scale=1&type=glTF)      |:x: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?category=tutorialModels&model=TriangleWithSimpleMaterial&scale=1&type=glTF)      |:x: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?category=tutorialModels&model=TriangleWithSimpleMaterial&scale=1&type=glTF)      |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?category=tutorialModels&model=TriangleWithSimpleMaterial&scale=1&type=glTF)      |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?category=tutorialModels&model=TriangleWithSimpleMaterial&scale=1&type=glTF)      |:x: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?category=tutorialModels&model=TriangleWithSimpleMaterial&scale=1&type=glTF)      |
|[Simple Meshes](SimpleMeshes)                                             |![](tutorialModels/SimpleMeshes/screenshot/screenshot.png)                     |:x: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?category=tutorialModels&model=SimpleMeshes&scale=1&type=glTF)                    |:x: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?category=tutorialModels&model=SimpleMeshes&scale=1&type=glTF)                    |:x: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?category=tutorialModels&model=SimpleMeshes&scale=1&type=glTF)                    |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?category=tutorialModels&model=SimpleMeshes&scale=1&type=glTF)                    |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?category=tutorialModels&model=SimpleMeshes&scale=1&type=glTF)                    |:x: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?category=tutorialModels&model=SimpleMeshes&scale=1&type=glTF)                    |
|[Simple Meshes With Advanced Material](SimpleMeshesWithAdvancedMaterial)  |![](tutorialModels/SimpleMeshesWithAdvancedMaterial/screenshot/screenshot.png) |:x: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?category=tutorialModels&model=SimpleMeshesWithAdvancedMaterial&scale=1&type=glTF)|:x: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?category=tutorialModels&model=SimpleMeshesWithAdvancedMaterial&scale=1&type=glTF)|:x: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?category=tutorialModels&model=SimpleMeshesWithAdvancedMaterial&scale=1&type=glTF)|:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?category=tutorialModels&model=SimpleMeshesWithAdvancedMaterial&scale=1&type=glTF)|:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?category=tutorialModels&model=SimpleMeshesWithAdvancedMaterial&scale=1&type=glTF)|:x: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?category=tutorialModels&model=SimpleMeshesWithAdvancedMaterial&scale=1&type=glTF)|
|[Simple Opacity](SimpleOpacity)                                           |![](tutorialModels/SimpleOpacity/screenshot/screenshot.png)                    |:x: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?category=tutorialModels&model=SimpleOpacity&scale=1&type=glTF)                   |:x: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?category=tutorialModels&model=SimpleOpacity&scale=1&type=glTF)                   |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?category=tutorialModels&model=SimpleOpacity&scale=1&type=glTF)    |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?category=tutorialModels&model=SimpleOpacity&scale=1&type=glTF)                   |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?category=tutorialModels&model=SimpleOpacity&scale=1&type=glTF)                   |:x: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?category=tutorialModels&model=SimpleOpacity&scale=1&type=glTF)                   |
|[Simple Texture](SimpleTexture)                                           |![](tutorialModels/SimpleTexture/screenshot/screenshot.png)                    |:x: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?category=tutorialModels&model=SimpleTexture&scale=1&type=glTF)                   |:x: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?category=tutorialModels&model=SimpleTexture&scale=1&type=glTF)                   |:x: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?category=tutorialModels&model=SimpleTexture&scale=1&type=glTF)                   |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?category=tutorialModels&model=SimpleTexture&scale=1&type=glTF)                   |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?category=tutorialModels&model=SimpleTexture&scale=1&type=glTF)                   |:x: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?category=tutorialModels&model=SimpleTexture&scale=1&type=glTF)                   |
|[Cameras](Cameras)                                                        |![](tutorialModels/Cameras/screenshot/screenshot.png)                          |:x: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?category=tutorialModels&model=Cameras&scale=1&type=glTF)                         |:x: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?category=tutorialModels&model=Cameras&scale=1&type=glTF)                         |:x: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?category=tutorialModels&model=Cameras&scale=1&type=glTF)                         |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?category=tutorialModels&model=Cameras&scale=1&type=glTF)                         |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?category=tutorialModels&model=Cameras&scale=1&type=glTF)                         |:x: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?category=tutorialModels&model=Cameras&scale=1&type=glTF)                         |
|[Simple Skin](SimpleSkin)                                                 |![](tutorialModels/SimpleSkin/screenshot/screenshot.gif)                       |:x: [Sample](https://cx20.github.io/gltf-test/examples/threejs/index.html?category=tutorialModels&model=SimpleSkin&scale=1&type=glTF)                      |:x: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/index.html?category=tutorialModels&model=SimpleSkin&scale=1&type=glTF)                      |:x: [Sample](https://cx20.github.io/gltf-test/examples/cesium/index.html?category=tutorialModels&model=SimpleSkin&scale=1&type=glTF)                      |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeogl/index.html?category=tutorialModels&model=SimpleSkin&scale=1&type=glTF)                      |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/index.html?category=tutorialModels&model=SimpleSkin&scale=1&type=glTF)                      |:x: [Sample](https://cx20.github.io/gltf-test/examples/grimoiregl/index.html?category=tutorialModels&model=SimpleSkin&scale=1&type=glTF)                      |

