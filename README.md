# DreamBooth: Fine Tuning Text-to-Image Diffusion Models 🎨🖼️✨🖌️

## Create Ultra-realistic photos of your animal completely for free under 10 Minutes with just 3-5 images ! 🎨✨

Welcome to DreamBooth, your ticket to a world of endless imagination with your animal! 
With DreamBooth, you're not just generating images – you're creating amazing scenarios with your loved pet/animal.


**Scenarios can literally be anything you want, possibilities are endless ✨** 🚀

Here are some cool images I created with just 4 pictures I took of my cat called "spy".


I generated eveything under 10 min and you can do this right now **with no installation or hardware required !**

spy in the snow            |  spy with a mountain in the background
:-------------------------:|:-------------------------:
 ![prompt_0_img_0 (1)](https://github.com/dalixMasmoudi/GenAI_Dreambooth/assets/94851502/2e3ef757-8511-472c-bee1-7333746d1d1e) |  ![prompt_6_img_0 (1)](https://github.com/dalixMasmoudi/GenAI_Dreambooth/assets/94851502/e3b48fca-a8c2-4eca-986c-3a1ae1152cf5)


spy wearing a santa hat           |  spy wearing a rainbow scarf"
:-------------------------:|:-------------------------:
![prompt_8_img_0 (1)](https://github.com/dalixMasmoudi/GenAI_Dreambooth/assets/94851502/27591290-c893-4735-ba8a-81cfe01af549) | ![prompt_9_img_0 (1)](https://github.com/dalixMasmoudi/GenAI_Dreambooth/assets/94851502/3613e2bb-966d-4522-8c1e-6de09dac65bd)





To truly experience the magic of DreamBooth, I invite you to open the project on  **Google Colab** . 


There, you'll have GPU usage (Needed for finetuning the model on your personal images) with **16 GBs of free usage**, ready and waiting for you to use. Trust me, it will make the experience you won't want to miss!

With the **Gen_AI_with_Dreambooth** Notebook, all repos and all dependencies needed will be installed automatically. You dont have do anything about it !
## Getting Started

To start on your DreamBooth journey, follow these simple steps:

1. **Clone the Repository or download the notebook file manually:**
```bash
   git clone https://github.com/dreambooth/DreamBooth.git
```

2. **Upload the Notebook file on google collab account after loggin in and activate GPU usage on the top right.**

3. **Create folders for the 2 folders called spy and cats and upload the images made available in this repository.**

4. **Follow the script. The instructions are very intuitive. Just run the cells in order**

4. **Train DreamBooth:**
- Fine-tune DreamBooth using the `train_dreambooth.py` script with desired command-line arguments.
- Explore options such as resolution, batch size, learning rate, and more to customize your training experience.
![DreamBooth Teaser](https://dreambooth.github.io/DreamBooth_files/teaser_static.jpg)

## Usage

DreamBooth offers a seamless workflow for generating images:

- **Inference with Multiple Images:** Generate multiple images based on different prompts using the provided `gen_imgs` function.
- **Inference with Single Image:** Generate a single image for a specific prompt and customize the inference steps for optimal results with the `gen_and_display_single_img` function.
- **Schedulers:** Experiment with different schedulers to control the noise addition process during inference and explore their impact on output diversity.

## Prior Preservation Loss (PPL)

DreamBooth introduces an innovative approach to mitigate language drift and enhance output diversity through Prior Preservation Loss (PPL). By supervising the model with its own generated samples, PPL ensures maximum subject fidelity and encourages diverse image generation.


## Results: 

You will find all your generated images in the ´´generated_images´´´folder.


## Contact

For inquiries and collaboration opportunities, feel free to reach out to us at [dmasmoudi@ymail.com](mailto:dmasmoudi@ymail.com). 


**Be creative with your promtps and enjoy generating right now!** 🎨🖼️🚀🐱✨🖌️
