# Fine-Tuning-GPTs

## Introduction
Not every organization will have the resources or capability to build a large language model from scratch due to the extensive dataset and computational requirements involved in the process

We believe that Model as a Service will become the standard in the industry, and that the most effective way to improve already trained large language models (LLMs) with over 100 billion parameters will be through fine-tuning

In this context, we propose an optimized method for fine-tuning Large LLM with a high accuracy rate on a limited amount of training data, which is known as few-shot learning


This is a project using transfer learning to fine tune GPT3 Language Model. With low amount of data, we are efficiently fine tuning the model based on a specific task. We also explore a cost effective way for training. 

## Workflow
We implement transfer learning strategy for fine tuning a GPT-3 model to work on script generation for a language model.

To optimize the performance of the model, we have experimented with different values for epochs, batch size, and learning rate during the fine-tuning process. By altering these parameters, we were able to determine which combination yields the best results.

We were able to successfully train the model with only a small amount of training and validation data.

We propose a strategy to lower the cost of GPT-3 while maintaining its high quality.

## Architecture

![hpml drawio (1)](https://user-images.githubusercontent.com/64778259/208584100-9d38a668-04b2-4793-b2e5-d3425a854533.png)

