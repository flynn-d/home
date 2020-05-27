---
title: "My own Shiny server!" 
excerpt: Getting started with Shiny server
image:
  credit: null
  creditlink: null
  feature: katahdinbar.jpg
layout: gallerypage
modified: null
share: yes
comments: yes
tags:
  - AWS
  - Shiny
categories: articles
---

I now have been experimenting with running a Shiny server, currently offline.

### [shiny.flynnd.io/dan/cca_compare/](http://shiny.flynnd.io/dan/cca_compare/)

And also have started a visualizer of bike count data, currently offline as well.

### [shiny.flynnd.io/dan/BikeCount/](http://shiny.flynnd.io/dan/BikeCount/)
(code [here](https://github.com/flynn-d/bikecount), *obviously a work in progress*)

The goal of this is to do the following:

- Make good use of the data feed provided by the City of Cambridge for the Broadway bike counter
- Build off the existing visualizer provided: https://data.cambridgema.gov/d/q8v9-mcfg/visualization
- Use predictive analytics to generate estimates of counts of cyclists in the next day, week, and year
- Track the predictions and report how far off or close they were

## Infrastructure

This is built with the following tools:

- [Shiny Server](https://www.rstudio.com/products/shiny/shiny-server/)
- AWS EC2 instance ([AMI from Louis Aslett](http://www.louisaslett.com/RStudio_AMI/), with modifications)
- GitHub pages (this site)
- Setting DNS records correctly with my domain name provider 
- Lots of Stack Overflow to get nginx, proxy stuff, ssh keys, and permissions all set up right 

