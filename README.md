# Ocean Cleanup - Data Challenge 2020 at UMD



## Team member: Kai Xu, Guanyu Bao, Cheng Chang, Duotun Wang





## Abstract

According to a study conducted in collaboration with Deloitte, yearly economic costs due to marine plastic pollution are estimated to be between $6-19 billion USD. The costs mainly stem from the plastic impact on tourism, fisheries, and aquaculture. Besides, the ocean garbage will seriously affect our ecosystems and health if not cleaned up appropriately.

In order to provide cleanup suggestions for organizations, our team establishes a "4W" cleanup execution scoring model based on the collected data of ocean cleanup, presenting our inference on population activity of ocean cleanup and garbage accumulation locations by performing classical regression and correlation analysis. Also, some geographic and time series graphs are given to provide a direct sense of the current situation of ocean cleanup.
	

We further take external dataset into consideration, including multiple social and economic factors (population, education level, the development of tourism on cleanup tasks, etc.) to construct a machine-learning-based model using random forest, mainly focusing on how do those indexes affect “Total Item Collected” and other garbage-related factors. Besides, after figuring out how the ocean trash distributes, we adopt neural network model and logistic model, transferring the number of people into size 1,2,3 to serve as the dependent variable, predicting what’s the size of people we should assign given the ocean garbage information. And we try to explore reasons in some specified regions where people are more enthusiastic about ocean cleanup, which guides us to allocate human resources and to inspire people’s environmental protection sense more effectively.
	

Based on the data mining and visualization results, we have provided detailed suggestions on which type of trash should be given most focus, what cleanup operations should be performed on specified place and cleanup types (e.g., land, watercraft and underwater), and finally, what we should do to arouse people’s awareness towards ocean garbage and to call on the public to participate more in CleanSwell’s activities.



## Dataset

After [Data Cleaning](https://github.com/Duotun/UMD-Data-Challenge-2020/blob/master/Code/OceanCleanup-DataCleaning.ipynb), all the classified datasets that we use for this problem are included in [OceanCleanup - Dataset](https://github.com/Duotun/UMD-Data-Challenge-2020/tree/master/OceanCleanup%20-%20DataSet)).



## Model

We perform linear regression on the given dataset ([Model on the given data](https://github.com/Duotun/UMD-Data-Challenge-2020/blob/master/Code/DataChallenge_Model.ipynb)) and perform linear regression, random forest, and SVM to the external dataset ([Model on the external data](https://github.com/Duotun/UMD-Data-Challenge-2020/blob/master/Code/DataChallenge_Model_Externel%20DataSet.ipynb)) to make comprehensive recommendations for the ocean cleanup operations. All the statistics output could be directly seen in the uploaded Jupyter Notebooks.



## Interactive Map

We use Tableau for interactive data visualizations: [Interactive Map](https://github.com/CharlesPikachu/Games/tree/master/Game1).