# machine-learning
test
Title         : BigRLab summary
author        :Pandeng Li
Subtitle      :(2016-5-18)
Logo          : False

![bigrlab-logo]

[bigrlab-logo]: images/bigrlab-logo.png "bigrlab-logo" { width:auto; max-width:90% }

[TITLE]


# BigRLab real-time serving 

BigRLab real-time serving is a fast prediction serving for production system, manual
with a focus on simplicity and plain text readability.

* Read the [reference manual].
* Explore the upper-right toolbox menu to discover how BigRLab server works. 
* `Alt-Q` reformats the current paragraph.

Most algorithm can be abstracted the loss of the objective function, a definition
 of $L$ is shown in Equation [#euler1], 
and then be solved through SGD parameters optimization methods, described by [#euler2],[#euler3] 
, proved by Theorem [#th-euler]:

~ Equation { #euler1 }
 {L}=\sum_{k=1}^n\left\{\frac{f(\beta^TX)y_k-g(\beta^TX)}{\alpha(\phi)}+\rho(y_k;\phi)\right\} \quad\forall n\in\mathbb N, 
~

~ Equation { #euler2 }
\begin{aligned}
\ {\frac{dL_{poisson}}{d\beta_j}} & =\sum_{k=1}^n\left[ y_k-e(\sum_{p=0}^m\beta_px_k^p)\right]x_k^j 
\end{aligned}
~

~ Equation { #euler3 }
\begin{aligned}
\ {\frac{dL_{logistic}}{d\beta_j}} & =\sum_{k=1}^n\left[ y_k-\frac{1}{1+e(\sum_{p=0}^m-\beta_px_k^p)}\right]x_k^j
\end{aligned}
~


~ Theorem {#th-euler; caption:"Euler's theorem" }
More math here.
~
# BigRLab Algorithm Engine

Enjoy!

 
[reference manual]: http://www.baidu.com  "BigRLab reference manual"
