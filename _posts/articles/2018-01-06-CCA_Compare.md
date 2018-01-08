---
title: "CCA Compare"
excerpt: Demonstrating CCA Comparison tool from AWS
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

This demonstrates an embedded version of the Community Choice Aggregation price comparison tool. 

<div class="container">
<iframe style="position:relative;top:0px;width:100%;height:120vh;" src="http://54.163.27.74:3838/cca_compare/"></iframe>
</div>

The tool is running on an AWS Shiny server, and can be embedded in any website with the following code (with CSS styling as necessary):

```
<div>
 <iframe 
   src="http://54.163.27.74:3838/cca_compare/">
 </iframe>
</div>
```

Tool source code is [here](https://github.com/flynn-d/cca_compare).