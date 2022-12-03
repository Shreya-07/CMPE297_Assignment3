# CMPE297_Assignment3
## Part a - Implement MMoE multi task learning model from scratch for a toy example and show that it runs as intended.
## https://colab.research.google.com/drive/1wwq8NJn_vvg4hdWfhn1rrnQXwlN5iQwQ?usp=sharing

#### Description - Multi-gate Mixture-of-Experts (MMoE) explicitly learns to model task relationships from data. The Mixture-of-Experts (MoE) structure to multi-task learning is adapted by sharing the expert submodels across all tasks, while also having a gating network trained to optimize each task. 

## Part b - Implement transferlearning using head2toe technique state of art in a nice colab
## https://colab.research.google.com/drive/1G2Q4xRWVNt-LtonsyFsGSLE_-WB1imtg?usp=sharing

#### Description - Head-to-Toe probing (Head2Toe), selects features from all layers of the source model to train a classification head for the target-domain. In evaluations on the Visual Task Adaptation Benchmark, Head2Toe matches performance obtained with fine-tuning on average while reducing training but critically, for out-of-distribution transfer, Head2Toe outperforms fine-tuning.

