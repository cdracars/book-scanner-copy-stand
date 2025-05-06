# Two Camera Setup Configuration

This guide will help you build the two-camera version of the book scanner copy stand. This configuration allows for faster scanning of books by capturing both left and right pages simultaneously.

## Required Components

### Common Components
First, ensure you have all the common components assembled as described in `config/common_components.md`:
- Book stand frame (right and left book stand parts)
- Glass frame with picture frame glass

### Additional 3D Printed Parts

Print the following parts from the `models/two_camera_config/` directory:

| Component | Quantity | Filename |
|-----------|----------|----------|
| Connecting Bars | 4 | connecting_bar.stl |
| Extensions | 2 | extension.stl |
| Top (no overhang) | 2 | top_no_overhang.stl |
| T Connectors | 2 | t_connector.stl |
| Two Camera Top Arm | 2 | two_camera_top_arm.stl |
| Camera Base Foot | 4 | camera_base_foot.stl |
| Adjustable Base Support | 2 | adjustable_base_support.stl |
| Stand Base | 2 | stand_base.stl |

### Additional Hardware

#### Fasteners
- 8× 20mm × 0.5mm screws and bolts (for connecting bars, adjustable base to stand base)
- 2× 2 inch × 1/2 inch nuts and bolts (to connect tops to extensions)
- 2× 1/2 inch × 1/2 inch nuts and washers (to connect cameras to top arms)

#### Camera Equipment
- 2× Cameras (DSLR, GoPro, or other camera with at least 10MP resolution)
  - The original creator recommends 4K cameras like GoPro for best results

## Assembly Instructions

1. Assemble the common components as described in `config/common_components.md`

2. Attach the connecting bars:
   - Use 20mm × 0.5mm screws and bolts (8 total) to connect the bars and adjustable base to stand base

3. Assemble the camera mount:
   - Connect the tops to extensions using 2 inch × 1/2 inch nuts and bolts (2 total)
   - Attach cameras to the top arms using 1/2 inch × 1/2 inch nuts and washers (2 total)

## Usage Tips

1. Position the cameras to capture both pages simultaneously
2. Ensure consistent lighting on both pages to get even exposure
3. Consider using a remote trigger or timer to avoid camera shake
4. For best results, use image processing software to crop and clean up the scanned pages

## Advantages of Two-Camera Setup

- Faster scanning process (two pages captured simultaneously)
- Better for high-volume book digitization
- More stable structure for heavy cameras
- Ideal for lengthy digitization projects

## Troubleshooting

- If the structure feels unstable, check that all bolts are properly tightened
- If the cameras are not level, adjust the position of the camera mount arms
- If parts don't fit together well, check your printer's calibration and consider reprinting problematic parts