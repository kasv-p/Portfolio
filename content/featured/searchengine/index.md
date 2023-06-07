---
date: '2'
title: 'Custom Search Engine'
cover: './1.png'
github: 'https://github.com/kasv-p/Building-Custom-Seach-Engine'
external: ''
tech:
  - Elasticsearch
  - Kibana
  - Python
  - Flask
---

A web application is created that functions as a search engine primarily when it is used to look for domain-specific URLs. Almost 10,000 links were crawled, used elasticsearch api to store the filtered terms found in each link, md5 hashing was used to hash the content from the url that was stored in a database so that the hash could be used to determine if the information on a website had been updated.