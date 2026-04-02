# EEL4810_Project1
A ResNet-18 classifier fine-tuned with LoRA rank-4 to identify brain tumors from MRI scans across seven categories. Trained on ~7,900 images using transfer learning, the model is evaluated with Macro-F1 to ensure balanced detection across all tumor types — critical in medical imaging where missing any class has real consequences.

## Dataset
We have chosen to use [brain tumor dataset](https://huggingface.co/datasets/RyanChen1209/Brain-Tumor-Classification-MRI) posted by RyanChen1209 on [huggingface.co](https://huggingface.co/).

This brain tumor dataset contains 7897 JPEG images of MRI scans of brains wcontaining various types of tumbors, alongside a control group with no tumors. Images are tagged with an integer value to represent one of six types of tumor or no tumor at all.

## Modules


## Running
