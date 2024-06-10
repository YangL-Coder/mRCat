# mRCat
## Title:mRCat: a Novel CatBoost Predictor of mRNA Subcellular Localization by Fusing Large Language Model Representation and Sequence Features
The subcellular localization of messenger RNAs (mRNAs) is a pivotal aspect of biomolecules, tightly linked to gene regulation and protein synthesis, and offers innovative insights into disease diagnosis and drug development in the field of biomedicine. we propose a new machine learning-based subcellular localization predictor of mRNAs, named mRCat. This predictor initially harnesses large language models to deeply explore the implicit information within the sequence. It then amalgamates traditional sequence characteristics for a comprehensive portrayal of mRNAs gene sequences. Ultimately, it utilizes the CatBoost as the foundational classifier to predict the subcellular localization of mRNAs. The experimental validation on an independent test set demonstrates that mRCat obtains Accu-racy of 0.761, F1 score of 0.710, MCC of 0.511, AUROC of 0.751. The results indicate that our method has higher accuracy and robustness compared to other state-of-the-art methods. It is an-ticipated to offer deeper insights into biomolecular research
.<div align=center>![image](https://github.com/YangL-Coder/mRCat/assets/168099551/d80aa277-7d54-4bcd-9974-9cf91ae834f9s)
<br>
Mus4mCPred uses the following dependencies:
python 3.9
pytorch
scikit-learn
numpy
pandas

Guiding principles:
1.The folder "data" contains the datasets used in this study, including the mouse dataset and datasets from six other species.
2.The folder "feature_extract" contains all the feature encoding methods as well as information on the Word2vec pre-trained language model.
3.Data_process.py is the implementation for data reading; model.py is the implementation for the neural network model structure; train.py is the implementation for training the data with the model; test.py is the implementation for independent testing; utils.py contains information related to evaluation methods; "model_save.pth" is the final model information.

Note
This code is for the article 'Mus4mCPred: Accurate identification of DNA N4-methylcytosine sites in mouse genome using multi-view feature learning and deep hybrid network'.
