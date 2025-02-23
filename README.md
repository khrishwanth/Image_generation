# Image generation using comfy ui

## Introduction
ComfyUI is a node-based GUI for Stable Diffusion. By chaining different blocks (called nodes) together, you can construct an image generation workflow. Some commonly used blocks are Loading a Checkpoint Model, entering a prompt, specifying a sampler, etc. ComfyUI breaks down a workflow into rearrangeable elements so you can easily make your own.
## Steps on how to use it
[Direct link to download](https://github.com/comfyanonymous/ComfyUI?tab=readme-ov-file#direct-link-to-download)

Simply download, extract with [7-Zip](https://7-zip.org/)and run. Make sure you put your Stable Diffusion checkpoints/models (the huge ckpt/safetensors files) in: ComfyUI\models\checkpoints

If you have trouble extracting it, right click the file -> properties -> unblock

If you have a 50 series Blackwell card like a 5090 or 5080 see this [discussion thread](https://github.com/comfyanonymous/ComfyUI/discussions/6643)

How do I share models between another UI and ComfyUI?
See the [Config file](https://github.com/comfyanonymous/ComfyUI/blob/master/extra_model_paths.yaml.example) to set the search paths for models. In the standalone windows build you can find this file in the ComfyUI directory. Rename this file to extra_model_paths.yaml and edit it with your favorite text editor.
