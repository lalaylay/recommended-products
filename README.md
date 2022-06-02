# Recommendation Product Assignment
This repository includes “Related Products” application which provides a recommended product list of related items in the cart. It is submitted to Hepsiburada Recommendation Team as data scientist assignment. This worflow explains the recommendation model with an API which retrieves products in the cart as request parameters and returns recommended Top 10 products with their scores by using Python. 

Contents
* HepsiBuradaRecommendationzip: All necessary files to run all workflow by using Python
* HepsiburadaRecommendation.ipynb: Jupyter notebook that includes all workflow about assignment

## Datasets
There are given two datasets
* events.json : add2cart events for a period of time
* meta.json : meta info of products in the events

## Dependencies
* Use 'requirements.txt' for Python requirements by running ```pip install requirement.txt```

## API usage
To be able test API, please use Postman. After running API part, you can use session id to get related link through Postman. 
