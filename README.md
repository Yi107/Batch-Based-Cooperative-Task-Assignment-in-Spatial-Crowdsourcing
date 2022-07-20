# Batch-Based-Cooperative-Task-Assignment-in-Spatial-Crowdsourcing

This repository stores the executable files of two algorithms proposed in the paper and the data set used in experiment.



## The usage of the algorithms

Executable files are provided to get the results of the algorithm.



For FT-BCTA algorithm, you can run this command in terminal: "FT-BCTA *workerdatafile* *taskdatafile* fixbatchtime *outputfilename*", where FT-BCTA is the executable file of FT-BCTA algorithm, *workerdatafile* is the file name of worker data, *taskdatafile* is the file name of task data, fixbatchtime is the fixed batching size *bs*, and *outputfilename* is the name of the output file.



For Adt-BCTA algorithm, you can run this command in terminal: "Adt-BCTA *workerdatafile* *taskdatafile* *MarkovPredictorfile* maxbatchingrange *outputfilename*", where Adt-BCTA is the executable file of Adt-BCTA algorithm,  *workerdatafile* is the file name of worker data, *taskdatafile* is the file name of task data, *MarkovPredictorfile* is the file name of MarkovPredictor, maxbatchingrange is the maximum time of batching, and *outputfilename* is the name of the output file.


After running the .exe file, you can obtain the results of algorithm in file **outputfilename**. 



## Description of the dataset

For the dataset of worker, it contains 9 parts. Id, Platform id, Radius, Apperance time, Latitude of apperance location, Longtitude of apperance location, Historical request value, Historical unit price, The distribution of historical unit price.



For the dataset of request, it contains 10 parts. Id, Platform id, Apperance time, Finishing time, Latitude of apperance location, Longtitude of apperance location, Latitude of ending location, Longtitude of ending location, Travel distance, Payment.



The real dataset used in the experiments is in folder **Real Data** and the synthetic data is in folder **Syn data**.



