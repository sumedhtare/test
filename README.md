# Cloutavista

## Introduction

### Powered by
- [![Python3](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/) 
- [![ElasticSearch](https://img.shields.io/badge/-ElasticSearch-005571?style=for-the-badge&logo=elasticsearch)](https://www.elastic.co/)


[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)



[npm-badge]: https://img.shields.io/npm/v/react-router-dom.svg?style=flat-square
[npm]: https://www.npmjs.org/package/react-router-dom

 Cloutavista back-end services provides REST API for cloutavista.com.  
 
It’s purpose is to provide all the data collected and tagged using NLP directly from cloutavista elastic search db and further let developers write/mutate queries and add more rational data to an end point (if needed).  
  
We’ve currently implemented the following end point in this repository which can be found here

  

## Getting Started

  

### Your next steps depend on where you’re standing:

  

 - unfamilier with ES queries? -> [click here](https://www.elastic.co/guide/en/elasticsearch/reference/current/search-search.html)

- Ready to code? -> [link to repo]('')

- like to give back? -> [how to make PR]('')

- want to chat? ->[email link]('')

  

## Table of contents

  

### Intro

#### Quick start:
`Supported OS: Linux`
`Python version: 3.x.x`
- Install all the requirements
``pip install -r requirements.txt``
- Run the service
- ``gunicorn --bind 0.0.0.0:9090 run:app -k uvicorn.workers.UvicornWorker``

#### Release Notes:

- This is an initial version


#### License:
- `link`
  

### API end points  
  
  - To get all the list of endpoints make sure to run the sevice and the visit [docs]('http://localhost:9090/docs')
  and [redoc]('http://localhost:9090/redoc')
  
### Issue/Bug report template
Before reporting an issue, make sure you've searched for similar one that was already created. 


### Make Donations
- [donation link]('https://abc.com')

