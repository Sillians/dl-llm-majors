# dl-llm-majors

Explore the evolution of neural networks through this repository. You’ll start with the core building blocks and work your way up to implementing sophisticated models like GPT.


## **Notebooks**

This series of notebooks is designed to be completed in order:

1. `1_building_blocks.ipynb`: The fundamental building blocks of deep learning.

2. `2_your_first_model.ipynb`: Build your first neural network.

3. `3_learning_patterns_cnn.ipynb`: Learn about convolutional neural networks for image recognition.

4. `4_going_deeper_resnet.ipynb`: Dive into deeper architectures with ResNets.

5. `5_from_pixels_to_prose.ipynb`: Explore models that can generate text from images.

6. `6_the_main_event_gpt.ipynb`: Build and understand the GPT model.

7. `7_demystifying_inference.ipynb`: Learn about the process of using a trained model.

8. `8_huggingface_finetuning.ipynb`: Fine-tune models using the Hugging Face ecosystem.


## **Prerequisites**

- `Python 3.10+`
- `uv` package manager. You can install it by following the [official instructions](https://github.com/astral-sh/uv).


## **Platform-specific Instructions**

**macOS (Apple Silicon)**

The default setup using `uv` should work correctly on Apple Silicon Macs. PyTorch will use the `Metal Performance Shaders (MPS)` backend for acceleration.

**Linux with NVIDIA GPU**

To leverage your `NVIDIA GPU`, you need to have the NVIDIA drivers and CUDA Toolkit installed. The dependencies in `pyproject.toml` are configured for CUDA.


The unsloth library provides significant speedups. Please refer to the [Unsloth documentation](https://github.com/unslothai/unsloth)  for detailed installation instructions tailored to your specific CUDA version to ensure maximum performance. You might need to install a specific version of unsloth