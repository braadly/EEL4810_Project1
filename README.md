# EEL4810_Project1
A ResNet-18 classifier fine-tuned with LoRA rank-4 to identify brain tumors from MRI scans across seven categories. Trained on ~7,900 images using transfer learning, the model is evaluated with Macro-F1 to ensure balanced detection across all tumor types — critical in medical imaging where missing any class has real consequences.

## Dataset
We have chosen to use [brain tumor dataset](https://huggingface.co/datasets/RyanChen1209/Brain-Tumor-Classification-MRI) posted by RyanChen1209 on [huggingface.co](https://huggingface.co/).

This brain tumor dataset contains 7897 JPEG images of MRI scans of brains wcontaining various types of tumbors, alongside a control group with no tumors. Images are tagged with an integer value to represent one of six types of tumor or no tumor at all.

## Main Model
The main model training program is "Group4NN_Final_Main_Model_Training.ipynb"

## Running
The fully trained main model is available at the following link: https://drive.google.com/file/d/1mXFxq8xzdRrU5r-0_gSKrSB2AO_pzdMl/view?usp=drive_link

To test the model with a specific image, and open the file "Group4NN_Main_Model_Load.ipynb". 
At the bottom of the last section write a function of the form "classify_image('image_path_here.png')", where "image_path_here.png" is the link to an image in your google drive.

You can find various preprocessed images fit for this model at the following link: https://drive.google.com/drive/folders/1RIAev7e1j69Aly_yA2lCkknJCG60QbfY?usp=drive_link
