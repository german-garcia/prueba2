---
title: "Primer Rmarkdown"
author: "Ger"
date: "5/3/2020"
output: 
  html_document: 
    keep_md: yes
---


## R Markdown

```r
## insert your brilliant WORKING code here
dado <- c(1:6)
dados = 4
replicate(dados, sample(dado))
```

```
##      [,1] [,2] [,3] [,4]
## [1,]    5    4    6    3
## [2,]    3    1    4    1
## [3,]    2    2    3    4
## [4,]    1    6    1    5
## [5,]    4    3    5    6
## [6,]    6    5    2    2
```

