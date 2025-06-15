# Game Animation Sample with Overlay Layering | Unreal Engine 5

## Introduction

This project integrates the ALS Overlay Layering System into the new Unreal Engine Motion Matching Game Animation Sample.
Advanced Locomotion System (ALS) provides a nice Overlay System that allows us to alter the entire locomotion animation just by applying simple overlay poses. 

## Features

- Game Animation Sample
- Overlay layering system built with separate Anim Graphs and Linked Layers
- All overlays from ALS
- Basic weapon attach system from ALS
- Basic overlay switcher widget from ALS
- Removed Echo and Twinblast characters and Manny/Quinn 4k textures to lower project size

## Overview

An overview of the system is available on my YouTube channel [Polygon Hive](https://www.youtube.com/watch?v=RDWNfIqvWBk&list=PLs9e0eJQMI2aaulgKJzC8feN1UEwDkEnq)

## Migrating Plugin

To migrate the GASPALS plugin to your own Unreal Engine project, you can follow these steps:

1. Copy the `Plugins/GASPALS` folder to your project's `Plugins` folder.
2. Merge the `Plugins/GASPALS/Config` files with your project's `Config` files.
3. Copy `DefaultEngine.ini` content at the end of your project's `DefaultEngine.ini`.
4. Copy `Tags/GameplayTags_GASPALS.ini` to your project's `Config/Tags` folder.
5. Launch the project, an error message will prompt you to add collision settings, click add at the end of the message.
6. Enjoy :) 

## Contributing

Contributions are welcome! I hope that, with the help of the community, we can turn this into a next-gen fully featured locomotion system. 

Please follow these steps to contribute:

1. Clone the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Open a pull request.

Please ensure your code follows the project's coding and naming standards.

## License

[UE-Only Content - Licensed for Use Only with Unreal Engine-based Products](https://www.unrealengine.com/en-US/eula/content)

## Contact

For questions, suggestions, or feedback, please contact:

- Anas EL FERACHI - [anas@polygonhive.com](mailto:anas@polygonhive.com)

## Support My Work

- [Buy Me A Coffee](https://buymeacoffee.com/PolygonHive)
---

Thanks for checking out the project! I hope it helps you create amazing games.


