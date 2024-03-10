🌌 Towel Movement: 🌌

Welcome to Towel Movement, made of these 3 repos:
## https://github.com/AUTOMATIC1111/stable-diffusion-webui
## https://github.com/thygate/stable-diffusion-webui-depthmap-script
## https://github.com/towelWet/Towel-Music-Visualizer-Node-JS


🌟 Key Features:

🎨 Stable Diffusion WebUI Features:

Original txt2img and img2img modes
One-click install (Python and Git required)
Artistic features like Outpainting, Inpainting, and Color Sketch
Advanced settings like X/Y/Z plot, Textual Inversion, and more
🗺️ Depth Map Script Features:

Generate or use custom depth maps
Create 3D stereo image pairs
Video processing support
Standalone mode available
📥 Installation:

🖥️ Windows: Use webui-user.bat after installing Python 3.10.6 and Git
🐧 Linux: Run ./webui.sh after installing dependencies
🍎 macOS: Navigate to the main directory and run ./webui.sh
🎯 Goals: Video Loop 🎯

🗺️ Depth Map

Our goal is to offer a robust depth map feature that will serve as the foundation for creating lifelike video loops.

🎭 Animation Style

We plan to offer multiple animation styles to suit different artistic visions:

Horizontal
Wide Circle
Circle
Tall Circle
Vertical
Perspective
⏳ Animation Length

To cater to various use-cases, we aim to provide a flexible range of animation lengths, from short to long.

🌪️ Amount of Motion

Users will have the option to control the amount of motion in the video loop, ranging from subtle movements to more dynamic actions.

🎯 Focus Point

The focus point feature will allow users to decide where the viewer's attention should be directed, from close-up subjects to far-off landscapes.

🌐 Edge Dilation

This feature will enable users to control the dilation of edges in the video loop, offering a range from less to more dilation for different artistic effects.

🛠️ Advanced Editor

For those who wish to dive deeper into customization, the Advanced Editor will offer the following settings:

Amplitude X
Amplitude Y
Amplitude Z
Phase X
Phase Y
Phase Z

🌐 Main Repo - javascript • 📁 Folder: stable-diffusion-webui/javascript o 📄 all_files_main_repo_javascript.txt o 🎮 imageviewerGamepad.js o 🖼 aspectRatioOverlay.js o 📑 inputAccordion.js o 🖱 contextMenus.js o 💾 localStorage.js o 🖐 dragdrop.js o 🌍 localization.js o ✏ edit-attention.js o 🔔 notification.js o 📝 edit-order.js o 📊 profilerVisualization.js o ➕ extensions.js o ⏳ progressbar.js o 🌐 extraNetworks.js o ↔ resizeHandle.js o 🛠 generationParams.js o 📝 textualInversion.js o 💡 hints.js o 🔢 token-counters.js o 🖼 hires_fix.js o 🎛 ui.js o 🖼 imageMaskFix.js o 🎛 ui_settings_hints.js o 🖼 imageviewer.js

Repository Directory Structure 🗂️

Main Repository: stable-diffusion-webui 🎨
JavaScript Folder 📁

stable-diffusion-webui/javascript
all_files_main_repo_javascript.txt
imageviewerGamepad.js 🎮
aspectRatioOverlay.js 🖼️
inputAccordion.js 📑
contextMenus.js 🖱️
localStorage.js 💾
dragdrop.js 🖐️
localization.js 🌍
edit-attention.js ✏️
notification.js 🔔
edit-order.js 📝
profilerVisualization.js 📊
extensions.js ➕
progressbar.js ⏳
extraNetworks.js 🌐
resizeHandle.js ↔️
generationParams.js 🛠️
textualInversion.js 📝
hints.js 💡
token-counters.js 🔢
hires_fix.js 🖼️
ui.js 🎛️
imageMaskFix.js 🖼️
ui_settings_hints.js 🎛️
imageviewer.js 🖼️
Scripts Folder 📜

