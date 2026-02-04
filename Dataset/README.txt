Synthetic Dental X-ray Dataset (for development/testing)
----------------------------------------------------------------
This dataset is synthetic and intended ONLY for developing and debugging
computer-vision pipelines (training, model testing, augmentation). These images
are NOT real medical X-rays and must NOT be used for clinical or diagnostic purposes.

Structure:
- train/normal, train/cavity
- val/normal, val/cavity
- test/normal, test/cavity

labels.csv - CSV with columns (relative_path,label) where label: 0=normal, 1=cavity

Total images per class: 240
Train/Val/Test split: 70%/15%/15%

Generated with a simple procedural image generator (PIL). Use this dataset to:
- verify preprocessing pipelines
- prototype architectures and training loops
- test data augmentation & training code

If you need a dataset with real dental X-rays, I can help with download scripts and troubleshooting
(for Kaggle, IEEE Dataport, GitHub) — but I cannot fetch them in this session.

