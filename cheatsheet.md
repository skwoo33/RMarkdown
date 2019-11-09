---
title: "R Markdown Cheatsheet"
author: "Skwoo"
date: "2017년 6월 25일"
output: html_document
---

Plain text  
End a line with two spaces to start a new paragraph.  
*italics* and _italics_  
**bold** and __bold__  
superscript^2^  
~~strikethrough~~  
[link](www.rstudio.com)

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

endash : --   
emdash : ---   
ellipsis : ...   
inline equation : $A = \pi*r^{2}$   
horizontal rule (or slide break) :

***

> block quote  
> abc

---

> block quote

* unordere list
* item 2
    + sub-item 1
    + sub-item 2

1. ordered list
2. item 2
    + sub-item 1
    + sub-item 2
    
Table Header  | Second Header
--------------| -------------
Table Cell    | Cell 2
Cell 3        | Cell 4

Two plus two equals `r 2 + 2`

Here's some code
```{r eval = FALSE}
dim(iris)
```

Here's some code
```{r echo = FALSE}
dim(iris)
```

Here's some code
```{r echo}
dim(iris)
```
