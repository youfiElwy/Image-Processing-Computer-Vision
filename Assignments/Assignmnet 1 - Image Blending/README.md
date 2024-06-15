# Computer Vision and Image Processing Lab Assignment 1

## Title: Image Compositing Using Alpha Blending

### Task Description:
In this lab assignment, you will work on creating a composite image by segmenting a photo of yourself and combining it with a different background using alpha blending techniques.

### Tools and Technologies:
- **Python programming language**
- **OpenCV library**

### Instructions:

1. **Capture Your Photo:**
   - Take a photo of yourself against a plain background using a camera or smartphone.
   - Ensure good lighting and clear visibility of your face.

2. **Create an Alpha Mask:**
   - Use image segmentation techniques to separate yourself from the background.
   - Understand how to load an image, apply segmentation, and create an alpha mask.

3. **Blur the Boundaries of the Masks:**
   - Apply image filtering techniques such as Weighted Average Filter and Gaussian Filter.
   - Explore kernel sizes of 3x3 and 5x5 for each filter.

4. **Use Alpha Blending for Image Composition:**
   - Combine your segmented image with a new background using alpha blending.
   - Implement point operations to ensure a seamless integration.

### Implementation:
- Write Python code to:
  - Load your photo and apply thresholding techniques for segmentation.
  - Select a suitable background image for compositing.
  - Implement image processing techniques to achieve realistic blending.

### Testing and Evaluation:
- Test your code with different background images to ensure robustness.
- Verify that segmentation accurately separates you from the background.
- Evaluate the realism of the composite image after blending.


---
