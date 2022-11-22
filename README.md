# Get_UniRep64features
This repository is meant for analyzing deep sequence data to generate two kinds of simple linear discriminant analysis (LDA) machine learning model: OneHot LDA model and UniRep LDA model.

The OneHot LDA model (in-library) for Pareto optimization was first developed by  Emily K. Makowski and et al. from Michigan university in the paper entitled "Co-optimization of therapeutic antibody affinity and specificity using machine learning models that generalize to novel mutational space", https://github.com/Tessier-Lab-UMich/Emi_Pareto_Opt_ML/blob/main/onehot_models.py.--> in-library analysis.

The UniRep LDA model (out-library) for predicting variants outside the Pareto frontier (novel mutations that have not seen in the deep sequencing library) was achieved by first extracting the deep learning features (UniRep) learnt from input deep sequencing data containing a list of VHH sequences in .txt format. The codes for UniRep was belong to https://github.com/churchlab/UniRep.

