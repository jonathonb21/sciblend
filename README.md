# SciBlend - ParaView to Blender scientific visualization

**Developer:** [Jonathon Brunson](https://github.com/jonathonb21) | [jonathonbrunson21@gmail.com](mailto:jonathonbrunson21@gmail.com)

SciBlend is a Blender 4.2+ add-on and ParaView macro set I developed to move scientific simulation data from ParaView into Blender for publication-quality rendering. It supports static and animated X3D export, material management, null-object grouping, and scene presets tuned for research visuals.

### Overview

https://github.com/user-attachments/assets/675cdb0f-2aca-4328-be14-432923eab8e2

## Table of Contents

1. [Why SciBlend?](#why-sciblend)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Exporting Data from Paraview](#exporting-data-from-paraview)
6. [Usage in Blender](#usage-in-blender)
7. [Contributing](#contributing)
8. [Support](#support)
9. [Demos](#demos)

## Updated Features

- **Advanced X3D Import**: Import static and animated X3D data with customizable settings.
- **Material Management**: Easily create and apply shared materials to represent different data attributes.
- **Null Object Manipulation**: Create and manipulate null objects for better scene organization and data representation.
- **Object Grouping**: Efficiently group objects by type for improved scene management.
- **Quick Scene Setup**: Set up scenes with predefined lighting and render settings optimized for scientific visualization.
- **Dynamic Boolean Operations**: Perform boolean operations to create cutaways and cross-sections of your data.
- **User-Friendly Interface**: Access all functions through a streamlined UI panel designed for scientists and researchers.

## Why SciBlend?

Scientific simulations produce complex, multi-dimensional data. ParaView excels at analysis; Blender excels at rendering. SciBlend connects both so you can explore data interactively and export figures or animations for papers and talks.

## Features

- Import static and animated ParaView exports into Blender
- Shared materials, null objects, and grouping for large scenes
- Boolean cutaways and cross-sections
- One-click lighting and render presets

## Requirements

- Blender 4.2 or higher
- ParaView 5.13 or higher
- Python 3.11 (bundled with Blender 4.2)

## Installation

### 1. Paraview Macros Installation

1. Open the `Paraview Macros` folder in this repository.
2. In ParaView, go to **Macros -> Import New Macro** and import `export_static.py` and `export_animation.py`.

### 2. Blender Addon Installation

1. Zip the `SciBlend` folder.
2. In Blender: **Edit -> Preferences -> Add-ons -> Install** and enable **SciBlend**.

## Exporting Data from Paraview

Use **Export Static** or **Export Animation** from the Macros menu after selecting objects in the Pipeline Browser.

## Usage in Blender

Open the **SciBlend** panel in the 3D Viewport sidebar to import X3D, apply materials, and set up the scene.

## Contributing

Issues and pull requests are welcome on GitHub.

## Support

Contact [jonathonbrunson21@gmail.com](mailto:jonathonbrunson21@gmail.com) or open an issue at https://github.com/jonathonb21/sciblend/issues

## Demos

https://github.com/user-attachments/assets/4bc2184c-d9bc-4ba3-8bc3-a18c295fea1e

https://github.com/user-attachments/assets/2374c9a9-43c7-4ce7-8629-3a7adeb4e3d4

https://github.com/user-attachments/assets/e3b058e8-eb94-497c-853a-d520418599cf

## Full walkthrough

[Watch full walkthrough (100 MB)](https://github.com/jonathonb21/sciblend/blob/main/docs/media/sciblend-full-demo.mp4)

## Repository

https://github.com/jonathonb21/sciblend

## License

GPLv3 - see [LICENSE](LICENSE).