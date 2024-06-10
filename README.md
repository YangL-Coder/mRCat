# mRCat
## Title:mRCat: a Novel CatBoost Predictor of mRNA Subcellular Localization by Fusing Large Language Model Representation and Sequence Features
N4-methylcytosine (4mC) is a critical epigenetic modification that plays a pivotal role in the reg-ulation of a multitude of biological processes, including gene expression, DNA replication, and cellular differentiation. Traditional experimental methods for detecting DNA N4-methylcytosine sites are time-consuming, labor-intensive, and costly, making them unsuitable for large-scale or high-throughput research. Computational methods for identifying DNA N4-methylcytosine sites, particularly those involving machine learning and deep learning, enable rapid and cost-effective analysis of DNA 4mC sites across entire genomes without the need for extensive laboratory re-sources. In this study, we focus on the identification of DNA 4mC sites in the mouse genome. Although there are already some computational methods that can predict DNA 4mC sites in the mouse genome, there is still significant room for improvement in accurately predicting DNA 4mC sites in the mouse genome due to their inability to fully capture the multifaceted characteristics of DNA sequences. To address this issue, we propose a new deep learning predictor called Mus4mCPred, which utilizes multi-view feature learning and deep hybrid networks for accurately predicting DNA 4mC sites in the mouse genome. The predictor Mus4mCPred firstly employ different encoding methods to extract feature vectors of DNA sequences, then input these features generated by different encoding methods into various hybrid deep learning models for learning and extraction of more sophisticated representations of these features, and finally fuse the ex-tracted multi-view features to serve as the final features for DNA 4mC sites prediction in the mouse genome. Multi-view features enable a more comprehensive capture of data characteristics, enhancing the feature representation of DNA sequences. Results from ten-fold cross-validation and independent testing demonstrate that the predictor Mus4mCPred outperforms other state-of-the-art methods, achieving accurate identification of 4mC sites in the mouse genome. It has the potential to become a valuable tool for DNA 4mC prediction in the mouse genome, providing in-depth insights into the regulation of biological processes.

image

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
