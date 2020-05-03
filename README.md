# Django Project Template
## Purpose
I'm lazy and I wanted to make template to kick-start Django projects qucikly.  
This template includes followings. 
1. Django. 
2. PostgreSQL Database. 
3. Circle CI config file (Please setup Circle CI by yourself). 
4. Docker-compose. 

## CircleCI Test Status
Dev:  [![CircleCI](https://circleci.com/gh/inuinana/data_uploader/tree/dev.svg?style=svg)](https://circleci.com/gh/inuinana/data_uploader/tree/dev)  
Master: [![CircleCI](https://circleci.com/gh/inuinana/data_uploader/tree/master.svg?style=svg)](https://circleci.com/gh/inuinana/data_uploader/tree/master)  

## How to run the app locally

$ cd docker-compose/test  
$ docker-compose build  
$ docker-compose up -d

## App can be found here 
http://0.0.0.0:8000/
