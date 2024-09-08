# Fine-Tuning LLM to Generate TextFSM Templates

This is a basic proof of concept for fine-tuning a large language model (LLM) to generate TextFSM templates based on raw text and the expected output.

The [ntc-templates](https://github.com/networktocode/ntc-templates) repository provides a collection of TextFSM templates, along with unit tests that include raw data and expected outputs. These resources serve as the foundation for this fine-tuning process.

Low-Rank Adaptation (LoRA) is used during fine-tuning to reduce memory consumption.

The code is in [textfsmllm.ipynb](textfsmllm.ipynb)
