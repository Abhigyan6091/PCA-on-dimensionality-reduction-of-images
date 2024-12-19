Motive:
Here we have applied Principal Component Analysis to observe the impact on dimensionality reduction of Image reconstruction.

Process Overview:
1. Data Extraction: Unzipped the Faces94 dataset and loaded images from specific subdirectories.
2. Preprocessing:
   Converted images to grayscale.
   Resized images to 200x180 pixels.
3. Flattened each image to a 1D array and normalized pixel values.
4. PCA Application: Reduced dimensionality using PCA with 1, 10, 15, and 20 components.
5. Image Reconstruction: Reconstructed images from reduced components to observe quality degradation.

Observation:
1 component: Barely recognizable, only basic contours.
10 components: General facial structure visible, still blurry.
15 components: Clearer, with most facial features discernible.
20 components: Close to original, minimal detail loss.


