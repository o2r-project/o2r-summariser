# o2r-summariser

o2r microservice for collecting summary statistics

This repository is a placeholder to collect ideas on such a microservice, what data it could provide, and how it could be presented.

## Structure

The microservice provides an endpoint `/api/v1/stats` to acces raw data points as well as infographics.

It should be written in Python :-).

Each data point can be calculated at fixed intervals, or be calculated on demand.

summariser may utilize both the MongoDB (also to store the statistics in a new collection) and Elasticsearch for collecting information.
For on-the-fly statistics Elasticsearch should be used.

## Data points

- average execution time of all jobs
- average exectution time of each step of all jobs
- average execution time of a collection of compendia (i.e. the "similar" compendia)
- code statistics
  - number of code files per compendium
  - programming language used
 
 Some examples for (visual) 
  
https://d2pdyyx74uypu5.cloudfront.net/spread-the-word/resources/infographics/2-year-anniversary/peerj-two-year-anniversary-infographic-1200x5362px.jpg

https://www.digital-science.com/blog/news/state-open-data-report-infographic-stateofopendata/

https://gist.github.com/r0mdau/db31403c0338b057bc7a
 
