# outlier-drift-time-test

This notebook plots the time it takes to detect outliers and drift with respect to different inference batch sizes.

Note: `outlier_detector_64` exceeds the GitHub file size limit of 100MB. To run the Jupyter notebook, you can download the model here: https://drive.google.com/drive/folders/1G6DyF50S3DGD1w4RWtY_IXfcn4DXofha?usp=sharing

This notebook utilizes models that were trained in a separate repository. Here’s some information about how the auto-encoders were trained: `outlier_detector_32` was trained on 10,000 32x32x3 GTSRB images using 75 epochs. `outlier_detector_64` was trained on 10,000 64x64x3 GTSRB images using 30 epochs. Both models were trained in 25 minutes. However, note that outlier detection performance will increase with more training time. Lastly, `drift_detector_32` was initialized with 10,000 GTSRB images.
