# Camera Transformations: Intrinsic and Extrinsic Parameters

This Jupyter notebook provides a practical guide to understanding and implementing camera transformations in computer vision, with a focus on the intrinsic and extrinsic parameters of a camera. The notebook includes examples of how to compute and apply transformation matrices to move between world and camera coordinate systems.

## Notebook Overview

The notebook covers the following topics:

### 1. **Extrinsic Matrix**
   - Explains the role of the extrinsic matrix in transforming points from world coordinates to camera coordinates.
   - Provides a link to further reading on the topic.
   - Discusses the interpretation of translation vectors and rotation matrices for transforming coordinate systems.

### 2. **Coordinate Transformations**
   - **Translation Only**: Demonstrates how to transform points between the world and camera coordinate systems with only translation (no rotation).
   - **Translation and Rotation**: Introduces rotation matrices and shows how to apply both translation and rotation to transform points.

### 3. **Ray Direction from Camera to Image Plane**
   - Explains how to compute the direction of a ray from the optical center of a camera to a specific point on the image plane, using the camera’s intrinsic parameters.
   - Demonstrates how to compute the camera coordinates of a point along this ray at a given distance from the optical center.

### 4. **Practical Examples**
   - The notebook includes practical code examples that compute the translation vectors, rotation matrices, and transformations between different coordinate systems, helping you visualize the process.

## Dependencies

The notebook requires the following Python libraries:
- `numpy`

To install the required libraries, run:
```bash
pip install numpy
