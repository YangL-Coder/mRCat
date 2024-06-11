# mRCat
## Title:mRCat: a Novel CatBoost Predictor of mRNA Subcellular Localization by Fusing Large Language Model Representation and Sequence Features
The subcellular localization of messenger RNAs (mRNAs) is a pivotal aspect of biomolecules, tightly linked to gene regulation and protein synthesis, and offers innovative insights into disease diagnosis and drug development in the field of biomedicine. we propose a new machine learning-based subcellular localization predictor of mRNAs, named mRCat. This predictor initially harnesses large language models to deeply explore the implicit information within the sequence. It then amalgamates traditional sequence characteristics for a comprehensive portrayal of mRNAs gene sequences. Ultimately, it utilizes the CatBoost as the foundational classifier to predict the subcellular localization of mRNAs. The experimental validation on an independent test set demonstrates that mRCat obtains Accu-racy of 0.761, F1 score of 0.710, MCC of 0.511, AUROC of 0.751. The results indicate that our method has higher accuracy and robustness compared to other state-of-the-art methods. It is an-ticipated to offer deeper insights into biomolecular research
.<div align=center>![image](https://github.com/YangL-Coder/mRCat/assets/168099551/d80aa277-7d54-4bcd-9974-9cf91ae834f9s)</div>
## mRCat uses the following dependencies:<br>
python: 3.9<br>
pandas: 1.4.4<br>
sklearn: 1.0.2<br>
numpy: 1.21.5<br>
matplotlib: 3.4.3<br>
## How to Use the Code in Jupyter (iPython) Notebooks:<br>
1.Clone the Repository:<br>
  First, clone the repository to your local machine. Open your terminal or command prompt and run the following command:<br>
  ```git clone https://github.com/YangL-Coder/mRCat.git<br>
## Guiding principles:<br>
1.The folder "data" contains the datasets used in this study, including Training and Testing Set.The mRNA_sublocation_TrainingSet_NC-BERTdata.csv file in the TrainingSet folder is the sequence training set features. The mRNA_sublocation_TestSet_NC-BERTdata.csv file in the TestSet folder is the sequence test set features. The remaining csv files are the process data files for constructing the training set and the test set.<br>
2.The folder "result" contains the results produced by the experimental process in this study.<br>
3.IPYNB file, CV_violin_plots, DocProcess is the code for data preprocessing and visualization, mRNA_sublocation_TestSet_EIIP, mRNA_sublocation_TestSet-DNABERT, mRNA_sublocation_TrainingSet-DNABERT, mRNA_sublocation_TrainingSet_EIIP are the codes for feature extraction of sequences,and the remaining IPYNB files focus on training models by combining various features with different base classifiers.<br>
## Note:<br>
This code is for the article 'mRCat: a Novel CatBoost Predictor of mRNA Subcellular Localization by Fusing Large Language Model Representation and Sequence Features'.
