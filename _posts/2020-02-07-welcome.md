# Essential mathematics of machine learning. $1/N$

1. TOC
{:toc}
## Learning as optimization 

We will start by only relying on our ability to formulate an optimization problem. Along the way we will discover several useful mathematical tricks with our sole objective being better understanding.

{% include alert.html text=" The following discussion is aimed at readers with atleast high school level understading of mathematics." %}

### Digression : Linear Algebra

{% include info.html text="Linear Algebra helps us in framing our optimization problems more compactly. We will later look at the subject from different perspectives to help us develop deeper appreciation of it's applications. But,for now I will suffice with a quick recap of some basic results." %}

#### Geometric View 

![Summary of useful results - Geometric view](/images/Website.jpg)

#### Now some useful results 

![Useful Results](/images/Matrix-results-.jpg)

![Useful Results](/images/Decomp-Continued-.jpg)


### PCA

We will start out with a bunch of points in `n` dimensional space . Now with the tools of some matrix algebra we will see how far we can go by framing optimization problems.

Given that these points have zero mean , and we want to squeeze all these points along a vector so that the variance is maximum.

![Useful Results](/images/Untitled-Artwork.jpg)
![Useful Results](/images/Pca-Complete..jpg)

#### How are 1 and 2 same 

The necessary geometric intuition can best be captured through a video. Checkout the following two videos from Khan Academy.


[![Constrained Optimization](/images/Screenshot 2020-02-07 at 11.38.42 AM.png)](https://www.youtube.com/watch?v=vwUV2IDLP8Q&list=PLCg2-CTYVrQvNGLbd-FN70UxWZSeKP4wV&index=8)

[![Lagrange multipliers](/images/Screenshot 2020-02-07 at 11.38.20 AM.png)](https://www.youtube.com/watch?v=yuqB-d5MjZA&list=PLCg2-CTYVrQvNGLbd-FN70UxWZSeKP4wV&index=1)


Now,let's complete our problem :

![](/images/Pca-Other-Directions-.jpg)
![](/images/Pca-Done.jpg)

We have one problem though as we wanted our sample to be representative of the true population which often might not be the case. So let's reformulate our problem :

#### Geometric Formulation

![](/images/1.Geometric-View.jpg)
![](/images/2.geometric-Pca.jpg)
![](/images/3.jpg)
![](/images/4..jpg)
![](/images/5..jpg)






