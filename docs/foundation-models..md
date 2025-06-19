# Foundation Models for Annotation

## Segment Anything Model (SAM)
The SAM model from Meta AI is a prompt-based segmentation tool achieving strong zero-shot performance across domains, including medical imaging. In CUBE.AI, it has been optimized to work directly with NumPy arrays and TensorFlow tensors, skipping DICOM-to-JPEG conversion. Feature embeddings are cached to reduce redundancy, and slice-wise segmentation is enhanced by adding boundary constraints via orthogonal 2D masks.

Performance: 2D slice time reduced from 3 minutes to 30 seconds, and 3D volume time from 15 minutes to 40 seconds (best case).

## Vista3D
Vista3D supports automatic and interactive segmentation of high-resolution 3D scans. It enables radiologists to segment 127 anatomical structures and refine them via 3D point prompts. Its low-memory binary segmentation strategy allows for real-time, high-quality results.

## nnInteractive
nnInteractive is optimized for standard GPUs and supports interactive segmentation via lasso, scribbles, or clicks. It supports multiple modalities and delivers low-latency, high-quality segmentations. It bridges the gap for clinics with limited computational resources.

CUBE.AI integrates SAM, Vista3D, and nnInteractive, allowing radiologists to choose based on their environment and task needs.