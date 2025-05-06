# Building Instructions for Book Scanner Copy Stand

This document provides instructions for building the Book Scanner Copy Stand originally designed by [caj on Thingiverse](https://www.thingiverse.com/thing:2466704).

## Configuration Options

The designer provides two main configuration options:

1. **Two Camera Book Scanner** - Uses two cameras for faster scanning
2. **Overhead Single Camera Stand** - Simpler design with a single overhead camera

Choose the configuration that best suits your needs based on your available equipment and scanning requirements.

## 3D Printing Recommendations

### Recommended Filament Types

- **PLA (Polylactic Acid)** - Recommended for most users
  - Easiest to print with minimal warping
  - Sufficient strength for a stationary device
  - Works on most 3D printers without special requirements
  - Good dimensional accuracy for parts that need to fit together

- **PETG (Polyethylene Terephthalate Glycol-modified)** - Alternative option
  - If you need more durability or impact resistance
  - If the scanner will be subject to higher stress or occasional bumps
  - If the scanner might be exposed to higher temperatures

### Print Settings

- **Layer Height**: 0.2mm recommended (0.1mm for higher detail in critical parts)
- **Infill**: 20-30% for most parts, 50%+ for parts that will be under stress
- **Perimeters/Shells**: At least 3 for good strength
- **Print Temperature**: Follow your filament manufacturer's recommendations
- **Build Plate**: Use a level bed with good adhesion (blue painter's tape works well for PLA)
- **Supports**: Most parts can be oriented to print without supports

## Required Parts

### 3D Printed Parts
Refer to the following files for a complete list of parts to print for your chosen configuration:
- Common components for all builds: [common_components_setup.md](config/common_components_setup.md)
- Single camera configuration: [single_camera_setup.md](config/single_camera_setup.md)
- Two camera configuration: [two_camera_setup.md](config/two_camera_setup.md)

The STL files are organized in the following directories:
- `models/common_components/` - Parts used in both configurations
- `models/single_camera_config/` - Parts specific to the single camera setup
- `models/two_camera_config/` - Parts specific to the two camera setup
- `models/common_alternatives/` - Optional parts and variants

### Hardware
- Picture frame glass (11x14 inch recommended)
  - The original creator recommends "main stay 11x14" frames found at Walmart
  - Most standard picture frames use the same thickness of glass
  - Avoid the largest frames as they typically have thicker glass
- Nuts and bolts (see detailed list in [BOM.md](hardware/BOM.md))
- For sourcing hardware components, see [SOURCING.md](hardware/SOURCING.md)

## Assembly Steps

### Common Components (For All Configurations)

1. Print all required common components from `models/common_components/`
2. Assemble the book stand frame:
   - Connect the right and left book stand parts using 50mm × 0.5mm screws and bolts (4 total)
3. Prepare the glass frame:
   - Use the glass frame connectors and edging pieces to create a frame for the glass
   - Insert the picture frame glass into the assembled frame

### Two Camera Configuration

1. Print all required parts for the two camera configuration from `models/two_camera_config/`
2. Assemble the common components as described above
3. Attach the connecting bars:
   - Use 20mm × 0.5mm screws and bolts (8 total) to connect the bars and adjustable base to stand base
4. Assemble the camera mount:
   - Connect the tops to extensions using 2 inch × 1/2 inch nuts and bolts (2 total)
   - Attach cameras to the top arms using 1/2 inch × 1/2 inch nuts and washers (2 total)

### Single Camera Configuration

1. Print all required parts for the single camera configuration from `models/single_camera_config/`
2. Assemble the common components as described above
3. Attach the stand base to the base support using 20mm × 0.5mm nuts and bolts (4 total)
4. Mount the extension using a 2 inch × 1/2 inch nut and bolt
5. Attach the camera to the single camera top arm using a 1/2 inch × 1/2 inch screw
6. If using a webcam instead of a camera, add the optional webcam adapter

## Using the Book Scanner

1. Place a book open on the glass surface
2. Position the camera(s) to capture clear images of the book pages
3. Take photos of each page spread
4. Use the Book Merge software (in the `software/book_merge/` directory) or any image processing software of your choice to process the scanned pages

## Alternative Parts

The repository includes some optional alternative parts in `models/common_alternatives/`:
- `half_extension.stl` - A shorter extension for smaller books or height-restricted areas
- `half_top_no_overhang.stl` - An alternative top piece for different camera positioning
- `dslr_webcam_adapter.stl` - An adapter specifically for DSLR cameras

These parts are optional and can be used with either configuration when you need specific modifications.

## Reference Diagrams

For help with assembly, refer to the complete diagram models in the `models/reference_diagrams/` directory. These files provide visual references for how all parts fit together but are not meant to be printed.

## Troubleshooting

If you encounter issues during the build process, please check the following:
- Ensure all 3D printed parts are correctly sized and fitted
- Verify that the camera is securely mounted and properly positioned
- Check that the lighting is adequate for clear photos

## Attribution

Remember that this project was created by caj on Thingiverse. When sharing your build or modifications, please provide appropriate credit to the original creator.