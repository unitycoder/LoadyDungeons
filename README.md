![LD](https://user-images.githubusercontent.com/263776/110165036-dde21300-7db7-11eb-8f49-e7745ed44b35.png)

Loady Dungeons is a simple **demo** intended to teach the basics of Addressables and Unity's Cloud Content Delivery.

### Prerequisites
* Unity Version: 2019.4 LTS
* Addressables Package: 1.16.16

### More Resources
* If you want to watch the step by step guide, go to our video: [LINK TO VIDEO]()
* For a written guide on how to get started with Cloud Content Delivery, visit the following link [LINK TO GUIDE]()

![AllLevels](https://user-images.githubusercontent.com/263776/110165940-42ea3880-7db9-11eb-871c-13e4933e2540.png)

### Asset Bundle Architecture
The project uses a simple approach for managing the bundles with the assets. Each **gameplay scene** is bundled in a separate group (Level_00, Level_01, Level_02 and Level_03). Level_01 is bundled with the game, so it uses the LocalBuildPath and LocalLoadPath. The other levels and the Hats group(containing prefabs as Addressable assets) are bundled separate (and downloaded from the cloud), they use the RemoteBuilPath and RemoteLoadPath.

![Asset Architecture](https://user-images.githubusercontent.com/263776/110168293-9611ba80-7dbc-11eb-9945-417a16c3386d.jpg)
