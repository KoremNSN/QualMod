# Modeling Decision-Making Under Uncertainty with Qualitative Outcomes

## Overview  
Traditional decision-making models rely on **quantitative** outcomes, yet many real-world decisions involve **qualitative** choices—such as selecting a medical treatment. This study introduces a **hierarchical Bayesian model** to estimate subjective values for qualitative outcomes and assess uncertainty attitudes across domains. Our model outperforms traditional utility functions in capturing decision-making behavior, demonstrating **cross-domain consistency in ambiguity attitudes**. The findings, replicated in an independent sample, highlight the feasibility of extracting quantitative insights from qualitative decision-making.

## Key Contributions  
- Developed a **computational model** for decisions with qualitative outcomes.  
- Demonstrated that **ambiguity attitudes** are consistent across domains.  
- Outperformed **utility-based models** in predicting decision-making behavior.  
- Provided a framework for **comparing decision-making under uncertainty** in diverse contexts.  

## Files & Analysis  

### **Data Extraction & Cleaning**  
1. **`ExportSubData.ipynb`** – Extracts data from **PsychToolBox mat files**.  
2. **`CleanSubjects-Online.ipynb`** – Cleans **online sample** data.  
3. **`CleanSubjects.ipynb`** – Cleans **in-person sample** data.  

### **Main Analysis & Model Comparisons**  
4. **`MainAnalysis.ipynb`** – Runs the **core analysis** and compares models.  

### **Sensitivity & Additional Analyses**  
5. **`PriorSensCheck.ipynb`** – Checks the impact of **prior selection**.  
6. **`OrdinalSensCheck.ipynb`** – Tests sensitivity to **ordinal value assumptions**.  
7. **`SurgeryAnalysis.ipynb`** – Examines the effect of **prior surgery experience**.  
8. **`simulation_model_check.ipynb`** – Evaluates model performance through **simulated data**.  

## Citation  
If you use this repository, please cite:  

**Korem, N.,** Duek, O., Jia, R., Wertheimer, E., Metviner, S., Grubb, M., & Levy, I. (2024). Modeling Decision-Making Under Uncertainty with Qualitative Outcomes. (Accpted), PLOS Computational Biology
