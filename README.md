# multi_agent_framework_experiments

## Introduction

This repository contains an experiment comparing three different AI frameworks—Microsoft AutoGen, MetaGPT, and Camel—in the context of building a classic and basic Pong game with two players in Python. The aim of this experiment is to evaluate these frameworks based on ease of customization, time taken to terminate, and overall performance.

## Experimental Setup

### Tools and Environment

The experiment was conducted using a basic Google Colab notebook for computing. The following GPT models were used:
- **Microsoft AutoGen**: `gpt-3.5-turbo`
- **MetaGPT**: `gpt-4`
- **Camel**: `gpt-4`

### Problem Statement

The problem to solve in this experiment was to "Build a classic and basic Pong game with 2 players in Python."

### Main Prompt

The main prompt used for all three frameworks was: "Build a classic and basic Pong game with 2 players in Python."

## Results

### Framework Evaluation

The following table summarizes the results of the experiment:

| Framework          | Easy to Customize (Rate from 1 —> 5) | Time to Terminate | Experiment Log Link |
|--------------------|---------------------------------------|--------------------|---------------------|
| Microsoft AutoGen  | 3                                     | 1                  | [MSAutogenPongGame.ipynb](https://github.com/sinhnguyen-sunny/multi_agent_framework_experiments/blob/main/MSAutogenPongGame.ipynb) |
| MetaGPT            | 4                                     | 2                  | [MetaGPTPongGame.ipynb](https://github.com/sinhnguyen-sunny/multi_agent_framework_experiments/blob/main/MetaGPTPongGame.ipynb) |
| Camel              | 1 (Failed)                            | 9                  | [CAMELAIPongGame.ipynb](https://github.com/sinhnguyen-sunny/multi_agent_framework_experiments/blob/main/CAMELAIPongGame.ipynb) |

### Thoughts

- **Microsoft AutoGen**: This framework was relatively easy to use and customize, earning a score of 3. It performed exceptionally well in terms of termination time, taking only 1 unit of time to complete. [Link to Experiment](https://github.com/sinhnguyen-sunny/multi_agent_framework_experiments/blob/main/MSAutogenPongGame.ipynb)

- **MetaGPT**: MetaGPT proved to be highly customizable with a rating of 4, and it terminated in a reasonable time frame with a score of 2. It demonstrated the ability to generate quality output for software development tasks. [Link to Experiment](https://github.com/sinhnguyen-sunny/multi_agent_framework_experiments/blob/main/MetaGPTPongGame.ipynb)

- **Camel**: Unfortunately, Camel faced difficulties in this experiment and received a low customization rating of 1. It also took significantly longer to

