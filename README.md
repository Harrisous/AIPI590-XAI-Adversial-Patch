# AIPI 590 XAI - Adversial Patch

## Background
- Model used: Torchvision ResNet34 model trained on a small version of ImageNet
- Classes available: check imagenet_classes.txt

## Task
Create an adversial patch to fool the image model into making a wrong classification. 
- Attack objective: recreational vehicle

## Deliverable
A physical patch is brought on testing day. Improvement from the original tutorial method: 
- Trained the patch to be robust with different location, size, transparency and 3D rotation/distortion
- The final patch will be made into some kind of painting/camouflage

## Reference: 
Naive batch creation tutorial: https://github.com/AIPI-590-XAI/Duke-AI-XAI/blob/main/adversarial-ai-example-notebooks/adversarial_attacks_patches.ipynb
