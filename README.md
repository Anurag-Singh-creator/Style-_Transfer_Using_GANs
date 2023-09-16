# Style_Transfer_Using_GANs
# Problem Statement

Misdiagnosis in the medical field is a very serious issue, yet it's uncomfortably common. When I interpret imaging procedures, it's not a straightforward binary process (Normal or Abnormal). Even among my colleagues, one radiologist might spot something another doesn't, leading to conflicting reports and challenges in recommending effective treatment options for patients.

One of the most challenging tasks in medical imaging is diagnosing MRI (Magnetic Resonance Imaging) scans. Sometimes, to interpret a scan accurately, I need different variations of the imaging, which can drastically enhance diagnosis accuracy by providing a more comprehensive understanding.

However, accessing different imaging variations can be both challenging and expensive. Using deep learning, I aim to leverage style transfer to generate artificial MRI images with different contrast levels from existing MRI scans. This will potentially aid in better diagnosis, given the added perspective from the artificially generated image.

In this capstone, my goal is to use CycleGAN to translate the style of one MRI image to another, enhancing the clarity and understanding of the scan. Specifically, I'll aim to create T2 weighted images from T1 weighted MRI images and vice-versa.

**Problem statement**: My task is to build a Generative Adversarial Model (modified U-Net) that can generate artificial MRI images of different contrast levels from existing MRI scans.

**NOTE**: The T1 and T2 MRI Images included in the dataset are unrelated since it's an unpaired dataset.

## Project Pipeline

The project can be broadly segmented into the following steps:

1. **Data Understanding**: Load the data and set up the dataset.
2. **Image Processing**: Process the images through various steps to ready them for the model.
3. **Model-Building and Training**: Here, I'll create the Generators and Discriminators using a modified U-Net architecture (similar to CycleGAN). Additionally, I'll define the loss function and finalize the training steps.

**Note**: I'll be submitting a zip file containing a Jupyter notebook. Evaluation rubrics are provided separately. The notebook will also visualize the predicted data for clearer understanding.
