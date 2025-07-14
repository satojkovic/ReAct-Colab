# ReAct-Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/satojkovic/ReAct-Colab/blob/main/hotpotqa.ipynb)

## Overview

This repository provides an easy way to try out the ReAct framework, proposed in the paper [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629), on Google Colaboratory.
Specifically, it implements a task that answers questions from the HotPotQA dataset by searching Wikipedia.

The implementation is based on the official ReAct repository: [https://github.com/ysymyth/ReAct](https://github.com/ysymyth/ReAct)

## hotpotqa.ipynb

### Overview

This Jupyter Notebook implements the ReAct framework to perform the HotPotQA task.
By iterating through `Thought`, `Action`, and `Observation` steps, the language model can reason, use tools (Wikipedia search), and derive the final answer.

### How to Run

1.  **Open in Google Colab:**
    - Click the "Open In Colab" button above to open the notebook in Google Colab.

2.  **Set API Key:**
    - Open the Secret Manager in Google Colab (the key icon in the left sidebar) and add your OpenAI API key as a new secret named `OPENAI_API_KEY`.

3.  **Run the cells:**
    - Execute the cells in order from top to bottom.
    - This will automatically install the necessary libraries, clone the required repository, and run the ReAct inference process.
