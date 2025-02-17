# Snow Generator - Blender Addon

Snow Generator is a Blender addon that allows you to generate realistic snow meshes on top of your 3D objects. The addon provides an intuitive interface with various parameters to customize the appearance and properties of the snow.

## Features

- Generate snow meshes on any 3D object
- Control snow coverage percentage
- Adjust snow height and resolution
- Customize snow material properties (subsurface scattering, roughness, displacement)
- Option to add snow only on selected faces
- Automatic snow material generation with realistic properties
- Support for multiple object selection

## Installation

1. Download the `__init__.py` file
2. Open Blender and go to Edit > Preferences
3. Click on the "Add-ons" tab
4. Click "Install" and navigate to the downloaded `__init__.py` file
5. Enable the addon by checking the box next to "Object: Snow Generator"

## Usage

1. Select one or more objects in your scene
2. Open the sidebar in the 3D Viewport (press N)
3. Find the "Snow Generator" tab
4. Adjust the snow parameters as needed:
   - Coverage: Controls how much of the object is covered in snow (0-100%)
   - Height: Adjusts the thickness of the snow layer
   - Resolution: Controls the detail level of the snow
   - Particle Scale: Adjusts the size of individual snow particles
   - Material Settings: Customize the snow's appearance
5. Click "Add Snow" to generate the snow mesh
6. Use "Reset Settings" to restore default values if needed

## Parameters

### Main Settings
- **Coverage**: Percentage of the object to be covered with snow (0-100%)
- **Height**: Height/thickness of the snow layer (0.1-1.0)
- **Selected Faces**: Option to add snow only on selected faces

### Geometry Settings
- **Resolution**: Controls the metaball resolution for snow detail (0.1-2.0)
- **Particle Scale**: Adjusts the scale of snow particles (0.01-0.5)
- **Decimate Ratio**: Controls mesh optimization (0.1-1.0)

### Material Settings
- **Subsurface Weight**: Controls the strength of subsurface scattering
- **Roughness**: Adjusts the surface roughness of the snow
- **Displacement**: Controls the strength of surface displacement

## Requirements

- For Blender 4.3 or newer ( or older )
- Cycles render engine for full material support

## Support

For bug reports and feature requests, please visit:
https://github.com/james-gambino/snow-generator/issues 

## License

This addon is released under the Community Support license.

## Credits

Created by Igor Tkhorik

## Version History

- 1.0: Current version
- Initial release: Compatible with Blender 4.3+