stable-diffusion-webui/scripts
all_files_main_repo_scripts.txt
postprocessing_codeformer.py 🐍
postprocessing_gfpgan.py 🐍
custom_code.py 🐍
img2imgalt.py 🐍
loopback.py 🔄
postprocessing_upscale.py 🐍
prompt_matrix.py 🐍
prompts_from_file.py 🐍
outpainting_mk_2.py 🎨
poor_mans_outpainting.py 🎨
sd_upscale.py 🐍
xyz_grid.py 🐍
Modules Folder 🧩

stable-diffusion-webui/modules
all_files_extensions_modules.txt
depthmap.py 🗺️
depthmap_api.py 🗺️
Root Folder Files 📌

stable-diffusion-webui
CHANGELOG.md 📄
CITATION.cff 📄
CODEOWNERS 📄
LICENSE.txt 📄
README.md 📄
pyproject.toml 📄
requirements-test.txt 📄
requirements.txt 📄
requirements_versions.txt 📄
package.json 📄
.pycache 🗑️
cache.json 📄
webui.py 📄
webui.sh 📄

Extension: stable-diffusion-webui-depthmap-script 🔍
Scripts Folder 📁

stable-diffusion-webui/extensions/stable-diffusion-webui-depthmap-script/scripts
all_files_extensions_scripts.txt
depthmap.py 🗺️
depthmap_api.py 🗺️
Source Folder 📁

stable-diffusion-webui/extensions/stable-diffusion-webui-depthmap-script/src
all_files_extensions_src.txt
depthmap_generation.py 🗺️
gradio_args_transport.py 📡
backbone.py 🦴
misc.py 🛠️
common_constants.py 📜
normalmap_generation.py 🗺️
common_ui.py 🧰
stereoimage_generation.py 👓
core.py 💻
video_mode.py 🎥
Root Folder Files 📌

stable-diffusion-webui-depthmap-script
CHANGELOG.md 📄
LICENSE 📄
README.md 📄
__init__.py 📄
bundled_sources.txt 📄
main.py 📄
requirements.txt 📄
install.py 📄
dzoedepth 📁
src 📁

Configuration File 🛠️
/Volumes/Knowledge/Towel-Ware/Towel-Movement/stable-diffusion-webui/ui-config.json

Files in 'modules' folder (overview from main automatic1111 repo):

Filename: ui.py • Description: This Python file appears to contain code related to the Gradio user interface (UI) for interacting with machine learning models. It defines various functions and components for setting up the Gradio UI, handling user input, and displaying outputs. The code includes functions for processing images, running inference on user input, and interacting with the Gradio UI elements.

Filename: ui_checkpoint_merger.py • Description: This Python file appears to contain code related to the Gradio UI for checkpoint merging. It defines various UI components and functions for merging neural network model checkpoints. The code allows users to select primary, secondary, and tertiary models, choose an interpolation method, and configure various settings for the merging process. The file also includes descriptions for the interpolation methods and handles exceptions during the merging process.

Filename: ui_common.py • Description: This Python file appears to contain code related to user interface (UI) components and functions for a Gradio interface. It defines various UI elements such as buttons, checkboxes, and forms, along with their respective actions and behaviors. The code handles interactions related to saving files, updating generation information, and creating output panels. It also includes functions for saving files in different formats and opening folders.

Filename: ui_components.py • Description: This file defines custom UI components that can be used within Gradio forms. It includes the following classes: • FormComponent: A base class for custom form components. • ToolButton: A small button with a single emoji as text, designed to fit inside Gradio forms. • ResizeHandleRow: A class that represents a row within Gradio forms, designed to fit inside Gradio forms and includes resizing handles.

Filename: ui_extensions.py • Description: This Python file contains code related to managing extensions in a Gradio interface. It includes functions for applying and restarting extensions, saving and restoring configuration states, checking for extension updates, and generating an extension table for display. The file also defines several custom UI components, such as FormRow, FormColumn, FormGroup, FormHTML, FormColorPicker, DropdownMulti, DropdownEditable, and InputAccordion, which are used to create various UI elements for configuring and interacting with extensions.

