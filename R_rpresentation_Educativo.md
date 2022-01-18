R Presentation Educativo
========================================================
author: Raymond L. Tremblay
date: Sept 7th, 2021
autosize: true
font-family: 'Risque'

First Slide
========================================================

For more details on authoring R presentations please visit <https://support.rstudio.com/hc/en-us/articles/200486468>.

- Bullet 1
- Bullet 2
- Bullet 3

Slide With Code
========================================================


```r
summary(cars)
```

```
     speed           dist       
 Min.   : 4.0   Min.   :  2.00  
 1st Qu.:12.0   1st Qu.: 26.00  
 Median :15.0   Median : 36.00  
 Mean   :15.4   Mean   : 42.98  
 3rd Qu.:19.0   3rd Qu.: 56.00  
 Max.   :25.0   Max.   :120.00  
```

Slide With Plot
========================================================

![plot of chunk unnamed-chunk-2](R_rpresentation_Educativo-figure/unnamed-chunk-2-1.png)





Slide With Image Left
====================================
![bivariate normal](Graficos/Bivariate_normal.png)
***
This text will appear to the right


Equation in sentence
====================================
A good website to do your latex formula is the following <https://latex.codecogs.com>



This is the equation of the arithmetic mean in a sentence 

\(PM_{2.5}\)


\( \\mu =\frac{\sum_{i=1}^{n}}{n}\\\)

\(\overline{x}=\frac{\sum_{ }{}x_i}{n}\) 


Equation in center
====================================

$$
  \begin{aligned}
  \dot{x} & = \sigma(y-x) \\
  \dot{z} & = \beta z + xy)
  \end{aligned}
$$

another alternative

$$
[2x_1 - 3x-1x_3\]
$$


Multiple columns
====================================

Species name
- Bullet 1
- Bullet 2

***


Size of Petal
- Bullet 1
- Bullet 2



Multiple columns: 70% 
====================================
left: 70%

Column one
- Bullet 1
- Bullet 2

***


Column two
- Bullet 1
- Bullet 2


Next Week: Xaringan
====================================

Bring your laptop

```r
library(xaringan)
```

See also <
