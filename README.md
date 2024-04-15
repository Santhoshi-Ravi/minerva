# Enhancing Language Models’ Performance on Mathematical Datasets: A Multi-Agent Approach

## Project Overview

This project focuses on evaluating and enhancing the performance of Large Language Models (LLMs) using mathematical datasets without traditional fine-tuning methods or relying on Retrieval-Augmented Generation (RAG) techniques. Our research is geared towards improving LLMs by employing a Multi-Agent Debate Architecture and exploring various innovative strategies.

## Objectives

- To conduct a thorough benchmarking of various LLMs using a significant mathematical dataset.
- To explore the capabilities of LLMs in solving mathematical problems through innovative methodologies such as the Zero-Shot Chain-of-Thought (CoT) and Multi-Agent interactions.

## Phase 1: Initial Benchmarking and Methodology Adjustments

### Summary of Activities
- **Dataset Used**: [math-dataset](https://huggingface.co/datasets/math_dataset) from Hugging Face, approximately 5Gb in size, with about 112,559,888 question-answer pairs.
- **Models Evaluated**: Gemma 2b, Llama 7b, and Orca-mini-3b.
- **Methodology**:
  - Direct prompting of models with mathematical questions.
  - Application of the Zero-Shot Chain-of-Thought strategy to enhance structured reasoning.
  - Chain of Thought Reasoning to elucidate decision-making processes.
  - Creating Persona's and testing them

### Results
- **Performance**: Initial testing involved 1000 questions, showing varied accuracy across models. A notable finding was the improved performance under guided reasoning frameworks.
- **Revised Evaluation**: Gemma showed improved accuracy, outperforming Orca in subsequent tests.

## Phase 2: Multi-Agent Debate Architecture

### Framework Overview
- **Agent Representation**: Each LLM functions as an independent agent within a debate-style interaction framework.
- **Process**:
  - Agents receive questions and produce responses independently.
  - Responses are concatenated and analyzed by a summarization agent.
  - The summarized content is used in subsequent debate rounds to refine the decision-making process.

### Implementation
- Utilized a subset of the math-dataset for consistency(approximtely 50 data points).
- Employed quantization techniques to the LLM enhance computational efficiency.

  ## Phase 3: Multi-Agent Debate Architecture - Intra debate strategies 
- Gemma vs Gemma
- Orca vs Orca
- Multiagent communication Paradigm

## Challenges Encountered
- **Computational Limitations**: Significant challenges due to the high computational demands of the LLMs and the large size of the dataset.
- **Evaluation Complexity**: Difficulty in standardizing evaluation methods across different LLM architectures.


## Conclusion

Our research provides valuable insights into the capabilities and limitations of LLMs in handling complex mathematical reasoning tasks. The innovative methodologies employed have not only enhanced the performance of these models but also paved the way for further explorations into advanced AI interactions.

## How to Contribute

Contributors interested in advancing this research can focus on extending the methodologies, enhancing the Multi-Agent framework, or optimizing the computational efficiency of the models. For collaboration, please contact the project team via Linkedin.
