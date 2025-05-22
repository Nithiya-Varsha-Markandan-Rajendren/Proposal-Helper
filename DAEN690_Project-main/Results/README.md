# Results Folder Documentation

This document provides an overview of the evaluation and analysis results stored in this directory. The files and folders here represent our test-driven development and scoring methodology, applied to multiple large language models (LLMs) answering 31 example questions provided by Allwyn.

## Folder Overview

### 📁 LLMsAnswerForEachModel
This folder contains the raw JSON outputs of different LLMs responding to test questions. These are the primary sources for evaluation and scoring.

### 📁 Context&Resource
This folder contains the reference context used to evaluate LLM answers. It includes source texts from original project documents, annotated with project names. These references help determine whether the model’s answers are factually grounded and contextually accurate.

### 📁 Kendra_TestResults
This folder stores the results from Kendra-based retrievals for comparison with LLM-generated answers. These are useful for validating whether LLM responses align with retrieval-based answers.

### 📁 scored_results
This folder contains the evaluation scores assigned to each LLM's answers. Scores range from 0 to 2:
- **0** = Completely incorrect  
- **1** = Partially correct  
- **2** = Fully correct  

Each answer was assessed based on three criteria:
1. **Relevance** – Did it answer the user's question?
2. **Specificity** – Did it state the correct project/source?
3. **Usefulness** – Is the response appropriate for inclusion in a proposal?

Initial evaluations revealed that **Claude** had the best overall average scores, while **Jamba** provided the most factually correct answers. Prompt refinement using test-driven development led to performance improvements exceeding **50%** in some cases.

### 📁 Visualization
This folder contains visual representations of model performance, generated from the scored results. It includes comparison charts between models and prompts.

## Summary

This folder represents a comprehensive evaluation pipeline for assessing LLM effectiveness in answering proposal-related questions with reference to project documentation. The combination of structured scoring, contextual verification, and visual analytics supports a rigorous comparison across LLMs and prompt strategies.
