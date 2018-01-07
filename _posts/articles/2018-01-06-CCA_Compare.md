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

This demonstrates an embedded version of the Community Choice Aggregation price comparison tool. The tool is running on an AWS Shiny server, and can be embedded in any website with the following code:

```
<div>
 <iframe width="1050" height="1000" 
   src="http://54.89.100.53:3838/cca_compare/">
 </iframe>
</div>
```


<div>
<iframe allowtransparency="true" width="1050" height="1000" src="http://54.89.100.53:3838/cca_compare/" frameBorder="3"></iframe>
</div>

Tool source code is [here](https://github.com/flynn-d/cca_compare).