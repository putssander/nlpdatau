# NLP-DATAU #

NLP Data Utilities for processing NLP-data and analyzing results.

## Notebooks ##

### Pre-processing ### 

ElasticSearch
- XML documents to ElasticSearch [link](notebooks/xlsx_template_parsing.ipynb) 
- ElasticSearch documents to Excel [link](notebooks/es_to_xlsx.ipynb)
- Prepare a dataset for doccano annotation using ElasticSearch [link](notebooks/es_to_doccano.ipynb)
- Template parsing [link](notebooks/xlsx_template_parsing.ipynb)

### Processing ### 

- Context Extraction using spaCy & pyContextNLP [link](notebooks/context_extraction.ipynb)

### Post-processing ### 

Stats
- Calculate NLP statistics over classification results in excel format [link](notebooks/xlsx_nlp_stats.ipynb)

## Dependencies ##

REQUIRED:
- docker [https://hub.docker.com/](https://hub.docker.com/) 

RECOMMENDED:
- git [https://git-scm.com/downloads](https://git-scm.com/downloads) 



## Install ##

1. Clone or download (button) this repository

    git clone https://github.com/putssander/nlp-datau.git

## Run ##
1. Navigate to the cloned or downloaded project using the terminal or cmd
    
2. Create network (if it does not exists)

        docker network create nlp-datau-network    

2. Start docker-compose

        docker-compose up
    
3. Find the Jupyter link in the log file and copy the link in the browser. 

        jupyter-nlp-datau             | [I 12:06:45.669 NotebookApp]  or http://127.0.0.1:8888/?token=0c01e853a34a4bb0db3a542ca15c3af036cab7a11fd64bb2

6. Navigate to the desired notebook in the browser (directory notebooks)

7. Data can be copied to the resources/data folder (needs to be created)
