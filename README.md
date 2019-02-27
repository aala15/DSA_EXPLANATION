in different python files, you can find different ML methods in which we try to extract explanations.

in the first step, we tried to extract different histograms in order to find a ground truth. (manual_explanaitions)+evaluation

DT-On-Shuttle: the main result of the project. you can find the RFC and DT and the way that we convert the explanations to semantically meaningful explanations. +evaluation

SVM-On-Shuttle: operating linear SVM on the data set and the way that we extract and compare the results to our manual Explanations.+evaluation (in order to avoid applying the SVM again on the dataSet you can just use coefff files which contains the coefficient of each attribute after applying SVM.

macrobase: evaluating the macroBase generated expressions on shuttle.

kdd: is applying DT on KDD and evaluation

macrobase_kdd: is the evaluation of macrobase's expressions on KDD data set. 
