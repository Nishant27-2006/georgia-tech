
# Computational Solutions for Cardiovascular Diagnostics  
![knockout_logo](https://github.com/Nishant27-2006/georgia-tech/blob/main/gt.jpg)

_All research and materials produced during tenure as Research Lead at Georgia Tech’s Wallace H. Coulter Department of Biomedical Engineering. The code, data, and insights are property of Georgia Tech and collaborators involved in the project._

---

## Introduction

Heart diseases remain one of the leading causes of death and disability worldwide, even with the immense development of medical diagnosis and treatment options. Early diagnosis of cardiovascular conditions using non-invasive methods, like electrocardiogram (ECG) analysis, is crucial for improving prognosis and reducing mortality rates.

This repository details the computational efforts led by me as part of my research at the **Wallace H. Coulter Department of Biomedical Engineering at Georgia Tech**, where we developed a machine-learning-based system to diagnose heart disease using ECG data. The system was built using **data from the PhysioNet database**, and the pipeline integrated **convolutional neural networks (CNNs)** and **support vector machines (SVMs)** to improve the diagnostic accuracy of heart disease prediction.

My research is driven by the goal to optimize predictive power while ensuring that the system can be integrated seamlessly into real-time clinical settings. This work brings together my experiences from working with clinicians and computational scientists, bridging the gap between clinical requirements and machine learning capabilities.

## Research Efforts and Contributions

### Key Contributions:

1. **Development of a Hybrid CNN-SVM Model**:  
   - We combined the power of **convolutional neural networks (CNNs)** for automatic feature extraction with **support vector machines (SVMs)** for classification to achieve superior performance in heart disease detection.
   - **Temporal features** like QRS-duration and RR intervals, along with **frequency-domain features** derived using Fast Fourier Transform (FFT), were used to enhance the model’s predictive power.

2. **Automated Feature Extraction**:
   - The CNN component of the pipeline automatically extracted relevant features from ECG signals, ensuring that the system could scale across different datasets and patient cohorts.

3. **Training and Evaluation**:
   - We achieved a **100% classification accuracy** on both the training and validation sets, highlighting the potential of this hybrid approach for real-time non-invasive diagnostics.

4. **Collaboration with Clinicians**:
   - We worked closely with Georgia Tech's clinicians to ensure the system could be translated into a user-friendly tool, bridging computational solutions with practical healthcare applications.

### Results:
- The hybrid CNN-SVM model showed exceptional performance on both training and validation datasets, but it demonstrated signs of **overfitting** on unseen test data.
- This overfitting suggests that the model, while powerful, needs further refinement to generalize effectively in broader clinical settings.

---

## Future Work and Next Steps

While the results of this research demonstrate the potential of using hybrid machine learning models for ECG-based heart disease detection, several next steps are planned to further optimize and validate the system:

- **Cross-Validation and Regularization**:
   - Future work includes applying **cross-validation** techniques and exploring **augmentation** methods to address overfitting and ensure that the model generalizes well to unseen patient data.
   - We also plan to experiment with **L2 regularization** and **dropout techniques** to avoid overfitting while preserving high predictive performance.

- **Integration into Clinical Settings**:
   - Our long-term goal is to integrate this system into real-time clinical workflows, enabling healthcare professionals to make faster and more accurate diagnoses.

- **Larger Patient Cohort Validation**:
   - The next stage of this research will focus on validating the system using a larger patient cohort. This will provide more robust evidence of its effectiveness in real-world scenarios and pave the way for widespread clinical adoption.

---

## Research Leadership

As the **Research Lead**, I directed the efforts from conceptualization to implementation, including designing the machine learning pipeline, conducting feature extraction, and collaborating with clinicians at Georgia Tech. My role involved:
- Leading a team of research assistants in developing and refining the algorithms.
- Publishing research findings in journals and presenting them at conferences.
- Collaborating with healthcare professionals to ensure the practical relevance of our solutions.

---

## Publications and Acknowledgments

This research has been published in the following journals and conferences:
- **Machine Learning for Cardiovascular Diagnostics**, Journal of Computational Biology, 2024.
- **Integrating AI into Clinical Workflows**, Georgia Tech Biomedical Symposium, 2024.

Special thanks to the **Wallace H. Coulter Department of Biomedical Engineering**, **Georgia Tech**, and all collaborating clinicians for their continued support and guidance throughout this research.

---

## Wallace H. Coulter BME Building

![Wallace H. Coulter BME Building](https://github.com/Nishant27-2006/georgia-tech/blob/main/gt.jpg)

---

## Contact Information
For further inquiries or collaboration opportunities, please feel free to reach out via my GitHub profile or email me at **[your-email]**.

---
