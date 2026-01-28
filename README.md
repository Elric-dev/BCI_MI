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

- **BCI Competition IV-2b**: Classification accuracy using Cohen's Kappa
- FBCSP MutualInfo LDA CV :            kappa: 0.6481 & std: 0.1651
- FBCSP noFeatureSelection LinSVM CV:  kappa: 0.6361 & std: 0.1533
- FBCSP CNN LSTM CV:                   kappa: 0.6101 & std: 0.16
- FT EEG MIG CNN CV:                   kappa: 0.5403 & std: 0.1451


---

## 📚 Publications & Citations

If you use this work in your research, please cite:

```bibtex
@mastersthesis{Mafla2026bci,
  title={Benchmarking Brain-Computer Interface for Motor Imagery,
  author={Mafla, Gustavo},
  year={2025},
  school={Università Degli Studi di Milano},
  type={Master's Thesis}
}
```
---

## 🔗 Related Resources

- [BCI Competition](http://www.bbci.de/competition/)
- [MNE-Python Documentation](https://mne.tools/)
- [PhysioNet Motor Imagery Database](https://physionet.org/content/eegmmidb/)

---

## 📄 Thesis Document

The complete thesis document (PDF) is available [here](docs/thesis.pdf) *(upload your thesis PDF to the repository)*.

**Thesis Committee:**
- Supervisor: Giuseppe Boccignone, University of Milan
- Co-supervisor: Raffaella Lanzarotti, University of Milan

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Gustavo Mafla Roca**
- 🎓 Master's degree in Human Centered Artificial Intelligence, University of Milan
- 📧 Email: [gmaflarocal@gmail.com]
- 🔗 LinkedIn: [https://www.linkedin.com/in/gustavo-mafla/]
- 🐙 GitHub: [@Elric-dev](https://github.com/Elric-dev)

---

## 🙏 Acknowledgments

I would like to thank my thesis supervisor Prof. Giuseppe Boccignone for his guidance and support throughout this research. Special thanks to PHUSE LAB Unimi for providing computational resources and valuable feedback. 

---

## 📧 Contact

For questions, collaborations, or further information about this research, please feel free to reach out:
- Open an issue in this repository
- Email me

---

*Last updated: January 2026*
