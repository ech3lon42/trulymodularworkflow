# Truly Modular Workflows

**_Rethinking the way we use ComfyUI_**

## Main features:
### Breaks up the workflow into functional parts called modules (or stages).

> Several powerful modules are included for you to play with. These are described in detail below and include:
> - Combine and switch effortlessly between SDXLTurbo, SD15 and SDXL, IPAdapter with Masking, HiresFix, Reimagine, Variation Maker, Noise Detailer, Person Detailer, Latent Upscale, Ultimate SDUpscale, IPAdapter assisted Upscale, Face Detailer, Face Swap, Controlnet Pose/Depth (single and batch), LCM Sampling for any module, IPAdapter for any module, Background Swapping, Auto generation (One Button Prompt), SDXLTurbo Live Drafting, Execution Presets, Image Choosers, Kohya DeepShrink, Passing Loras and Embeddings directly through your prompt and more.

> Easily extend the workflow with your own plug-and-play modules. More information below.

### Easy Toggles.

> Use a single UI Switch to toggle any of the modules, creating your own custom workflow with just a few clicks.
> <details>
> <summary>ℹ️ <i>Example</i></summary>
> 
> ![Context Node](documentation/images/teaser_switch.png)
> 
> </details>


### Create Presets.
> Configure which modules you want to run in your workflow and save them as a preset that can be run with a single click.
> <details>
> <summary>ℹ️ <i>Example</i></summary>
> 
> ![Context Node](documentation/images/teaser_presets.png)
> 
> </details>

### Selective Processing.
> Generate several images and choose which ones you wish to progress.
> <details>
> <summary>ℹ️ <i>Example</i></summary>
>
> ![Context Node](documentation/images/teaser_chooser.png)
>
> </details>

### Pause, Resume and Restart (Anywhere).
> Pause and restart the workflow at any stage or module of your choice with any images of your choice.
> <details>
> <summary>ℹ️ <i>Always Pause</i></summary>
> Pauses the workflow before any particular module and lets you select which images (from the previous stage) to progress.
>
> ![Context Node](documentation/images/pause_always.png)
>
> </details>
> <details>
> <summary>ℹ️ <i>Pause if Batch</i></summary>
> Pauses the workflow before any particular module, but only if there is more than one incoming image (from the previous stage) to choose from.
>
> ![Context Node](documentation/images/pause_batch.png)
>
> </details>
> <details>
> <summary>ℹ️ <i>Pass through</i></summary>
> Does not pause the workflow before the module and automatically passes on any incoming images (from the previous stage).
>
> ![Context Node](documentation/images/pause_pass_through.jpg)
>
> </details>

### Instantly switch between SDXL, SD15 and SDXLTurbo.
> Switch between SDXL, SD15 and SDXLTurbo with the click of a button. This uses special repeater nodes to automatically switch all modules to the proper CLIP format and to activate the correct IPAdapter models. The only thing you may have to do is update your custom loras.
> 
> You can also start progressing an image in SDXL and pause the workflow anywhere you like, switch to SD15 and continue form there.
> 
> Prop tip: Start by generating a large batch of images in SDXLTurbo or even in Live Drafting. Then select the images you like and continue processing them with a high quality model in SD1.5. Simply activate 'Initial Gen (Turbo)' in the Workflow Enabler and activate 'Enable SD1.5' in the SD1.5 or SDXL selection Box. Your initial image will be generated using SDXLTurbo and the rest will be done in SD1.5. Of course you may also configure any particular custom models and VAE you'd like to use. It's that easy.
> <details>
> <summary>ℹ️ <i>Example</i></summary>
>
> ![Context Node](documentation/images/switch_sd15.png)
> 
> > ![Context Node](documentation/images/switch_sdxl.png)
>
> </details>

### Powerful Control Panels.
> Each module comes with a separate control panel that allows configuration of all parameters.
> <details>
> <summary>ℹ️ <i>Example</i></summary>
>
> ![Context Node](documentation/images/controlpanels.png)
>
> </details>
>
> The control panel includes an Options box that allows you to toggle the use of LCM, IPAdapter and CFG Rescale within that module.
> <details>
> <summary>ℹ️ <i>Options Example</i></summary>
>
> ![Context Node](documentation/images/options.png)
>
> </details>
>
> You have fine control over the start, end and strength of the IPAdapter in each module. Or you can disable the use of IPAdapter altogether. You may even pass a completely new image to the IPAdapter. On top of that you may mix the new image with the original image (from the previous stage) and define the strength of each one (dual IPAdapter).
> <details>
> <summary>ℹ️ <i>IPA Example</i></summary>
>
> ![Context Node](documentation/images/ipa_override.png)
>
> </details>
>
> For each module you may configure any sampler and scheduler you prefer, as well as cfg and steps. The options panel allows you to switch to the LCM sampler in order to speed up the processing time of the module significantly. Simply activate 'Enable LCM' and set the KSampler Config  in the modules control panel. Select the 'LCM' sampler and 'sgm_uniform' scheduler, steps 4 and cfg 1.1. That's it. Your module is now using high-speed LCM sampling. This works for all modules, latent upscalers, detailers, highres fix, sdupscale and so on.
> <details>
> <summary>ℹ️ <i>LCM Example</i></summary>
>
> ![Context Node](documentation/images/lcm_anywhere.png)
>
> </details>
> 
> Some modules contain additional parameters and toggles which are specific to the module. The detailers include additional prompts, upscalers include resize options etc.

### Powerful Prompting.
### Powerful Controlnets.
### Powerful IPAdapters.

## The Modules

## Installation