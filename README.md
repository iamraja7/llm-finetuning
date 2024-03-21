# LLM Fine-Tuning for Enhanced Dialogue Summarization and Detoxification

This repository contains two Jupyter notebooks that explore advanced fine-tuning techniques for Large Language Models (LLMs), specifically the FLAN-T5 model from Hugging Face. The goal is to enhance the model's capabilities in dialogue summarization and generate less-toxic content.

## Notebooks Overview

1. `finetune_generative_ai_model.ipynb`: Demonstrates how to fine-tune a generative AI model for dialogue summarization tasks. The notebook provides a comprehensive guide to fine-tuning the FLAN-T5 model, evaluating it with ROUGE metrics, and comparing full fine-tuning with Parameter Efficient Fine-Tuning (PEFT) methods.

2. `finetune_model_to_detoxify_summaries.ipynb`: Focuses on reducing the toxicity of the generated content. It involves fine-tuning FLAN-T5 with reinforcement learning techniques such as Proximal Policy Optimization (PPO), guided by a hate speech reward model from Meta AI.

## Objectives

- To showcase the process of fine-tuning LLMs for specific summarization tasks.
- To illustrate the ethical aspect of AI by detoxifying the generated summaries using reinforcement learning.

## Prerequisites

- An AWS account
- Access to AWS SageMaker
- Familiarity with SageMaker environments and notebook instances

## Setup

Follow the AWS documentation to set up a SageMaker notebook instance: [Amazon SageMaker Documentation](https://docs.aws.amazon.com/sagemaker/latest/dg/howitworks-create-ws.html).

Once set up, upload the notebooks to your instance and follow the instructions within to install any necessary libraries and dependencies.

## Usage

Open the AWS SageMaker notebook instance, upload the provided notebooks, and follow the in-notebook instructions to proceed with fine-tuning, and evaluate the results.

