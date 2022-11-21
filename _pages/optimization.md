---
layout: archive
title: "Optimization"
permalink: /optimization/
author_profile: true
---
### add curly brackets ({}) and percent sign (%) to each line of codes in the people.html
 include base_path 

### link the documents under _people folder
 for post in site.people reversed 
   include archive-single.html 
 endfor 
