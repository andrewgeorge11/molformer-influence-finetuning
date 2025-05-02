# MoLFormer Fine-Tuning with Influence-Based Data Selection

_ Project Overview
This project presents a complete framework for fine-tuning the MoLFormer chemical language model on the lipophilicity prediction task. It incorporates:
_Masked Language Modeling (MLM) for domain adaptation
- Influence function-based data selection to choose valuable external data
- Parameter-efficient fine-tuning (LoRA, BitFit, iA3) comparisons

##Tools & Libraries
- Hugging Face Transformers
- PyTorch
- LiSSA (for influence scores)
- scikit-learn, matplotlib, pandas
- Kaggle GPU (Tesla P100)

## Project Structure
- Notebooks: 3 tasks implemented in Jupyter notebooks
- report: Final project report (PDF)


## Key Contributions
- Achieved 6.6% reduction in MSE via influence selection
- Demonstrated LoRA as the most effective parameter-efficient method
- Identified “mononuclear cell differentiation” as top GO term in pathway analysis

## Performance Summary
| Model Variant     | MSE   | RMSE  | R²    |
|------------------|-------|-------|-------|
| Base             | 0.474 | 0.688 | 0.703 |
| MLM Fine-tuned   | 0.439 | 0.662 | 0.725 |
| Influence-Based  | 0.442 | 0.665 | 0.722 |

##  Authors
- Andrew Zaki 
- Mouhammed Yasser Soliman 
- Ahmed Hassaan 



