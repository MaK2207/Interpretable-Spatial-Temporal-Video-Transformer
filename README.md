# Interpretable Spatial-Temporal Video Transformer (ISTVT)

## Overview

This repository contains the implementation of the **Interpretable Spatial-Temporal Video Transformer (ISTVT)**, a deep learning model designed for interpretable deepfake detection using transformers. The model leverages spatial and temporal information from video frames to detect manipulated videos while providing interpretability.

## Project Structure

```
├── README.md                                          # This file
├── ISTVT_IEEE_Format.docx                            # Research paper in IEEE format
├── ISTVT Interpretable Spatial-Temporal Deepfake Detection.pptx  # Presentation slides
├── 5.pdf                                             # Reference document/paper
└── ISTVT_Deepfake_Detection.ipynb                   # Main implementation notebook
```

## Key Features

- **Spatial-Temporal Analysis**: Captures both spatial patterns within frames and temporal dynamics across frames
- **Transformer Architecture**: Utilizes attention mechanisms for interpretability
- **Deepfake Detection**: Trained to identify and classify manipulated videos
- **Interpretability**: Provides insights into model decisions through attention visualization

## Files Description

### Core Implementation
- **ISTVT_Deepfake_Detection.ipynb** - Main Jupyter notebook containing:
  - Data loading and preprocessing
  - Model architecture definition
  - Training pipeline
  - Evaluation metrics
  - Visualization and interpretability analysis

### Documentation
- **ISTVT_IEEE_Format.docx** - Full research paper detailing:
  - Literature review
  - Methodology
  - Experimental results
  - Performance comparisons
  
- **ISTVT Interpretable Spatial-Temporal Deepfake Detection.pptx** - Presentation slides with:
  - Project overview
  - Key findings
  - Visual results

- **5.pdf** - Reference materials and supplementary information

## Requirements

The implementation uses standard Python deep learning libraries:
- PyTorch
- TensorFlow/Keras
- NumPy
- Pandas
- OpenCV
- Scikit-learn
- Matplotlib/Seaborn

## Usage

1. **Setup**: Install required dependencies (see Requirements)
2. **Data Preparation**: Prepare your video dataset
3. **Training**: Run the notebook cells sequentially to:
   - Load and preprocess data
   - Initialize the ISTVT model
   - Train on your dataset
   - Evaluate performance
4. **Inference**: Use trained model for deepfake detection on new videos

## Model Architecture

The ISTVT model combines:
- **Spatial Transformer**: Processes spatial features within individual frames
- **Temporal Transformer**: Captures temporal dynamics across frames
- **Attention Heads**: Multiple attention heads provide interpretability
- **Classification Head**: Binary classification (Real/Fake)

## Results & Performance

[Add your performance metrics, accuracy scores, and comparison with other methods]

## Contributing

This is an academic project. For contributions or questions, please reach out to the repository owner.

## Citation

If you use this project in your research, please cite:

```bibtex
@article{ISTVT2024,
  title={Interpretable Spatial-Temporal Video Transformer for Deepfake Detection},
  author={[Author Names]},
  journal={IEEE Format},
  year={2024}
}
```

## License

[Add appropriate license information]

## Acknowledgments

- References and inspirations are detailed in the research paper (ISTVT_IEEE_Format.docx)
- Built with PyTorch and modern deep learning best practices

---

For more details, refer to the research paper and presentation included in this repository.
