# Medical Image Gen
An AI-powered web application that generates realistic images of skin rashes from textual descriptions, empowering healthcare professionals to enhance patient education and communication. Integrated Streamlit for the intuitive user interface design.

## UI
<img width="400" alt="Screenshot 2024-08-12 at 3 45 41 PM" src="https://github.com/user-attachments/assets/e06e8ca3-d2c2-44c2-8f37-3c16d732cea4">


## Tech Stack

- **Frontend**: 
  - [Streamlit](https://streamlit.io/) - A framework for creating interactive web applications.
- **Backend**:
  - [PyTorch](https://pytorch.org/) - An open-source machine learning library used for model training and inference.
  - [Diffusers](https://huggingface.co/docs/diffusers) - A library for diffusion models, used for generating images.
- **Models**:
  - [Latent Diffusion Model](https://huggingface.co/CompVis/stable-diffusion-v1-4) - A generative model for producing high-quality images.
  - [CLIP](https://github.com/openai/CLIP) - A model for connecting textual descriptions with images, used for fine-tuning.
- **Cloud Services**:
  - [Google Colab](https://colab.research.google.com/) - An online platform for running Python code in the cloud.

## Features

- **Interactive Sidebar**:
  - **Image Height**: Adjust the height of the generated image.
  - **Image Width**: Adjust the width of the generated image.
  - **Random Seed**: Set a random seed for reproducibility of the generated images.
  - **Inference Steps**: Control the number of steps for the image generation process to balance quality and computation time.
- **Realistic Image Generation**: Utilizes a latent diffusion model to generate high-quality images based on textual descriptions.
- **Downloadable Results**: Option to download the generated image in JPEG format.
- **Custom Loader**: An animated loader is displayed while the image is being generated, providing a better user experience.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Required Python packages (see `requirements.txt`)


To run the Streamlit app in Google Colab, follow these steps:

1. **Open a New Colab Notebook**

    Go to [Google Colab](https://colab.research.google.com/) and create a new notebook.

2. Run all cells to run the streamlit app

3. You will see a URL printed in the last cell output. Click on this URL to open your Streamlit app in a new tab.




