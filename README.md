# Chain-of-Discussion

### 1. Data Format

   We have released the dataset employed in our work, which contains 200 open-ended QA examples in the domain of Chinese Civil Code.

   The data file is stored by JSON format, which can be loaded directly.

   Each example includes 4 parts:
   * `question`: the texts of questions;
   * `golden_response`: the responses written by human lawyers;
   * `articles_retrieval`: five articles retrieved by a classification model (if the model does not recall correct articles, the human annotators will use the correct ones to replace part of irrevelant ones);
   * `article_labels`: whether an article should be necessary to answer the question: **0** for irrevelant, **1** for optional, and **2** for necessary.
  
### Cite
```
@misc{tao2024chainofdiscussion,
      title={Chain-of-Discussion: A Multi-Model Framework for Complex Evidence-Based Question Answering}, 
      author={Mingxu Tao and Dongyan Zhao and Yansong Feng},
      year={2024},
      eprint={2402.16313},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
