# LLM4SE-Multilingual-Multicultural-and-Multievent-Online-Polarization
The official repository for the project of Large Language Models for Software Engineering 2025/2026

## Architectures for Subtasks
This repository contains the code and notebooks for the project 'Multilingual, Multicultural, and Multi-event Online Polarization'. The project investigates effective modeling strategies for online polarization analysis in a multilingual setting inspired by POLAR @ SemEval-2026 (Task 9). We compared multiple approaches for each subtask by implementing and evaluating different model architectures, in order to assess their effectiveness under the same experimental setting.


## Project Structure

```text
├── Dataset/
├── subtask-1/
│   ├── Architecture-1/    # XLM-RoBERTa-Base_No_LoRA + XLM-RoBERTa-Large+LoRA
│   ├── Architecture-2/    # MarianTranslate + deBERTa
│   ├── Architecture-3/    # 
├── subtask-2/
│   ├── Architecture-1/    # Two-Model_Cascade_Pipeline
│   ├── Architecture-2/    # deBERTa
│   ├── Architecture-3/    # 
```

The file ‘XLM-RoBERTa-Base_No_LoRA’ contains the training and evaluation of the model for both tasks.
