# OVERVIEW
This repo contains code for supervised classification based on text files and labellised pictures
Pictures labellisation is run with AWS REKO API
Model is trained with AUTOML

### steps
1. get text datas (csv) and associate with pict to build training set : 1-import-datas.ipynb
1. labellise pict (batches of 100 pict) : 2-AWS_REKO.ipynb
1. concat labels with training set : 3-concat-datas-with-AWS-labels.ipynb
1. train model and predict target : 4-predict-groupe-AutoML.ipynb