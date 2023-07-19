# TEXT-TO-VID-MODEL-PYTHON
MODEL= "damo-vilab/text-to-video-ms-1.7b"

DETAILED OVERVIEW >> "https://github.com/CreativeAnkush/TEXT-TO-VID-MODEL-PYTHON/blob/main/Text_Vid.ipynb"

DESCRIPTION OF MODEL >> 
LINK TO MODEL- "https://huggingface.co/damo-vilab/text-to-video-ms-1.7b#model-details"

This model is based on a multi-stage text-to-video generation diffusion model, which inputs a description text and returns a video that matches the text description. Only English input is supported.
The text-to-video generation diffusion model consists of three sub-networks: text feature extraction model, text feature-to-video latent space diffusion model, and video latent space to video visual space model. The overall model parameters are about 1.7 billion. Currently, it only supports English input. The diffusion model adopts a UNet3D structure, and implements video generation through the iterative denoising process from the pure Gaussian noise video.

Model Details: 
Developed by: ModelScope
Model type: Diffusion-based text-to-video generation model
Language(s): English
License: CC-BY-NC-ND

OUTPUT VIDEO >>

https://github.com/CreativeAnkush/TEXT-TO-VID-MODEL-PYTHON/assets/92021625/282bdf30-c9fc-4aeb-8f21-1e686f069486

