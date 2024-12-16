# Bring Your Own Project - Github Repo
## 1. Fine Tuning Stable Diffusion Model
   - Login to the kaggle
   - Make sure accelerator is on before running the notebook
   - Import the [resized coco demo](https://www.kaggle.com/datasets/deevanshik/resized-coco-demo) dataset from kaggle itself.
     - Note that the mentioned dataset contains images and corresponding text prompts.
     - You can have a look how the prompts look like in the generating-the-text-prompts.ipynb file.
   - Run the notebook : fine-tuning-sdm.ipynb
## 2. Generating Text Prompts
These text prompts are used to fine tune the stable diffusion model by passing them along with the corresponding images.
   - Here, I have generated text prompts for 2000 images taken randomly fromt the COCO dataset.
   - Import the annotation file (link to the file is there in the notebook itself) in the input directory of kaggle.
   - Run the notebook - generating-the-text-prompts.ipynb
   - Download the zip file
## 3. Resizing the Images to desired resolution
For Fine Tuning the SDM, we need a resolution of 512x512 but the COCO dataset had a variety of resolutions. This part resizes the images to 512x512.
- Add the annotation file along with coco dataset in the kaggle input directory.
- Run the file: resizing-coco-images.ipynb
- You will be able to download the zip file from the kaggle output directory once the code is executed.
