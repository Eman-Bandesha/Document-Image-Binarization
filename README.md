

# Document Image Binarization Evaluation with Otsu, Sauvola, and Adaptive Gaussian Filtering

This repository contains code for document image binarization with the implementation of Otsu, Sauvola, and Adaptive Gaussian Filtering algorithms. The evaluation metrics used for assessing the performance include Peak Signal-to-Noise Ratio (PSNR), Dynamic Range Decrease (DRD), Intersection over Union (IOU), and Structural Similarity Index (SSIM).

## Dataset
The code is applied and evaluated on the DIBCO 2016 dataset, which can be accessed [here](https://vc.ee.duth.gr/h-dibco2016/). The DIBCO (Document Image Binarization Contest) dataset is widely used for evaluating document image binarization algorithms.

## Code Description
- **Otsu Binarization:** Otsu's method is a simple thresholding technique to perform global image binarization.
- **Sauvola Binarization:** Sauvola's method is an adaptive thresholding technique that computes local thresholds for each pixel.
- **Adaptive Gaussian Filtering:** This technique applies Gaussian filtering to the image before binarization, enhancing its robustness.

## Evaluation Metrics
1. **Peak Signal-to-Noise Ratio (PSNR):** Measures the quality of the reconstructed image compared to the original, indicating the level of noise introduced during binarization.
2. **Dynamic Range Decrease (DRD):** Evaluates the reduction in dynamic range caused by the binarization process.
3. **Intersection over Union (IOU):** Computes the overlap between the binarized image and the ground truth, providing a measure of segmentation accuracy.
4. **Structural Similarity Index (SSIM):** Assesses the similarity between the binarized image and the ground truth in terms of luminance, contrast, and structure.

## Usage
1. **Data Preparation:** Download the DIBCO 2016 dataset from the provided link and organize it according to the directory structure specified in the code.
2. **Algorithm Implementation:** Implement Otsu, Sauvola, and Adaptive Gaussian Filtering algorithms on the dataset.
3. **Evaluation:** Calculate PSNR, DRD, IOU, and SSIM metrics for each algorithm.
4. **Analysis:** Analyze the performance of each algorithm based on the evaluation metrics.


## Contributors
- [Eman Azam](https://github.com/Eman-Bandesha)

