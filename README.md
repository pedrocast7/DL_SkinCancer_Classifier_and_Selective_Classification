# DL_SkinCancer_Classifier_and_Selective_Classification
A repository with a multi-class image classification problem to train models using transfer learning and fine-tuning, conducting an analysis of each step, such as preparing the data, hyperparameter optimization, choosing a proper metric to address the problem, and finally applying selective classification for an OOD dataset. There is also a PDF to read if you want to dive more deeply into the concepts aborded here. Still, the Jupyter Notebook is divided into sections so you can follow along with the commentaries. The files' description is:

- The Pedro_Castrofinal-project-dl-skin-cancer-classifier_PAPER_APPROACH.ipynb notebook is the training and optimizations following what is done in the referred paper [Multi-class Skin Cancer Classification Architecture
Based on Deep Convolutional Neural Network](https://arxiv.org/pdf/2303.07520) where I reproduce the steps done by Mst Shapna Akter et al.
- The Pedro_Castrofinal-project-dl-skin-cancer-classifier_OPTIMIZED.ipynb is the notebook with the optimization of the models done using the balanced accuracy as goal metric, with the Selective Classification implemented too.
- Pedro_Castro_ML_Final_Project_Report.pdf is the report that you can read to dive into the concepts used a little bit more.

#### Footnote: if you get any problem loading the datasets, download it directly from the URLs below: 
- ID data: [https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)
- OOD data: [https://data.mendeley.com/datasets/zr7vgbcyr2/1](https://data.mendeley.com/datasets/zr7vgbcyr2/1)

Acknowledgments: 
- Pacheco, Andre G. C.; Lima, Gustavo R.; Salomão, Amanda S.; Krohling, Breno; Biral, Igor P.; de Angelo, Gabriel G. ; Alves Jr, Fábio  C. R. ; Esgario, José G. M.; Simora, Alana C. ; Castro, Pedro B. C. ; Rodrigues, Felipe B.; Frasson, Patricia H. L. ; Krohling, Renato A.; Knidel, Helder ; Santos, Maria C. S. ; Espírito Santo, Rachel B.; Macedo, Telma L. S. G.; Canuto, Tania R. P. ; de Barros, Luíz F. S. (2020), “PAD-UFES-20: a skin lesion dataset composed of patient data and clinical images collected from smartphones”, Mendeley Data, V1, doi: 10.17632/zr7vgbcyr2.1.
- Tschandl, P., Rosendahl, C. & Kittler, H. The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions. Sci. Data 5, 180161 doi:10.1038/sdata.2018.161 (2018).


