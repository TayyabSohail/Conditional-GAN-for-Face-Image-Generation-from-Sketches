# Conditional-GAN-for-Face-Image-Generation-from-Sketches

## Research Paper 
[Tayyab_question_3_report.pdf](https://github.com/user-attachments/files/17557218/Tayyab_question_3_report.pdf)


# Project Overview
This project implements a Conditional Generative Adversarial Network (cGAN) using the Person Face Sketches dataset, with the goal of generating realistic face images conditioned on input sketches. The model learns the mapping between a sketch and its corresponding real face during training, allowing it to generate realistic faces from any provided sketch once trained. The architecture adheres closely to the original cGAN structure to ensure high-quality, visually realistic outputs that match the input sketches.

# Tools and Technologies Used

Programming Language: Python

# Libraries:

TensorFlow/Keras: For constructing and training the cGAN model

NumPy: For handling data manipulation and matrix operations

OpenCV/PIL: For preprocessing and transforming images

Dataset: Person Face Sketches

# Techniques:

Conditional GAN (cGAN) for generating face images from sketches

Sketch-to-image mapping through adversarial training

Architecture implementation based on the original cGAN paper

# Setup and Installation
## Clone the repository:

git clone https://github.com/your-username/cgan-face-generation-from-sketches.git

cd cgan-face-generation-from-sketches


## Install the required dependencies:

pip install -r requirements.txt

Download the Person Face Sketches dataset and place it in the appropriate directory for training.

## How to Run

Train the Conditional GAN model:

python train.py

Test the model with a user-provided sketch:

python test.py --input_sketch <path_to_sketch_image>

The model will output a realistic face image based on the provided sketch.
![WhatsApp Image 2024-10-21 at 9 53 00 PM](https://github.com/user-attachments/assets/384ac356-b903-485b-a187-9b07ea8a0244)
![Screenshot 2024-10-20 194510](https://github.com/user-attachments/assets/32c91089-5d26-43ba-a9d2-a2058345c064)
![Screenshot 2024-10-20 194430](https://github.com/user-attachments/assets/e9d57cf6-beb8-4ba5-8f54-4494f2946121)
![WhatsApp Image 2024-10-21 at 9 53 04 PM](https://github.com/user-attachments/assets/04c16c13-bb92-4e05-8fdb-c12c4fdfb137)
![WhatsApp Image 2024-10-21 at 9 53 02 PM](https://github.com/user-attachments/assets/dc0874d7-b96a-407a-8818-30cf8960df31)



Results
After training, the cGAN model is capable of generating highly realistic face images from input sketches, demonstrating effective sketch-to-image translation based on the conditioning input.
