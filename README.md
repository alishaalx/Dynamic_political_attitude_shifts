# Dynamic_political_attitude_shifts
The project is a research into the impacts of events and the changes in poltical attitude. This data analysis project is solely based on Python. 

Political attitudes are critical components of an individual’s engagement with social and political
landscapes. The catalysts for shifts in political attitudes encompasses personal experiences as well as
social events. This research delves into the changes in political attitudes due the impacts of transformative
events including the most popular Brexit as well as the pandemic virus outbreak Covid -19. In this
research, we work on a dataset created by extracting relevant features from a survey dataset (Natcen Social Research). The
datasets are then divided into two groups marking the two periods that are not impacted by the respective
events as well as well impacted by the events. For the given research, we consider the years before 2020
as an era unimpacted whereas 2020,2021 as a time period impacted by the events of Brexit and Covid-
19. It is then followed by the implementation of an Unsupervised Clustering Algorithm called K-Prototype
Clustering. It is then followed by analysing the results obtained. The Cluster evaluation is
carried out by a Classification Model.

The code files-> include optimal cluster number determination using Elbow method and Silhouette score coefficient method, implementing K-Prototype clustering followed by the evaluation of clusters  using a classification model called Light Gradient Boosting Machine.Here the attributes of evalation include distinctiveness of clusters usiing cross-vlidated f1-score and Informativeness of clusters using SHAP Summary plot.

The datasets -> the Datasets are extracted from British Social Attitude survey by NatCen Social Reserch. Here I have created the datasets by filetring the relevant survey questions. The questions are selected  based on the study conducted by  Reimer Reinsman and joffrey Evans. The datasets include 2018,2019 (pre_time period) and 2020,2021(post-timeperiod).

 
