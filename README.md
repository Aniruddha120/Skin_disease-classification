# Skin_decease-classification

## introduction
The HAM1000 dataset contains a diverse collection of skin lesion images, each labeled with the corresponding skin disease diagnosis. The dataset consists of various skin disease types, making it a valuable resource for building predictive models.

## Project Objective
The primary objective of this project is to create a deep-learning model capable of accurately classifying skin disease types based on images. By training the model on a subset of the HAM1000 dataset, we aim to achieve a high level of accuracy in predicting skin disease types from new images.

## Project Details
Total Images for Training: 1400
Image Size: 64x64 (larger than the original 32x32 to capture more detail)
Activation Function Used: Softmax
Optimizer: Adam
Results
The accuracy achieved by the model on the test dataset is approximately 64%. While this accuracy is promising, the model's performance can be further improved in future iterations through various strategies such as architectural enhancements, data augmentation, and fine-tuning.

## Getting Started
To get started with this project, follow these steps:
1. Clone the repository to your local machine.
   ```sh
   git clone https://github.com/Aniruddha120/Skin_decease-classification.git
   cd Skin_decease-classification
3. Ensure you have the required dependencies installed

   ```sh
    pip install -r requirements.txt

4. Use the Jupyter Notebook or Python scripts to train and evaluate the skin disease classification model.

## Future Improvements
This project is an ongoing effort, and there are several avenues for improvement:

Fine-tuning: Experiment with different hyperparameters and network architectures to improve accuracy.
Data Augmentation: Apply data augmentation techniques to increase the diversity of the training dataset.
Transfer Learning: Explore the use of pre-trained models (e.g., transfer learning with models like ResNet, Inception, etc.).
Visualization: Create visualization tools to help interpret model predictions and gain insights into the data.
Deployment: Consider deploying the model as a web application or mobile app for practical use in healthcare settings.
Contributions and suggestions for improvements are welcome. Feel free to fork this repository and submit pull requests.

Thank you for your interest in this skin disease classification project!

Thanks!
## References:
Dataset used: https://arxiv.org/abs/1803.10417

Publication: https://paperswithcode.com/dataset/ham10000-1
