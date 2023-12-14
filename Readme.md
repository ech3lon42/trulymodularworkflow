# Truly Modular Workflows

**_Rethinking the way we use ComfyUI_**

## Main features:
### Breaks up the workflow into functional parts called modules.

> Several powerful modules are included for you to play with. These are described in detail below and include:
> - Combine and switch effortlessly between SDXLTurbo, SD15 and SDXL, IPAdapter with Masking, HiresFix, Reimagine, Variation Maker, Noise Detailer, Person Detailer, Latent Upscale, Ultimate SDUpscale, IPAdapter assisted Upscale, Face Detailer, Face Swap, Controlnet Pose/Depth (single and batch), LCM Sampling for any module, IPAdapter for any module, Background Swapping, Auto generation (One Button Prompt), SDXLTurbo Live Drafting, Execution Presets, Image Choosers, Kohya DeepShrink, Passing Loras and Embeddings directly through your prompt and more.

> Easily extend the workflow with your own plug-and-play modules. More information below.

### Easy Toggles.

> Use a single UI Switch to toggle any of the modules, creating your own custom workflow with just a few clicks.
> <details>
> <summary>ℹ️ <i>Example</i></summary>
> 
> ![Context Node](documentation/images/teaser_switch2.jpg)
> 
> </details>


### Create Presets.
> Configure which modules you want to run in your workflow and save them as a preset that can be run with a single click.
> <details>
> <summary>ℹ️ <i>Example</i></summary>
> 
> ![Context Node](documentation/images/teaser_presets2.jpg)
> 
> </details>

### Selective Processing.
> Generate several images and choose which ones you wish to progress.
> <details>
> <summary>ℹ️ <i>Example</i></summary>
>
> ![Context Node](documentation/images/teaser_chooser.jpg)
>
> </details>

### Pause, Resume and Restart.
> Pause and restart the workflow at any stage or module of your choice.
> <details>
> <summary>ℹ️ <i>Always Pause</i></summary>
> Pauses the workflow before any particular module.

> ![Context Node](documentation/images/teaser_chooser.jpg)
>
> </details>
> <details>
> <summary>ℹ️ <i>Pause if Batch</i></summary>
> Pauses the workflow before any particular module, but only if there is more than one incoming image to choose from.

> ![Context Node](documentation/images/teaser_chooser.jpg)
>
> </details>
> <details>
> <summary>ℹ️ <i>Pass through</i></summary>
> Does not pause the workflow before the module and automatically passes on any incoming images.

> ![Context Node](documentation/images/teaser_chooser.jpg)
>
> </details>
## The Modules

## Installation