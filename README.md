# Text-to_3D

This project implements an end-to-end 3D reconstruction pipeline that begins with image synthesis using a Stable Diffusion text-to-image model. The generated image is then processed using a pretrained monocular depth estimation network to infer scene geometry. The resulting depth map is combined with the synthesized RGB image to form an RGBD representation, which is used to generate and post-process a 3D point cloud and ultimately reconstruct a 3D mesh using Open3D.

## Bengal Tiger:

Prompt: "A bengal tiger in the foreground and short green grass in the background ultra HD 8k immersive"

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/984500d5-2924-4d48-ba0d-829a2846990d" />

## Woodpecker:

Prompt: "A woodpecker flying in ultra 8k hd with the sky in the background immersive"

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/b528bb0b-bb82-4397-9057-9046a1510e8c" />
