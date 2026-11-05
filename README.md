# CardioSAM-Mem

**Reliability-Guided Temporal Memory for SAM2-Based Echocardiography Video Segmentation**

CardioSAM-Mem is a deep learning framework for left ventricular segmentation in echocardiography videos. It integrates SAM2 with reliability-guided temporal memory, anatomical topology constraints, and temporal consistency learning to improve segmentation robustness across cardiac motion sequences.

### Experimental Datasets

- **CAMUS:** Cardiac ultrasound segmentation using four-chamber echocardiographic sequences.
- **EchoNet-Dynamic:** Echocardiography video segmentation using left ventricular tracing annotations.

### Key Components

- SAM2-based video segmentation
- Reliability-guided memory modeling
- Anatomical topology constraints
- Temporal consistency and anatomy-aware loss
- Dataset-specific training and evaluation
