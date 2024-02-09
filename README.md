# CycleGAN Project Guidelines
![TensorFlow Badge](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras Badge](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white)
![Matplotlib Badge](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![tqdm Badge](https://img.shields.io/badge/tqdm-3178C6?style=for-the-badge&logo=python&logoColor=white)
![RandomNormal Initializer](https://img.shields.io/badge/RandomNormal-Initializer-blue?style=for-the-badge "RandomNormal Initializer")
![ImageDataGenerator](https://img.shields.io/badge/ImageDataGenerator-Preprocessing-blue?style=for-the-badge "ImageDataGenerator")

<p align="center">
  <img src="https://github.com/nirmolcho.png?size=100" width="100" style="border-radius: 50%;" alt="Contributor 1">
  <img src="https://github.com/royzohar2.png?size=100" width="100" style="border-radius: 50%;" alt="Contributor 2">
  <img src="https://github.com/Seanlavi.png?size=100" width="100" style="border-radius: 50%;" alt="Contributor 3">
  <img src="https://github.com/Yair7799.png?size=100" width="100" style="border-radius: 50%;" alt="Contributor 3">

</p>



## Overview
This project focuses on implementing a Cycle-GAN using Python and the TensorFlow Keras platform. It challenges you to explore deep learning (DL) concepts by developing and training models from scratch, emphasizing the practical application of the theories and techniques learned in the course. 

## Requirements
1. **Python dependensis:** pip install -r requirements.txt
1. **Platform:** Utilize Python and TensorFlow Keras for all implementations.
2. **Submission:** Alongside your Kaggle competition submission, provide two Google Colab notebooks: one for the training phase and another for the testing environment. The training notebook must document various experiments conducted during the development process.
3. **Implementation:** Your task is to implement a Cycle-GAN architecture. Within this architecture, one discriminator must be a Patch-GAN with a receptive field size different from 70x70. The architecture submitted to the Kaggle competition will represent your best model.
4. **Image Size:** For academic purposes, generate images of 320x320 pixels. Adjust the image size to 256x256 pixels for Kaggle submissions using the `imresize()` function.
5. **Restrictions:** The use of pre-trained models, transfer learning methods, or external metadata is prohibited. Focus on creating and training your models to demonstrate your understanding of DL principles.
6. **Learning Compliance:** Do not employ architectures not covered in the course.
7. **Experiments:** Your training notebook should illustrate and compare different approaches, including variations in hyperparameters and architectures. Include graphs to visualize these comparisons and use text cells to explain your experiments and the insights gained.
8. **Documentation:** For each experiment and architecture, display the model's output images during training, along with convergence graphs showing loss over epochs. Detail the network architecture, chosen hyperparameters, methodologies, and rationale in text cells.
9. **Testing Notebook:** Create a testing environment that loads the trained model to process a 256x256 input image and output a 320x320 generated image. Provide a link to your best model weights and architecture.
10. **Code Execution:** Ensure all code outputs are visible within the notebook.
11. **Code Submission:** Submit your work as Google Colab notebooks to facilitate easy execution by the course team.
12. **Code Quality:** Write clean, well-organized code. Use separate code and text cells extensively for clarity.
13. **Final Submission:** Do not modify your notebooks after the final submission date. Any modifications post-deadline will lead to disqualification.

## Academic Integrity
- **Citations:** Clearly cite any external code or ideas used. Failing to credit sources constitutes academic dishonesty and will be treated as such.
- **Originality:** You must not copy code from others. Sharing or copying code is against the honor code and will result in disciplinary action.
- **Attribution:** If your code builds upon existing work, you must provide proper attribution and clarify your contributions.

## Submission Instructions
- Evaluate both the strengths and weaknesses of your approach.
- Include all relevant outputs in your notebooks.
- Submit an explainer file with instructions for operating your notebook and any other necessary details.
- Share your notebook via Google Drive, accessible to anyone with the link.

Adhering to these guidelines will ensure a thorough understanding of DL concepts and their practical application, demonstrating your ability to develop complex models from scratch.



