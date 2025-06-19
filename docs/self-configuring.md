# Self-Configuring Models

CUBE.AI uses a self-configuring framework inspired by nnU-Net to automate the full model training process. It creates a fingerprint of each dataset—capturing size, voxel spacing, label distribution—and configures preprocessing, network architecture, training, augmentation, and post-processing.

After assisted annotation using foundational models, the system automatically preprocesses data, builds models, trains them, and validates results for deployment—all without human intervention.