Filename: ui_extra_networks.py • Description: This Python file contains code related to managing extra networks and pages in a Gradio interface. It includes functions for registering extra network pages, fetching files from allowed directories, and defining UI components for working with extra networks. The file also handles saving and reading image information, as well as UI components like ToolButton and extra_pages.

Filename: ui_extra_networks_checkpoints.py • Description: This Python file contains code related to handling checkpoint data in extra networks. It defines a class ExtraNetworksPageCheckpoints that represents a page for managing checkpoints. This page allows users to list, select, and view checkpoint details. It also provides functions for refreshing checkpoint data, listing items, and managing user metadata for checkpoints.

Filename: ui_extra_networks_checkpoints_user_metadata.py • Description: This Python file contains code for managing user metadata for checkpoints in extra networks. It defines a class CheckpointUserMetadataEditor that allows users to edit and save metadata for checkpoints. The class provides functions for setting up the UI components, saving user metadata, updating VAE (Variational Autoencoder) weights, and more.

Filename: ui_extra_networks_hypernets.py • Description: This Python file defines a class ExtraNetworksPageHypernetworks for managing hypernetworks in extra networks. It provides functions for listing hypernetworks, refreshing data, creating items, and specifying directories for previews.

Filename: ui_extra_networks_textual_inversion.py • Description: This Python file defines a class ExtraNetworksPageTextualInversion for managing textual inversion models in extra networks. It provides functions for listing textual inversion models, refreshing data, creating items, and specifying directories for previews. This page is specifically designed for textual inversion models.

Filename: ui_extra_networks_user_metadata.py • Description: This Python file contains code related to managing user metadata for extra networks. It defines a UserMetadataEditor class that can be used to edit and save metadata for different types of extra network items. This class sets up UI components for editing metadata, saving user metadata, and more.

Filename: ui_gradio_extensions.py: • Description: This Python file contains code related to Gradio extensions. It defines a function webpath for generating web paths for files, a function javascript_html for including JavaScript scripts in the HTML, and other utilities related to handling scripts and files within Gradio extensions.

Filename: ui_loadsave.py: • Description: This Python file defines a class UiLoadsave for managing the saving and loading of default values for Gradio components. It allows users to save and restore default values for Gradio UI elements. The class provides methods for adding Gradio components to the registry of tracked components, reading and writing default values to a file, and iterating over changes between default values and current values.

Filename: ui_postprocessing.py: • Description: This Python file defines the creation of a Gradio UI for postprocessing images. It includes elements for selecting processing mode, choosing input sources, specifying input and output directories for batch processing, and running the postprocessing operation.

Filename: ui_prompt_styles.py: • Description: This Python file is related to defining UI components for managing prompt styles. It includes functions for selecting, saving, deleting, and applying prompt styles to user prompts. It also provides a UI for managing prompt styles in the main Gradio interface.

Filename: ui_settings.py: • Description: This Python file defines the creation of a Gradio UI for managing settings and options. It includes elements for adjusting various settings and options, saving changes, and reloading the Gradio UI. The file also manages quick settings and the layout of different sections within the settings UI.

Filename: ui_tempdir.py: • Description: This Python file appears to manage temporary files and directories for Gradio. It includes functions for registering and checking temporary files, saving PIL images to temporary files with PNG metadata, and cleaning up temporary directories. It also includes an override for saving PIL images to temporary files to ensure PNG metadata is saved.

Files in 'scripts' folder (overview from main automatic1111 repo):

custom_code.py:
Handles custom code execution within the Gradio interface.
Defines two functions:
convertExpr2Expression(expr): Modifies the attributes of an expr object and returns a new ast.Expression object.
exec_with_return(code, module): Similar to the built-in exec() function, but can return values. It takes a string of Python code and a module object as arguments.

