# Illustrious-Modular-WF
Illustrious Modular WF for ComfyUI

Just an adaptation of my classic Modular workflows for Illustrious XL (but it should also work with SDXL).

The workflow will let you generate txt2img and img2img outputs, it has the following modules:  HiRes Fix, Ultimate SD Upscaler, FaceDetailer, and a post-production node.

Also, the generation will stop once the basic image is created ("Image Filter" node) to allow you to choose whether to continue the workflow with that image or cancel it. This is extremely useful when you generate a large batch of images!

Also, the Save Image node will save all the metadata about the generation of the image, and the metadata is compatible with CivitAI too!
