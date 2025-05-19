# Brainwave_Matrix_Intern  
# Task 2: Text-to-Image Generation App

This task involves building a generative AI application that transforms user-provided text prompts into images using a pretrained diffusion model.

## Objective:
- Develop a text-to-image generation app using FastAPI and the Stable Diffusion model.
- Allow users to enter a text description and receive a generated image as output.
- Learn the basics of serving generative models through APIs and integrating them with a frontend.

## Task Details:
- The backend is built using **FastAPI** and loads the **Stable Diffusion v1.5** model from Hugging Face.
- The model is used to process a text prompt and generate an image, which is saved locally.
- A simple HTML frontend lets users submit prompts and receive generated images.
- The project is structured to run locally on CPU or GPU (if available).

## Repository:
The code for this task can be found in the `text2image-app` repository. You can access the repository at the following link:

👉 [Text-to-Image Generator Repository](https://github.com/MhamedHalloub/image-generator)

## Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/MhamedHalloub/image-generator
   cd text2image-app/backend
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the FastAPI server:
   ```bash
   uvicorn main:app --reload
   ```

4. Open the `frontend/index.html` file in your browser and submit a prompt.

5. The generated image will be saved in the `output/` folder as `output.png`.

## Tools & Technologies:
- Python
- FastAPI
- Hugging Face `diffusers`
- Stable Diffusion v1.5
- HTML/CSS (basic frontend)
- Torch (PyTorch)

