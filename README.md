# Project 2
## Hanan Sukenik
------------------------------


- In this project, I will be using the command line to interact with Zookeeper, Kafka, Hadoop and Spark, as well as a Jupyter Notebook. I will use assessments data from an ed tech firm, publish it, manipulate it, explore it, analyze it and eventually load it into Hadoop. The goal is get the data ready ready for data scientists who work for our customers to run queries on the data

- Through this project, I will:
    * Publish and consume messages with Kafka
    * Use Spark to transform the messages so that I could land them in HDFS
    * Perform some basic analysis of the data
    
  
- The project includes several files:
    
    * project-2.ipynb - In this Jupyter Notebook, I will walk through the whole process, specify regarding any code used along the way and summarize my conclusions
    * spark_history.txt - A text file containing my Spark history
    * history.txt - A text file containing my command line history
    * docker-compose.yml - A Docker Compose .yml file used for spinning the pipeline
    * assessment-attempts-20180128-121051-nested.json - The actual data file (in json format), containing the assessments
    
    
    
 - General Notes:
 
     * While I have done all of the basic transformations and wrangling of the dataset, in order to conduct deeper analysis it will require further unwrapping of nested arrays within the dataset. Further context is within the Jupyter Notebook.
     
     
Enjoy!