img2imgalt.py:
Related to image-to-image conversion processes.
Defines a function find_noise_for_image(p, cond, uncond, cfg_scale, steps) that finds noise for an image as part of the conversion process using various libraries such as shared, K, and torch.

loopback.py:
Related to a Gradio interface for a loopback script.
Defines a class Script with methods:
title(): Returns the string "Loopback".
show(is_img2img): Returns the value of the boolean argument is_img2img.
ui(is_img2img): Defines a Gradio UI component for the script, including a slider for the number of loops with a minimum value of 1, maximum value of 32, and default value of 4.

outpainting_mk_2.py:
Related to outpainting, the process of extending the content of an image beyond its borders.
Defines functions for generating matched noise for an image as part of the outpainting process, including get_matched_noise(_np_src_image, np_mask_rgb, noise_q=1, color_variation=0.05).

poor_mans_outpainting.py:
A simpler version of outpainting.
Defines a class Script with methods:
title(): Returns the string "Poor man's outpainting".
show(is_img2img): Returns the value of the boolean argument is_img2img.
ui(is_img2img): Defines a Gradio UI component for the script, including a slider for the number of pixels to be added to the image with a minimum value of 1, maximum value of 100, and default value of 10.

postprocessing_codeformer.py:
Related to post-processing using CodeFormer, a machine learning model.
Defines a class ScriptPostprocessingCodeFormer with a method ui() that defines a Gradio UI component for the script, including a slider for the CodeFormer visibility with a minimum value of 0.0, maximum value of 1.0, step of 0.001, and default value of 0.

postprocessing_gfpgan.py:
Related to post-processing using GFPGAN, a generative adversarial network.
Defines a class ScriptPostprocessingGfpGan with a method ui() that defines a Gradio UI component for the script, including a slider for the GFPGAN visibility with a minimum value of 0.0, maximum value of 1.0, step of 0.001, and default value of 0.

The file postprocessing_upscale.py contains import statements, variable declarations, and a class definition.

Import Statements:
Image from PIL
numpy as np
scripts_postprocessing and shared from modules
gr from gradio
FormRow, ToolButton from modules.ui_components
switch_values_symbol from modules.ui
Variable Declarations:
upscale_cache: A dictionary to store cached values for upscaling.
Class Definition:
ScriptPostprocessingUpscale: A class that inherits from scripts_postprocessing.ScriptPostprocessing. This class has the following attributes and methods:
name: A string attribute with the value "Upscale".
order: An integer attribute with the value 1000.
ui(): A method that defines the Gradio UI components for the script. The UI includes a column with form rows, tabs, and various buttons and sliders for controlling the upscaling process.

prompt_matrix.py:
Related to handling prompt matrices for generating images based on text prompts.
Defines a function draw_xy_grid(xs, ys, x_label, y_label, cell) that creates a grid for prompt matrices and processes images based on the prompts using the process_images() function from the modules.processing module.

prompts_from_file.py:
Related to handling prompts from a file and processing their values.
Defines functions to process prompt values based on their types, including process_string_tag(tag), process_int_tag(tag), process_float_tag(tag), and process_boolean_tag(tag).
Contains a dictionary prompt_tags that maps various keys to values, which are processed using the functions defined in the file.

Files in 'src' folder (overview from main thygate repo):

backbone.py
This file contains the BackboneType enum class and imports several modules from stable-diffusion-webui, such as save_image and torch_gc.

common_constants.py
This file defines the GenerationOptions enum class with default values for various generation options such as COMPUTE_DEVICE, MODEL_TYPE, BOOST, NET_SIZE_MATCH, NET_WIDTH, NET_HEIGHT, and DO_OUTPUT_DEPTH.

common_ui.py
This file imports various modules and defines functions related to the Gradio UI. It also includes the ensure_gradio_temp_directory function.

core.py
This file contains various functions related to image processing and generation, such as core_generation_funnel, unload_models, and run_makevideo. It also defines constants like REPOSITORY_NAME, SCRIPT_NAME, and SCRIPT_VERSION.

