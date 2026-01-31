# LLM4SE-Multilingual-Multicultural-and-Multievent-Online-Polarization
The official repository for the project of Large Language Models for Software Engineering 2025/2026

## About the repository
This repository contains the code and notebooks for the project 'Multilingual, Multicultural, and Multi-event Online Polarization'. The project investigates effective modeling strategies for online polarization analysis in a multilingual setting inspired by POLAR @ SemEval-2026 (Task 9). We compared multiple approaches for each subtask by implementing and evaluating different model architectures, in order to assess their effectiveness under the same experimental setting.

## Project Structure

```text
├── Dataset/
│   ├── Subtask-1/
│   │   ├── original/      # original data from the challenge
│   │   ├── translated/    # translated data for the architecture 2
│   ├── Subtask-2/
│   │   ├── original/      # original data from the challenge
│   │   ├── translated/    # translated data for the architecture 2 and 3
├── subtask-1/
│   ├── Architecture-1/    # XLM-RoBERTa-Base_No_LoRA + XLM-RoBERTa-Large+LoRA
│   ├── Architecture-2/    # MarianTranslate + deBERTa
├── subtask-2/
│   ├── Architecture-1/    # Two-Model_Cascade_Pipeline
│   ├── Architecture-2/    # deBERTa
│   ├── Architecture-3/    # LlamaArch3_q4bit
```

The file ‘XLM-RoBERTa-Base_No_LoRA’ contains the training and evaluation of the model for both tasks.
The file ‘LlamaArch3_q4bit’ contains the training and evaluation of the model for both tasks.
