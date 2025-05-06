# Single Camera Setup Configuration

This guide will help you build the single-camera version of the book scanner copy stand. This configuration uses the common book stand and glass components along with a single overhead camera mount.

## Required Components

### Common Components
First, ensure you have all the common components assembled as described in `config/common_components.md`:
- Book stand frame (right and left book stand parts)
- Glass frame with picture frame glass

### Additional 3D Printed Parts
Print the following parts from the `models/single_camera_config/` directory:

| Component | Quantity | Filename |
|-----------|----------|----------|
| Single Camera Top Arm | 1 | single_camera_top_arm.stl |
| Top (no overhang) | 1 | top_no_overhang.stl |
| Stand Base | 1 | stand_base.stl |
| Extension | 1 | extension.stl |
| Base Support | 1 | base_support.stl |
| Webcam Adapter (optional) | 1 | webcam_adapter.stl |

### Additional Hardware

#### Fasteners
- 4× 20mm × 0.5mm nuts and bolts (to bolt stand base to base support)
- 1× 1/2 inch × 1/2 inch screw (to mount camera)
- 1× 2 inch × 1/2 inch nut and bolt (to mount extension)

#### Camera Equipment
- 1× Camera (DSLR, GoPro, or other camera with at least 10MP resolution)
  - The original creator recommends 4K cameras like GoPro for best results
  - Alternatively, you can use a webcam with the optional webcam adapter

## Assembly Instructions

1. Assemble the common components as described in `config/common_components.md`

2. Attach the stand base to the base support:
   - Use 20mm × 0.5mm nuts and bolts (4 total)

3. Mount the extension:
   - Use a 2 inch × 1/2 inch nut and bolt

4. Attach the camera:
   - Connect the camera to the single camera top arm using a 1/2 inch × 1/2 inch screw
   - If using a webcam instead of a camera, add the optional webcam adapter

## Usage Tips

1. Position the book on the glass surface with the page spread flat
2. Take a photo of the two-page spread
3. Turn the page and repeat
4. For best results, use image processing software to crop, rotate, and clean up the scanned pages
5. Consider using a remote trigger or timer to avoid camera shake

## Advantages of Single Camera Setup

- Requires fewer parts to print
- Simpler assembly process
- More compact design
- Easier to transport
- Works well with most cameras, including webcams and smartphones (with appropriate adapters)

## Troubleshooting

- If the structure feels unstable, check that all bolts are properly tightened
- If the camera is not positioned correctly, adjust the height of the extension arm
- If parts don't fit together well, check your printer's calibration and consider reprinting problematic parts