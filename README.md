# Predictive-analysis-for-Precision-Farming
This repository contains all the work had been done in **ONE LAB Egypt** Descriptive analysis on PA using ML internship.
The general scope of the proposed project lies in the field of agricultural development by using green electromagnetic-based techniques. In particular, the project focuses on the early prediction and control of the harmful green field living organisms by using **Machine Learning** models that capable to predict the numbers and conditions of these organisms then control the quasi-stationary magnetic fields. In this project, we target 
##### The eggs of cotton leaf worm, scientifically known as Spodoptera littoralis.
<img src="https://www.sciencesource.com/Doc/TR1_WATERMARKED/7/4/8/e/SS2363319.jpg?d63642015363" width="250" height="200">

##### Potato Blight.
<img src="https://www.quickcrop.ie/blog/wp-content/uploads/2013/09/Potato-blight-on-leaf.jpg" width="250" height="200"> <img src="https://cdn.britannica.com/17/171817-050-BF8C19FA/blight-plant-disease-water-mold-Phytophthora-infestans.jpg" width="250" height="200">
                                                                                                                      
##### Guava trees  seasonal abundance of mealybug species and its associated predators and parasitoid .  
<img src="https://www.vnrnursery.in/wp-content/uploads/2017/04/MB2.jpg" width="250" height="200">

### abstract
------------
Traditional ways of farming are no longer suitable for early and accurate detection of biotic stress. Recently, precision agriculture has been extensively used as a potential solution for agriculture problems using high resolution sensors and data analysis.
In this paper, several methods of machine learning have been utilized in order to study pests' population, and agricultural conditions for some crops such as potatoes, guava, and cotton, which are among the main Egyptian crops.

### Dataset and setup
The datasets used in this work for guava trees, cotton leafworm are a research study by Dr. Haitham Sharaf a professor at Cairo University, faculty of Agriculture, which contains data of weather conditions inside a controlled greenhouse system where Guava trees, cotton are planted.

Seasonal abundance of mealybug species and their associated predators and parasitoid on guava trees in Egypt have been surveyed. The survey has been conducted in Giza, Egypt spanning two years (Jan. 2014 to Dec. 2015). Fifteen plants have been randomly chosen and five leaves have been biweekly collected, Each leave has been picked either from the middle of the inspected trees or the four cardinal directions.The dataset includes `four pest mealybug species`, `four predator species`, `two parasitoids attack predators`, `four primary parasitoid species`, and `one hyper parasitoid`

The most dominant insect species are: `the mealybug Ferrisia virgata`, `the predator Scymnus syriacus`, `the parasitoid` that attacks  `Homalotylus vicinus`, `the primary parasitoid of mealybugs`, and `the hyperparasitoid`, `Chartocerus subaeneus.F.virgata` is the first recorded insect on guava trees in Egypt and the primary parasitoid Aenasius spieces is recorded for the first time in the Egyptian guava harvest. Based on the present study, it is clear that the surveyed natural enemies have played a weak role in controlling the mealybugs attacking guava trees, due to the effect of the parasitoids attacking predators and the hyperparasitoids. It is found that the role played by these bio-agents could have been of great importance in the process of predictive analysis and studying the relationship between these insects to accurately help reduce the harmful effect of insects or parasites that cannot be overcome by other insects.Consequently, in finding the correlation and statistical distribution between insects, some of which were among the most important factors for conducting a good predictive analysis.

### methods
Several methods of machine learning have been utilized for these analyses such as support vector machines ,Decision Tree, Random Forest, Gradient Boosting algorithms for classification (supervised learning); k-means and self-organizing maps for clustering (unsupervised learning). These methods are able to calculate both linear and non-linear models, require few statistical assumptions and adapt flexibly to a wide range of data characteristics.
The collected dataset includes the insects popularity on a biweekly basis, meanwhile the weather data is available on a daily basis. Thus some preprocessing on the data has to be done to make use of the available daily weather data.Here, unsupervised learning techniques played the solution to predict the relationship between climatic and soil features and population of insects.
Mainly two methods have been used: predicting the numbers of each insect separately on a daily basis, and predicting the numbers of all insects simultaneously together on a daily basis as well. In each of these methods one or a combination of the following techniques have been applied: `linear interpolation`, `data imputation` using `mean/median value`, data imputation using `KNN` , `k-fold cross-validation`, `standard scaler`, and `min-max scaler`
