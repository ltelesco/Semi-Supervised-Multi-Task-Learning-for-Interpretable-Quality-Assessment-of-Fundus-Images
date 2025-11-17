# Semi-Supervised Multi-Task Learning for Interpretable Quality Assessment of Fundus Images

This repository contains the image quality labels for **EyeQ-D**, a subset of the [Kaggle-EyePACS](https://www.kaggle.com/c/diabetic-retinopathy-detection) dataset, as presented in the paper "Semi-supervised multi-task learning for interpretable quality assessment of fundus images".

## Dataset Description - EyeQ-D

The `data/EyeQ-D-Quality-Details.csv` file contains quality labels for fundus images, assessing capture conditions and overall quality.

### CSV Format

The CSV file has the following columns:

*   `file_name`: The original image name from the Kaggle-EyePACS dataset.
*   `overall_quality`: The overall image quality, graded on three levels:
    *   `0`: Reject
    *   `1`: Usable
    *   `2`: Good
*   `illumination`: A binary label for illumination.
    *   `0`: Bad
    *   `1`: Good
*   `clarity`: A binary label for sharpness/clarity.
    *   `0`: Bad
    *   `1`: Good
*   `contrast`: A binary label for contrast.
    *   `0`: Bad
    *   `1`: Good

## Citation

If you use this dataset in your research, please cite our paper:

```
L. Telesco, et al., "Semi-supervised multi-task learning for interpretable quality assessment of fundus images", Biomedical Signal Processing and Control, 2025.
DOI: https://doi.org/10.1016/j.bspc.2025.109167
```
