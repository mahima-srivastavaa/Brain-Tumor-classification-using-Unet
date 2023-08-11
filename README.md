# Brain-Tumor-classification-using-Unet
The dataset consists of 484 MR image samples, each with a size of (240, 240, 155) for images and labels, and includes four sequences per image.
The data preprocessing involves generating randomly sampled sub-volumes, ensuring inclusion of tumor data, and standardizing pixel values for input to the model.
The 3D U-Net model used for brain tumor classification demonstrated a strong performance with an F1 score of approximately 0.93.


The project embarked on a comprehensive exploration of utilizing advanced deep learning techniques for accurate brain tumor classification and segmentation from MRI scans. The following key steps were undertaken:

Data Collection: Acquired a diverse dataset of brain MRI scans with tumor annotations.
Data Preprocessing: Performed skull stripping and bias correction, along with resizing and data augmentation.
Model Selection: Opted for the state-of-the-art 3D U-Net architecture, known for its excellence in medical image segmentation tasks.
Model Adaptation: Fine-tuned the 3D U-Net with custom modifications to suit the specific tumor classification and segmentation tasks.
Training: Conducted extensive training of the model on the preprocessed data, encompassing the augmentation of data and validation for optimal results.
Evaluation: Employed established metrics such as F1 score, to gauge the model's performance with respect to tumor classification.
Post-processing: Implemented post-processing techniques for further refining of segmentation masks.
Deployment Potential: Explored the integration of the trained model into the clinical workflow, demonstrating its potential to assist radiologists in making accurate diagnoses.
