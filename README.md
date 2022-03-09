# mvs-wall
MagicVoxel wall shader.

This shader creates various wall-like structures. It has three modes to create walls, lines, or points. You can adjust the model box X/Y/Z size to limit the respective axis size to create longer, wider, narrower, or taller structures.

## Parameters

### X-axis/Y-axis/Z-axis
Values: 0, 1

Create voxels on the selected axis or on multiple ones. When the value is set to 0, that axis will be ignored.

### Spacing
Values: 0 - 255

Spacing between voxels.

### Thickness
Values: 1 - 255

Adjust the thickness of the generated structure.

### Type
Values: 1 - 3

Type of structure to generate. 1 - walls, 2 - lines, 3 - points.
