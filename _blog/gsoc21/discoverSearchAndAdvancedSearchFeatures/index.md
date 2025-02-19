---
layout: page
title: Discovery Search and Advanced Search features
author: 'Yashraj Desai'
tags: ['project', 'gsoc', 'gsoc2021', 'discoverySearchAndAdvancedSearchFeatures', 'draft']
---

## Discovery Search and Advanced Search Features

CDLI Framework integrates features of the project in a logical infrastructure, prepares new data displays, including machine-readable outputs, to enhance knowledge diffusion. It includes a unified interface for the project website, more powerful search capabilities, more internal links to navigate the catalogue, and intuitive displays for calendars, glossaries, bibliographies, etc.

The Project focuses on enhancing the search and advanced search features in the CDLI framework and documenting the implemented features.

Proposal Link : [Discovery search and advanced search features](https://docs.google.com/document/d/1WEeNnALSUN4yecCbYxuDyMNUMOzkGcev6Dss4XuNydc/edit#)

### Objectives and Deliverables

:heavy_check_mark: --> Completed Tasks
:white_check_mark: --> Ongoing Tasks

| \# | Status  | Objectives                    | Associated Deliverables         | issue(s) |
| --- | --- | ----------------------------- | ---------------------------------------------- | -------- |
| 1 |:white_check_mark:|  Add “Ids” and “Keywords” search fields to both simple and advanced search | Users will be able to search for specific keywords,Id/Numbers artifacts | [#314](https://gitlab.com/cdli/framework/-/issues/314) |
| 2 |:white_check_mark:| Implementation of fuzzy queries | Fuzzy queries would yield search results | [#593](https://gitlab.com/cdli/framework/-/issues/593) |
| 3 |:white_check_mark:| Enable search inscription with sign value permutation | When a user will enable this search feature and search for sign values, all inscriptions with matching sign values will be returned | [#596](https://gitlab.com/cdli/framework/-/issues/596)
| 4 |:white_check_mark:| Highlight transliteration sign values in ATF display |The sign values will be highlighted in the compact search results page|[#347](https://gitlab.com/cdli/framework/-/issues/347)
| 5 |:white_check_mark:| On add or edit save a sanitized version of inscription as a list of sign names |When an artifact is added/edited the sanitised atf data will be stored in the transilteration_sign_names field of the database|[#120](https://gitlab.com/cdli/framework/-/issues/120#note_550066667)
| 6 |:white_check_mark:| Users will have the flexibility to search with both UTF-8 and ASCII characters |Users will have the flexibility to search with both UTF-8 and ASCII characters |[#597](https://gitlab.com/cdli/framework/-/issues/597)
| 7 |:white_check_mark:| Filter search results by RTI Image, Transliterations , 3D Data | Users can apply filters such as RTI Image, Transliterations , 3D Data and get search results | [#136](https://gitlab.com/cdli/framework/-/issues/136)
| 8 |:white_check_mark:| Port request to Elasticsearch from cURL to HttpClient | Replaced cURL implementation with HTTP Client|[#350](https://gitlab.com/cdli/framework/-/issues/350)



### Additional Objectives

| \# | Status  | Objectives         | Associated Deliverables                                             | issue(s) |
| --- | --- | ------------------ | ------------------------------------------------------------------- | -------- |
| 1 | :white_check_mark: | Implementation of CakePHP elasticsearch plugin  | Cakephp Elasticsearch plugin implemented along with documentation | [#460](https://gitlab.com/cdli/framework/-/issues/460) |



### Tentative timeline  

| Week  |Objectives | Deliverables |
|---|---|---|
|1| :heavy_check_mark: Week Objective-1 <br> :white_check_mark: Week Objective-2  |  :heavy_check_mark: Week Deliverables |
|2|   |   |
|3|   |   |
|4|   |   |
|5|   |   |
|6|   |   |
|7|   |   |
|8|   |   |
|9|   |   |
|10|   |   |
|11|   |   |
|12|   |   |



