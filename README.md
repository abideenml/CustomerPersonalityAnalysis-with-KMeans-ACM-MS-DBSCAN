# Customer Personality Analysis with K-Means, Agglomerative, Mean Shift and Density-based Spatial Clustering 

In this project, I have aggregated data of a grocery store and applied exploratory data analysis on it   to understand it. We can observe the effect of major features as shown below:



<p align="center">
<img src="readme_pics/Pipeline.png" width="700"/>
</p>


## Table of Contents
  * [What is Customer Personality Analysis?](#what-is-customer-personality-analysis?)
  * [Clustering Techniques](#clustering-techniques)
  * [Data Workflow](#data-workflow)
  * [Observations](#observations)
  * [Setup](#setup)
  * [Todos](#todos)
  * [Acknowledgements](#acknowledgements)
  * [Citation](#citation)
  * [Connect with me](#connect-with-me)

  <br>


## What is Customer Personality Analysis?



## Clsutering Techniques



## Data Workflow

![Effect of important features](https://user-images.githubusercontent.com/89645252/187375749-2a8be0d8-2778-4699-9c46-219a5d067bac.png)

Correlation matrix:

![Correlation matrix](https://user-images.githubusercontent.com/89645252/187375975-dc391af6-ca8e-4210-8144-f5ebdd8a7c45.png)

Then i applied Elbow method to find the number of optimal clusters.

![Elbow method](https://user-images.githubusercontent.com/89645252/187374550-c55ffb03-ab8b-4096-b730-5d5474faf5a5.png)

 I have also applied Principal component analysis before applying any model. The data looks something like this if we visualize it in 3D space:
 
 ![3D Projection after Principal Component Analysis](https://user-images.githubusercontent.com/89645252/187375490-1679b2a6-838a-43e8-ab27-b5a688c81bc3.png)


After that I have applied Complete Agglomerative clustering with 4 clusters:

![Agglomerative clustering Complete results](https://user-images.githubusercontent.com/89645252/187375086-b85059ff-56a2-4890-acc0-b41f2d4c431e.png)

Average Agglomerative clustering with 4 clusters:

![Agglomerative clustering Average results](https://user-images.githubusercontent.com/89645252/187375250-da78501c-0564-474e-9657-873eb088f33b.png)

K-Means clusters: 

![K-mean results](https://user-images.githubusercontent.com/89645252/187376272-7fe93c76-14a4-483b-9489-38d4629a4154.png)

Mean-shift clusters:

![Mean Shift results](https://user-images.githubusercontent.com/89645252/187376389-2e2af825-7bc6-4c14-a444-407b8f8b71a4.png)

Density based Spatial Clustering:

![DBSCAN results](https://user-images.githubusercontent.com/89645252/187376619-48c0bb52-c3b5-4f42-88f6-1be1230f3c14.png)

## Observations

In the end, I have concluded with the following observations from the complete Agglomerative Clustering that:

Cluster 0 are parents who have arounf 2 to 4 members in family and single parents are also included in this. This cluster consists of relatively older people.

Cluster 1 are not parents. They are high income people with max 2 members in family and they span all ages.

Cluster 2 are parents and are relatively younger with only one child. At max, there are 3 members in family.

Cluster 3 are parents but are lower income group. They have max 5 people and min 3 people in family.




## Setup

So we talked about what telephone based social engineering attacks are, and what they can do for you (among other things). <br/>
Let's get this thing running! Follow the next steps:

1. `git clone https://github.com/abideenml/CustomerPersonalityAnalysis-with-KMeans-ACM-MS-DBSCAN`
2. Navigate into project directory `cd path_to_repo`
3. Create a new venv environment and run `pip install -r requirements.txt`
4. Run the `Clustering.ipynb` file.

That's it! <br/>





## Todos:

Finally there are a couple more todos which I'll hopefully add really soon:
* Explore how these clustering models perform on huge amounts of data.
* Productionize these models to get weekly reports regarding the customers.






## Acknowledgements

I found these resources useful (while developing this one):

* [Clustering | Introduction, Different Methods, and Applications](https://www.analyticsvidhya.com/blog/2016/11/an-introduction-to-clustering-and-different-methods-of-clustering/)
* [Understanding Mean Shift Clustering and Implementation with Python](https://towardsdatascience.com/understanding-mean-shift-clustering-and-implementation-with-python-6d5809a2ac40)




## Citation

If you find this code useful, please cite the following:

```
@misc{Zain2023CustomerPersonalityAnalysis,
  author = {Zain, Abideen},
  title = {customer-personality-analysis},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/abideenml/CustomerPersonalityAnalysis-with-KMeans-ACM-MS-DBSCAN}},
}
```

## Connect with me

If you'd love to have some more AI-related content in your life :nerd_face:, consider:

* Connect and reach me on [LinkedIn](https://www.linkedin.com/in/zaiinulabideen/) and [Twitter](https://twitter.com/zaynismm)
* Follow me on 📚 [Medium](https://medium.com/@zaiinn440)
* Subscribe to my 📢 weekly [AI newsletter](https://rethinkai.substack.com/)!

## Licence

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/abideenml/CustomerPersonalityAnalysis-with-KMeans-ACM-MS-DBSCAN/blob/master/LICENCE)