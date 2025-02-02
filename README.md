# TOPSIS Method for Selecting the Best Pretrained Model for Text Classification

## Overview
This project implements the **TOPSIS** method to evaluate and rank pretrained models for text classification based on multiple performance criteria.

## 1. Models and Evaluation Criteria
The following pretrained models are evaluated:
- **DistilBERT**
- **RoBERTa**
- **ALBERT**
- **BERT**
- **XLNet**

The criteria for evaluation include:
- **Accuracy** (Higher is better)
- **F1-score** (Higher is better)
- **Inference Time** (Lower is better)
- **Model Size** (Lower is better)

## 2. Implementation Steps
The **TOPSIS method** is applied using the following steps:
1. **Normalization** of the decision matrix.
2. **Weighted normalization** of the decision matrix.
3. **Calculation of ideal best and worst solutions**.
4. **Distance computation** from the ideal solutions.
5. **Calculation of TOPSIS scores** for each model.
6. **Ranking of models** based on the scores.

**Decision Matrix**
![image](https://github.com/sidak32/Topsis_PreTrainedModel_TextClassification/blob/main/Decision%20Matrix.png)

## 3. Code Execution
The implementation is provided in the Python script: `Topsis_PreTrained_Models_Text_Classification.ipynb`.

## 4. Results
### Final Rankings:
![image](https://github.com/sidak32/Topsis_PreTrainedModel_TextClassification/blob/main/Topsis_Ranking.png)

### Visualization:
![image](https://github.com/sidak32/Topsis_PreTrainedModel_TextClassification/blob/main/Visualization_Topsis.png)

## 5. Conclusion
Using the **TOPSIS method**, we effectively ranked pretrained models for text classification based on multiple criteria, providing a systematic approach for model selection.

