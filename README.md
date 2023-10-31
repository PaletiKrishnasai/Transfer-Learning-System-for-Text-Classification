# Transfer-Learning-System-for-Text-Classification

This repository contains the codebase for prompt-based finetuning of RoBERTa-Large on a series of tasks with multiple prompts used for each task.

### Work Done:

- Optimized RoBERTa Large Language Model (LLM) performance in data-scarce environments, employing prompt-based fine-tuning strategies within a few-shot setting to enhance training efficiency and model efficacy.
- Improved the SOTA accuracy of SST2 and QNLI tasks by 1.5% and 3% respectively.
- Reduced the time taken to fine-tune by employing a few shot learning and non-parametric approach to predict label words

### How to use
- The "SRC" directory contains the required data.  The data has been prepared using the process given in [LM-BFF](https://github.com/princeton-nlp/LM-BFF#prepare-the-data) for few-shot text classification. Therefore, you can follow the same steps to prepare the data.
- Just fork the repository and run the notebook!
