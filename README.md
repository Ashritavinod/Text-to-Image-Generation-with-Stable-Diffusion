# 🎨 Text-to-Image Generation with Stable Diffusion

This project demonstrates how to use a pre-trained Stable Diffusion model from Hugging Face for text-to-image generation using custom prompts and parameters.

## 🚀 Overview

This notebook showcases:
- Loading the `dreamlike-art/dreamlike-diffusion-1.0` model.
- Generating high-quality images from text prompts.
- Exploring various generation parameters to control output.
- Running everything in Google Colab (with CUDA support).

## 📒 Steps in the Notebook

1. **Installation**:
   - Required libraries: `diffusers`, `transformers`, `gradio`, `accelerate`.

2. **Model Loading**:
   - Uses `dreamlike-art/dreamlike-diffusion-1.0` from Hugging Face.
   - Uses `torch.float16` and `safetensors` for memory efficiency.
   - Utilizes GPU if available.

3. **Image Generation**:
   - Generates images from text prompts.
   - Visualized using `matplotlib`.

4. **Parameter Exploration**:
   - `num_inference_steps`
   - `height`, `width`
   - `num_images_per_prompt`
   - `negative_prompt`

5. **Custom Image Generation Function**:
   - `generate_image(model, prompt, **params)`

6. **Experimentation**:
   - Try different prompts and parameters for creative results.


## 🛠 Requirements

```bash
pip install -r requirements.txt
