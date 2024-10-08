# AI Personalized Avatars

This project harnesses the power of artificial intelligence to generate unique, personalized avatars based on a set of training images. The model used in this project is a variant of the Stable Diffusion model, known for its exceptional capabilities in image generation tasks.

## Sample Images


Here are some example input training images and corresponding output images generated by the AI model:

<img src="https://github.com/NisaarAgharia/AI-Personalized-Avatars/assets/22457544/1c10b986-d605-4ad9-85f7-8f620e700bd6" width="50%" />
<img src="https://github.com/NisaarAgharia/AI-Personalized-Avatars/assets/22457544/7d2d73a1-9f3e-418f-ab54-62b789b34d90" width="50%" /> 
<img src="https://github.com/NisaarAgharia/AI-Personalized-Avatars/assets/22457544/cc42fc71-ea05-4189-9f69-ecdafdbd2a54" width="50%" /> 

**Generated Avatars:**

<p align="center">
  <b>Avatar 1 - Style: Historic and Gaming Character</b><br>
  <img src="https://github.com/NisaarAgharia/AI-Personalized-Avatars/assets/22457544/1c10b986-d605-4ad9-85f7-8f620e700bd6" width="45%" />
  <img src="https://github.com/NisaarAgharia/AI-Personalized-Avatars/assets/22457544/02a680e4-6d5c-4fc3-944c-15dd392a7bfa" width="45%" /> 
  <br><br>
  <b>Avatar 2 - Style: Abstract Art</b><br>
  <img src="https://github.com/NisaarAgharia/AI-Personalized-Avatars/assets/22457544/52da37d9-1b5b-4481-aa2e-11c9198219b7" width="45%" />
  <img src="https://github.com/NisaarAgharia/AI-Personalized-Avatars/assets/22457544/21cca9d8-cc38-4d8f-af9d-7263b0782d0e" width="45%" /> 
  <br><br>
  <b>Avatar 3 - Style: Comic and Cyberpunk</b><br>
  <img src="https://github.com/NisaarAgharia/AI-Personalized-Avatars/assets/22457544/54c6f312-3440-43f0-88a9-73644b3b8fab" width="45%" />
  <img src="https://github.com/NisaarAgharia/AI-Personalized-Avatars/assets/22457544/f629ddf1-5e82-4339-89a3-1292b1b47716" width="45%" /> 
</p>


## Repository Contents

This repository contains:

1. **Google Colab Notebook:** A pre-configured Google Colab notebook for training your model. The notebook includes steps for setting up the environment, loading the necessary pre-trained models, uploading training images, training the model, and saving the model checkpoints.

2. **Regularization Images:** A set of regularization images used for stabilizing the training process. You can add more images or replace these images as per your requirements.

3. **Training Images Directory:** A dedicated directory to upload your training images. The images you upload will be used to personalize the AI model, and should be representative of the avatars you wish to generate.

4. **Trained Models:** The final trained model checkpoints saved in a directory named "trained_models".

## How to Use

Follow these steps to create your own AI personalized avatars:

1. **Clone or Download this Repository:** You can clone this repository to your local machine or simply download it.

2. **Setup the Environment:** Install the necessary Python packages which are listed in the Google Colab notebook.

3. **Download the Pre-trained Model:** The Google Colab notebook contains steps to download a pre-trained model from Hugging Face. This pre-trained model serves as a starting point for training your personalized avatar model.

4. **Upload Training Images:** You can upload your own set of training images in the "training_images" directory. These images will be used to fine-tune the pre-trained model. Ensure the images are representative of the avatars you wish the AI to generate.

5. **Train the Model:** Run the training script in the Google Colab notebook. This script fine-tunes the pre-trained model on your training images.

6. **Save and Use the Trained Model:** After training, the resulting model checkpoint is saved in the "trained_models" directory. You can now use this model checkpoint to generate your own personalized avatars.
