<!-- Banner Image -->
<img src="https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdevnotebooks.png" width="100%">

<!-- Links -->
<p align="center">
  <a href="https://console.brev.dev" style="color: #06b6d4;">Console</a> •
  <a href="https://brev.dev" style="color: #06b6d4;">Docs</a> •
  <a href="/" style="color: #06b6d4;">Templates</a> •
  <a href="https://discord.gg/NVDyv7TUgJ" style="color: #06b6d4;">Discord</a>
</p>

[![Static Badge](https://img.shields.io/badge/Open_In-AI_Workbench-76B900)](https://ngc.nvidia.com/open-ai-workbench/aHR0cHM6Ly9naXRodWIuY29tL2p0Y2FzYWJsYW5jYS9icmV2LW5vdGVib29rcy1haXdi)

# Brev.dev Notebooks

This repo contains helpful AI/ML notebook templates for LLMs, multi-modal models, image segmentation, and more. Each notebook has been coupled with the minimum GPU specs required to use them along with a 1-click deploy badge that starts each notebook on a GPU.

## Contributing

We welcome contributions to this repository! If you have a notebook you'd like to add, please reach out to use the [Discord](https://discord.gg/y9428NwTh3) or open a pull request!

## Notebooks

We've split the notebooks into categories based on the type of task they're designed for. Our current split is: LLM finetuning/training, multi-modal models, computer vision/image segmentation, and miscellaneous. Let us know if you want to see more notebooks for a certain task or using different frameworks and tools!

### LLM Finetuning/Training

| Notebook                                                                                                                       | Description                                               | Min. GPU | Deploy                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| ------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Fine-tune Llama3 using Direct Preference Optimization](https://github.com/brevdev/notebooks/blob/main/llama3dpo.ipynb)        | Fine-tune Llama3 using DPO                                | 1x A100  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/llama3dpo.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/llama3dpo)                                                                                                                                                                                    |
| [Fine-tune Llama3 using SFT](https://github.com/brevdev/notebooks/blob/main/llama3_finetune_inference.ipynb)                   | Fine-tune and deploy Llama 3                              | 2x A100  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/llama3_finetune_inference.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/llama3_finetune_inference)                                                                                                                                                    |
| [Fine-tune Llama 2](https://github.com/brevdev/notebooks/blob/main/llama2-finetune.ipynb)                                      | A Guide to Fine-tuning Llama 2                            | 1x A10G  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/llama2-finetune.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/llama2-finetune) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=lPLrODJjHUE)                     |
| [Fine-tune Llama 2 - Own Data](https://github.com/brevdev/notebooks/blob/main/llama2-finetune-own-data.ipynb)                  | Fine-tune Llama 2 on your own dataset                     | 1x A10G  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/llama2-finetune-own-data.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/llama2-finetune-own-data) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=lPLrODJjHUE)   |
| [Fine-tune Mistral](https://github.com/brevdev/notebooks/blob/main/mistral-finetune.ipynb)                                     | A Guide to Fine-tuning Mistral                            | 1x A10G  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/mistral-finetune.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/mistral-finetune)                                                                                                                                                                      |
| [Fine-tune Mistral using NVIDIA NeMO and PEFT](https://github.com/brevdev/notebooks/blob/main/mistral-finetune-nemo.ipynb)     | Fine-tune Mistral using NVIDIA NeMO and PEFT              | 1x A100  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/mistral-finetune-nemo.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/mistral_nemo_finetune)                                                                                                                                                            |
| [Fine-tune Mistral - Own Data](https://github.com/brevdev/notebooks/blob/main/mistral-finetune-own-data.ipynb)                 | Fine-tune Mistral on your own dataset                     | 1x A10G  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/mistral-finetune-own-data.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/mistral-finetune-own-data) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=kmkcNVvEz-k) |
| [Fine-tune Mixtral (8x7B MoE)](https://github.com/brevdev/notebooks/blob/main/mixtral-finetune.ipynb)                          | A Guide to Fine-tuning Mixtral, Mistral's 8x7B MoE        | 4x T4    | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/mixtral-finetune.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/mixtral-finetune-own-data) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=zbKz4g100SQ)          |
| [Fine-tune Mixtral (8x7B MoE) - Own Data](https://github.com/brevdev/notebooks/blob/main/mixtral-finetune-own-data.ipynb)      | A Guide to Fine-tuning Mixtral on your own dataset        | 4x T4    | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/mixtral-finetune-own-data.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/mixtral-finetune-own-data)                                                                                                                                                    |
| [Fine-tune BioMistral](https://github.com/brevdev/notebooks/blob/main/biomistral-finetune.ipynb)                               | A Guide to Fine-tuning BioMistral                         | 1x A10G  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/biomistral-finetune.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=biomistral-finetune&file=https://github.com/brevdev/notebooks/raw/main/biomistral-finetune.ipynb&python=3.10&cuda=12.0.1)                       |
| [Fine-tune Phi-2](https://github.com/brevdev/notebooks/blob/main/phi2-finetune.ipynb)                                          | A Guide to Fine-tuning Phi-2                              | 1x A10G  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/phi2-finetune.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/phi2-finetune-own-data) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=t55XrJddjLA)                |
| [Fine-tune Phi-2 - Own Data](https://github.com/brevdev/notebooks/blob/main/phi2-finetune-own-data.ipynb)                      | Fine-tune Phi-2 on your own dataset                       | 1x A10G  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/phi2-finetune-own-data.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/phi2-finetune-own-data) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=t55XrJddjLA)       |
| [Training Question/Answer models using NVIDIA NeMo](https://github.com/brevdev/notebooks/blob/main/question_answer_nemo.ipynb) | Use NeMo to train BERT, GPT, and S2S models for Q&A tasks | 1x A10G  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/question_answer_nemo.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/question_answer_nemo)                                                                                                                                                              |

### LLM Inference/Deployment

| Notebook                                                                                                           | Description                                                   | Min. GPU | Deploy                                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Run inference on Llama3 using TensorRT-LLM](https://github.com/brevdev/notebooks/blob/main/tensorrt-llama3.ipynb) | Run inference on Llama3 using TensorRT-LLM                    | 1x A10G  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/tensorrt-llama3.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/llama3-tensorrtllm-deployment)                                                                                                         |
| [Inference on DBRX with VLLM and Gradio](https://github.com/brevdev/notebooks/blob/main/dbrx_inference.ipynb)      | Run inference on DBRX with VLLM and Gradio                    | 4x A100  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/deploy-to-replicate.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebooks/dbrx_inference)                                                                                                                   |
| [Run BioMistral](https://github.com/brevdev/notebooks/blob/main/biomistral.ipynb)                                  | Run BioMistral                                                | 1x A10G  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/biomistral.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=biomistral&file=https://github.com/brevdev/notebooks/raw/main/biomistral.ipynb&python=3.10&cuda=12.0.1) |
| [Run Llama 2 70B](https://github.com/brevdev/notebooks/blob/main/llama2-finetune-own-data.ipynb)                   | Run Llama 2 70B, or any Llama 2 Model                         | 4x T4    | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/llama2.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebooks/llama2-finetune-own-data)                                                                                                                      |
| [Use TensorRT-LLM with Mistral](https://github.com/brevdev/notebooks/blob/main/tensorrt_mistral.ipynb)             | Use NVIDIA TensorRT engine to run inference on Mistral-7B     | 1x A10G  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/tensorrt_mistral.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/trtmistral1)                                                                                                                          |
| [StreamingLLM for Optimized Inference](https://github.com/brevdev/notebooks/blob/main/streamingllm-tensorrt.ipynb) | Use StreamingLLM for infinite length input without finetuning | 1x A10G  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/streamingllm-tensorrt.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/streamingllm-tensorrt-llm)                                                                                                       |

### Multi-modal and Computer Vision Models

| Notebook                                                                                                                       | Description                                          | Min. GPU | Deploy                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------- | -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Finetune and deploy LlaVA](https://github.com/brevdev/notebooks/blob/main/llava-finetune.ipynb)                               | Finetune the LlaVA model on your own data            | 1x A10G  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/llava-finetune.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/llava-finetune) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=XICHJx2_Rm8)                         |
| [AUTOMATIC1111 Stable Diffusion WebUI](https://github.com/brevdev/notebooks/blob/main/automatic1111-stable-diffusion-ui.ipynb) | Run Stable Diffusion WebUI, AUTOMATIC1111            | 1x A10G  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/stable-diffusion-ui.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/automatic1111-stable-diffusion-ui) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=Sf6PwCz6fbI) |
| [ControlNet on AUTOMATIC1111](https://github.com/brevdev/notebooks/blob/main/controlnet.ipynb)                                 | Run ControlNet Models on Stable Diffusion WebUI      | 1x A10G  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/controlnet.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/controlnet)                                                                                                                                                                                    |
| [SDXL inference with LoRA and Diffusers](https://github.com/brevdev/notebooks/blob/main/diffusion_lora_inference.ipynb)        | Run inference using LoRA adaptors and SDXL           | 1x A10G  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/diffusion_lora_inference.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/diffusion_lora_inf)                                                                                                                                                              |
| [Oobabooga LLM WebUI](https://github.com/brevdev/notebooks/blob/main/oobabooga.ipynb)                                          | Run Oobabooga, the LLM WebUI (like AUTOMATIC1111)    | 1x A10G  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/oobabooga.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/oobabooga)                                                                                                                                                                                      |
| [EfficientViT Segement Anything](https://github.com/brevdev/notebooks/blob/main/efficientvit-segmentation.ipynb)               | Run a TensorRT optimized version of Segment Anything | 1x A10G  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/efficientvit-segmentation.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/efficientvit-segmentation)                                                                                                                                                      |

### Other applications and tools

| Notebook                                                                                                               | Description                                 | Min. GPU     | Deploy                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ---------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- | ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Deploy to Replicate](https://github.com/brevdev/notebooks/blob/main/deploy-to-replicate.ipynb)                        | Deploy Model to Replicate                   | any \|\| CPU | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/deploy-to-replicate.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/deploy-to-replicate) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=eczHFcqx1ic) |
| [GGUF Export FT Model](https://github.com/brevdev/notebooks/blob/main/gguf-export.ipynb)                               | Export your fine-tuned model to GGUF        | 1x A10G      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/gguf-export.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/gguf-export)                                                                                                                                                                    |
| [Julia Install](https://github.com/brevdev/notebooks/blob/main/julia-install.ipynb)                                    | Easily Install Julia + Notebooks            | any \|\| CPU | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/julia-install.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/julia-install)                                                                                                                                                                |
| [PDF Chatbot (OCR)](https://github.com/brevdev/notebooks/blob/main/ocr-pdf-analysis.ipynb)                             | PDF Chatbot using OCR                       | 1x A10G      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/ocr-pdf-analysis.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebooks/ocr-pdf-analysis)                                                                                                                                                         |
| [Zephyr Chatbot](https://github.com/brevdev/notebooks/blob/main/zephyr-chatbot.ipynb)                                  | Chatbot with Open Source Models             | 1x A10G      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/zephyr-chatbot.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/zephyr-chatbot)                                                                                                                                                              |
| [Accelerate Data Science using NVIDIA RAPIDS](https://github.com/brevdev/notebooks/blob/main/rapids_cudf_pandas.ipynb) | Accelerate Data Science using NVIDIA RAPIDS | 1x A10G      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/rapids_cudf_pandas.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/rapids_cudf_pandas)                                                                                                                                                      |
| [Accelerate Data Science using NVIDIA RAPIDS](https://github.com/brevdev/notebooks/blob/main/rapids_cudf_pandas.ipynb) | Accelerate Data Science using NVIDIA RAPIDS | 1x A10G      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/rapids_cudf_pandas.ipynb) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-dark.svg)](https://console.brev.dev/notebook/rapids_cudf_pandas) [![ Click here to deploy.](https://brev-assets.s3.us-west-1.amazonaws.com/nv-lb-light.svg)](https://console.brev.dev/notebook/rapids_cudf_pandas)    |

---

### What is Brev.dev?

Brev is a dev tool that makes it really easy to code on a GPU in the cloud. Brev does 3 things: provision, configure, and connect.

#### Provision:

Brev provisions a GPU for you. You don't have to worry about setting up a cloud account. We have solid GPU supply, but if you do have AWS or GCP, you can link them.

#### Configure:

Brev configures your GPU with the right drivers and libraries. Use our open source tool Verb to point and click the right python and CUDA versions.

#### Connect:

Brev.dev CLI automatically edits your ssh config so you can `ssh gpu-name` or run `brev open gpu-name` to open VS Code to the remote machine
