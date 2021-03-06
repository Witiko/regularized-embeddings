Regularized Word Embeddings in Text Classification
==================================================
Use Python 3.4+ with Pip to install the required Python packages:

    pip install -r requirements.txt

Reproducing Our Results
-----------------------
To reproduce our results, you can download all the datasets and corpora,
produce Word2Vec models and similarity matrices, and perform the evaluation.
Alternatively, you can download and visualize our result files.

### Performing Your Own Evaluation
To perform your own evaluation, you will require the following additional
tools: GNU Make, Perl 5, GNU Parallel, GNU Wget, Unzip, XZ Utils, GNU
Coreutils, and Moreutils. Execute the following command:

    dvc repro results.dvc

Open the Jupyter notebook with the experimental code to see the results:

    jupyter-notebook classification.ipynb

### Downloading and Visualizing Our Results
To download our results, execute the following command:

    dvc pull results.dvc

Open the Jupyter notebook with the experimental code to see the results:

    jupyter-notebook classification.ipynb

Citing
------
### Text

NOVOTNÝ, Vít, Eniafe Festus AYETIRAN, Michal ŠTEFÁNIK and Petr SOJKA. Text
classification with word embedding regularization and soft similarity measure.
New York, USA: Cornell University, 2020.

### BibTeX
```bib
@misc{novotny2020text,
  title = {{Text classification with word embedding regularization and soft similarity measure}},
  author = {V\'{i}t Novotn\'{y} and Eniafe Festus Ayetiran and Michal \v{S}tef\'{a}nik and Petr Sojka},
  year = 2020,
  eprint = {2003.05019v1},
  archivePrefix = {arXiv},
  primaryClass = {cs.IR},
  url = {https://arxiv.org/abs/2003.05019v1},
}
```
