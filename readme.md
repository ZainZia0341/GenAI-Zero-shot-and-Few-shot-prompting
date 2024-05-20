# Generative AI Use Case: Dialogue Summarization

Welcome to this practical course module! Here, we'll delve into dialogue summarization using generative AI. You'll discover how the input text shapes the model's output and learn about prompt engineering to guide it for specific tasks. By comparing zero-shot, one-shot, and few-shot inferences, you'll take the first steps towards prompt engineering and witness how it can improve the generative output of Large Language Models (LLMs).

## Table of Contents:

- [Set up Kernel and Required Dependencies](#1---set-up-kernel-and-required-dependencies)
- [Summarize Dialogue without Prompt Engineering](#2---summarize-dialogue-without-prompt-engineering)
- [Summarize Dialogue with an Instruction Prompt](#3---summarize-dialogue-with-an-instruction-prompt)
  - [Zero Shot Inference with an Instruction Prompt](#zero-shot-inference-with-an-instruction-prompt)
  - [Zero Shot Inference with FLAN-T5 Prompt Template](#zero-shot-inference-with-flan-t5-prompt-template)
- [Summarize Dialogue with One Shot and Few Shot Inference](#4---summarize-dialogue-with-one-shot-and-few-shot-inference)
  - [One Shot Inference](#one-shot-inference)
  - [Few Shot Inference](#few-shot-inference)
- [Generative Configuration Parameters for Inference](#5---generative-configuration-parameters-for-inference)

## 1 - Set up Kernel and Required Dependencies:

Ensure the correct kernel is selected and install necessary packages for PyTorch, Hugging Face transformers, and datasets.

## 2 - Summarize Dialogue without Prompt Engineering:

Generate summaries of dialogues using the FLAN-T5 model without prompt engineering. Display sample dialogues and their human-written summaries alongside model-generated summaries.

## 3 - Summarize Dialogue with an Instruction Prompt:

Explore prompt engineering by providing an instruction prompt to guide the model. Compare zero-shot inferences with and without using a FLAN-T5 prompt template.

### Zero Shot Inference with an Instruction Prompt

### Zero Shot Inference with FLAN-T5 Prompt Template

## 4 - Summarize Dialogue with One Shot and Few Shot Inference:

Experiment with one-shot and few-shot inferences to provide the model with examples before generating summaries. Observe how adding context influences the model's output.

### One Shot Inference

### Few Shot Inference

## 5 - Generative Configuration Parameters for Inference:

Adjust generation configuration parameters such as max_new_tokens, do_sample, and temperature to observe their impact on the model's output during inference.

Prompt engineering significantly enhances the model's ability to summarize dialogues effectively. Understanding and manipulating these parameters can lead to more accurate and contextually relevant summaries. Let's dive in!
