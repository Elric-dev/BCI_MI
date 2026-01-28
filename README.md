# Brain-Computer Interface for Motor Imagery Classification

**Master's Thesis**

---

## 📋 Abstract

This repository hosts the complete implementation and documentation of my Master's thesis on Brain-Computer Interface (BCI) systems for Motor Imagery (MI) classification. The research focuses on developing robust machine learning algorithms for decoding motor imagery patterns from electroencephalography (EEG) signals, enabling direct brain-to-computer communication.

Motor imagery-based BCIs have significant applications in assistive technologies, neurorehabilitation, and human-computer interaction. This work investigates state-of-the-art signal processing techniques and deep learning architectures to improve classification accuracy and reliability of MI-based BCI systems.

---

## 🎯 Key Contributions

- **Novel Classification Approach**: Development and evaluation of advanced machine learning models for MI-EEG signal classification
- **Feature Engineering**: Implementation of robust feature extraction techniques including Common Spatial Patterns (CSP), wavelet transforms, and spectral features
- **Deep Learning Integration**: Exploration of convolutional neural networks (CNNs) and recurrent architectures for end-to-end MI classification
- **Real-time Performance**: Optimization strategies for achieving low-latency classification suitable for real-time BCI applications
- **Comprehensive Benchmarking**: Extensive evaluation on public datasets with comparative analysis against state-of-the-art methods

---

## 🔬 Methodology

### Data Acquisition
- **EEG Paradigm**: Motor Imagery (left hand, right hand, feet, tongue)
- **Datasets**: BCI Competition datasets (IV-2a, IV-2b), PhysioNet Motor Imagery Database
- **Signal Processing**: Preprocessing pipeline including filtering, artifact removal, and epoch extraction

### Feature Extraction
- Common Spatial Patterns (CSP)
- Filter Bank CSP (FBCSP)
- Power Spectral Density (PSD)
- Time-frequency representations

### Classification Models
- Support Vector Machines (SVM)
- Linear Discriminant Analysis (LDA)
- Convolutional Neural Networks (CNN)
- Long Short-Term Memory (LSTM) networks
- Hybrid architectures

---

## 📊 Results

Key performance metrics achieved on benchmark datasets:

- **BCI Competition IV-2a**: Classification accuracy of XX.X% (specify your results)
- **BCI Competition IV-2b**: Classification accuracy of XX.X% (specify your results)
- **Cross-subject validation**: Demonstrated generalization capability across multiple subjects
- **Computational efficiency**: Real-time classification with <XXms latency

*(Note: Update with actual results from your thesis)*

---

## 🛠️ Repository Structure

```
BCI_MI/
├── data/                  # Dataset storage and preprocessing scripts
├── src/                   # Source code for BCI pipeline
│   ├── preprocessing/     # Signal preprocessing modules
│   ├── features/          # Feature extraction algorithms
│   ├── models/            # Classification models
│   └── utils/             # Utility functions
├── notebooks/             # Jupyter notebooks for analysis and visualization
├── experiments/           # Experimental configurations and results
├── docs/                  # Documentation and thesis PDF
└── README.md             # This file
```

*(Note: Add directories as you populate the repository with your thesis code)*

---

## 💻 Installation & Usage

### Requirements
```bash
Python >= 3.8
NumPy
SciPy
scikit-learn
MNE-Python (for EEG processing)
TensorFlow/PyTorch (for deep learning models)
matplotlib, seaborn (for visualization)
```

### Setup
```bash
# Clone the repository
git clone https://github.com/Elric-dev/BCI_MI.git
cd BCI_MI

# Install dependencies
pip install -r requirements.txt

# Run preprocessing
python src/preprocessing/preprocess.py --config configs/default.yaml

# Train model
python src/train.py --model cnn --dataset bcic_iv_2a

# Evaluate
python src/evaluate.py --model_path models/best_model.pth
```

*(Note: Update commands based on your actual implementation)*

---

## 📚 Publications & Citations

If you use this work in your research, please cite:

```bibtex
@mastersthesis{yourname2026bci,
  title={Brain-Computer Interface for Motor Imagery Classification},
  author={Your Name},
  year={2026},
  school={Your University},
  type={Master's Thesis}
}
```

**Related Publications:**
- [Add any conference papers or journal articles related to this work]

---

## 🔗 Related Resources

- [BCI Competition](http://www.bbci.de/competition/)
- [MNE-Python Documentation](https://mne.tools/)
- [PhysioNet Motor Imagery Database](https://physionet.org/content/eegmmidb/)

---

## 📄 Thesis Document

The complete thesis document (PDF) is available [here](docs/thesis.pdf) *(upload your thesis PDF to the repository)*.

**Thesis Committee:**
- Supervisor: [Name], [Institution]
- Co-supervisor: [Name], [Institution]
- Examiner: [Name], [Institution]

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**[Your Name]**
- 🎓 Master's degree in [Your Field], [Your University]
- 📧 Email: [your.email@domain.com]
- 🔗 LinkedIn: [Your LinkedIn Profile]
- 🐙 GitHub: [@Elric-dev](https://github.com/Elric-dev)

---

## 🙏 Acknowledgments

I would like to thank my thesis supervisor [Name] for their guidance and support throughout this research. Special thanks to [Research Group/Lab Name] for providing computational resources and valuable feedback. This work was supported by [Funding Source, if applicable].

---

## 📧 Contact

For questions, collaborations, or further information about this research, please feel free to reach out:
- Open an issue in this repository
- Email: [your.email@domain.com]

---

*Last updated: January 2026*
