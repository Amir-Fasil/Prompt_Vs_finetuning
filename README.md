#### Prompt_Vs_finetuning
https://colab.research.google.com/drive/1W1lH5qN9I6JSI84-4ihEHNAz5KMZh662?usp=sharing
#### prompting system
https://colab.research.google.com/drive/1b0JRVRf3qu-GBZKKdLR7ib97h5NtJsDp?usp=sharing

# AI Teaching Assistant:

An intelligent teaching assistant that dynamically selects prompting techniques (ReAct, Few-Shot, Zero-Shot) based on query analysis, with comparative benchmarks against fine-tuned models.

## Key Features

- **Context-Aware Routing**: Auto-selects optimal prompting technique using trigger words
- **Multi-Technique Integration**:
  - 🟢 **ReAct**: Fact verification with Wikipedia/API lookups
  - 🟣 **Few-Shot**: Class monitering and Interaction
  - 🔵 **Zero-Shot**: General Q&A fallback
- **Benchmark Suite**: Comparative analysis vs. fine-tuned models
- **Education-Optimized**: Designed for STEM accuracy and grading consistency

## Installation

- since it is colab file the reqirments are attached there

# LLM Prompting vs. Fine-Tuning Benchmark

Experimental comparison of two approaches for Hate speech classffication:
1. **Base Model (Few-Shot Prompting)**
2. **Fine-Tuned Model (Zero-Shot)**

## Key Findings

| Approach | Accuracy | Setup Cost | Inference Cost | Best For |
|----------|----------|------------|----------------|----------|
| Base Model (Zero-Shot) | 50% | $0 | Low | Rapid prototyping |
| Fine-Tuned Model (Zero-Shot) | 55%* | High | Medium | Domain consistency |
| Few-Shot Prompting | 60% | Low | High | Complex classification |

*10% improvement over base model


## Installation

- since it is colab file the reqirments are attached there
