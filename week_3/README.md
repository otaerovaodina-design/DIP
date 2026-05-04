# LAB3 - Geometric Image Transformations

## Overview
Learning various geometric transformations applied to images using OpenCV's affine transformation functions.

## Topics Covered
- **Translation** - Shifting images using transformation matrix (`warpAffine`)
- **Rotation** - Rotating images around center point (`getRotationMatrix2D`)
- **Scaling** - Resizing images with scale factors
- **Shearing** - Applying shear transformation along x-axis

## Key Functions
- `cv2.warpAffine()` - Apply affine transformations
- `cv2.getRotationMatrix2D()` - Create rotation/scaling matrix
- `np.float32()` - Define transformation matrices

## Image Properties
- Original image: 1800x1440 pixels, 3 channels (RGB)

## Files
- `main.ipynb` - Jupyter notebook with all exercises
- `nature.jpg` - Sample image used for transformations
