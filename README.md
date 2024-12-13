# Ensemble Classification of Skin Cancer Using Pre-trained Deep Learning Models: AlexNet and VGG16

This analysis addresses skin cancer classification by leveraging an ensemble of deep learning models, specifically AlexNet and VGG16, known for their feature extraction capabilities. The ensemble demonstrated superior accuracy and predictive capabilities, significantly outperforming individual models and the baseline results. Evaluation metrics such as accuracy, F1, recall, precision, and AUC indicated notable improvements, with the ensemble achieving an precision of 0.90 and an AUC of 0.77. These findings suggest that ensemble methods can effectively enhance classification accuracy in skin cancer detection.

**See attached in the repo the full report**

**Discussion and Conclusion**

The experimental results demonstrate that the ensemble model outperformed the individual AlexNet and VGG16 models in terms of precision and AUC. The ensemble model achieved a higher AUC (0.77) compared to AlexNet (0.76) and VGG16 (0.75), indicating better overall performance. The confusion matrices also show that the ensemble model had fewer false negatives and false positives compared to the individual models, making it more reliable for skin cancer classification.

This research demonstrated that fine-tuning pre-trained models with data augmentation and combining their predictions through ensemble methods can significantly enhance the performance of skin cancer classification tasks. The ensemble model, in particular, showed promising results, outperforming individual models and providing a balanced performance across various metrics.

The report highlights the promise of utilizing pre-trained models and ensemble techniques in medical image classification tasks, ultimately leading to more precise and dependable diagnostic tools

**Key Findings**

**Ensemble Model Superiority:** The ensemble of AlexNet and VGG16 achieved the highest AUC and overall better performance metrics compared to individual models.

**Model Robustness:** Data augmentation techniques improved the robustness and generalization capability of the models.

**Computational Efficiency:** AlexNet provided a good balance between complexity and performance, suitable for environments with moderate computational resources, whereas VGG16, though more complex, delivered superior individual model performance.

**Future Work**

In respect of this research, the availability of computational resources significantly impacted this project. To address this challenge, allocating additional computational power would allow for testing more advanced models. Specifically, exploring efficient architectures like ResNet, GoogLeNet, and other state-of-the-art models could enhance skin cancer detection accuracy. Additionally, incorporating thses state-of-the-art models into ensemble methods—such as weighted averaging or model stacking—would further improve classification performance.

The quality and diversity of training and testing data significantly impact model generalization. Utilizing larger and more diverse skin cancer datasets would enhance the model’s ability to handle variations in skin lesions. Collecting data from different populations, skin types, and clinical scenarios would contribute to robustness.