depthmap_generation.py
This file defines the ModelHolder class and contains functions related to depth map generation.

gradio_args_transport.py
This file defines the GradioComponentBundle class, which is used to bundle Gradio components for ease of use.

misc.py
This file contains various utility functions.

normalmap_generation.py
This file defines the create_normalmap function, which generates normal maps from depth maps.

stereoimage_generation.py
This file defines the create_stereoimages function, which generates stereo images from original images and depth maps.

video_mode.py
This file contains functions related to video processing, such as open_path_as_images.

Common "Serious" Errors:

AttributeError: 'NoneType' object has no attribute 'cond_stage_model'
This error indicates that the shared.sd_model object is None when trying to access its cond_stage_model attribute. This suggests that the stable diffusion model failed to load correctly.

RuntimeError: MPS backend out of memory
This error indicates that the application ran out of memory while trying to allocate space for the model. The application is using the MPS (Metal Performance Shaders) backend on a Mac, and it seems that the allocated memory for MPS has been exceeded.

##Run on windows with cpu only:

1. **Install Python 3.10.6:**
   - Download Python 3.10.6 from the official Python website.
   - During installation, ensure you check the option "Add Python to PATH".

2. **Navigate to the Repository Folder:**
   - Change directory to the cloned repository:
     ```shell
     cd stable-diffusion-webui
     ```

3. **Run the Installation Batch File:**
   - Execute the `webui-user.bat` file by double-clicking on it in Windows Explorer or running it from the command prompt.

4. **Encounter the Error:**
   - The installation will attempt to install GPU versions of PyTorch and torchvision, which will fail on a CPU-only system, leading to the error message you received.

To correct this and proceed with a CPU-only installation:

5. **Create a Virtual Environment** (if not already created):
   ```shell
   python3 -m venv venv
   ```

6. **Uninstall the GPU version of PyTorch and torchvision:**
   - Activate the virtual environment:
     ```shell
     venv\Scripts\activate
     ```
   - Uninstall the GPU versions:
     ```shell
     pip uninstall torch torchvision
     ```

7. **Install the CPU version of PyTorch:**
   - Install the CPU version of PyTorch with the following command:
     ```shell
     pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cpu
     ```

8. **Downgrade the `httpx` library** to version 0.24.1:
   ```shell
   pip install httpx==0.24.1
   ```

9. **Install the Requirements:**

Ensure you have the requirements.txt or similar file provided by the repository.
   - Run:
     ```shell
     pip install -r requirements.txt
     ```

10. **Modify the `webui-user.bat` file:**
   - Edit the `webui-user.bat` file to prevent future attempts to install the GPU version of PyTorch.

11. **Run the script with the CPU flag:**
    - Set the environment variable to skip the GPU check:
      ```shell
      set COMMANDLINE_ARGS=--skip-torch-cuda-test
      ```
    - Run the `webui-user.bat` file again.
   

## Running on a Mac:

1. **Navigate to the Repository Folder**:
   ```shell
   cd stable-diffusion-webui
   ```

2. **Create a Virtual Environment** (if not already created):
   ```shell
   python -m venv venv
   ```

3. **Activate the Virtual Environment**:
   ```shell
   source venv/bin/activate
   ```

4. **Downgrade the `httpx` library** to version 0.24.1:
   ```shell
   pip install httpx==0.24.1
   ```

5. **Install the Requirements**:
   - Ensure you have the `requirements.txt` or similar file provided by the repository.
   - Run:
     ```shell
     pip install -r requirements.txt
     ```

6. **Launch the Web UI**:
   - Use the provided shell script which should be made executable:
     ```shell
     ./webui.sh
     ```

   If the `webui.sh` script is not executable, you may need to make it executable by running:
   ```shell
   chmod +x webui.sh
   ```

   Then attempt to run it again:
   ```shell
   ./webui.sh
   ```

These steps should start the stable-diffusion-webui on your Mac. If you encounter any issues, refer back to the repository's documentation or issue tracker for the most recent updates or troubleshooting tips.
