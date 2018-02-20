# Multi-class object detection with BAdaCost.

This repo has a modified version of [Piotr Dollar toolbox](http://vision.ucsd.edu/~pdollar/toolbox/doc/) (Matlab and C++ code) to replicate the experiments we made for our Cost-Sensitive Multiclass algorithm paper. If you use this code for your own researh, **you must reference our journal paper**:
  
   **BAdaCost: Multi-class Boosting with Costs.**
   Antonio Fernández-Baldera, José M. Buenaposada, and Luis Baumela.
   Pattern Recognition, Elsevier. In press, 2018.
   [DOI:10.1016/j.patcog.2018.02.022](https://doi.org/10.1016/j.patcog.2018.02.022)


# Replicate paper experiments or simply use our trained classifiers.

Our modifications to P.Dollar toolbox have only been tested on GNU/Linux Matlab. To replicate paper experiments you have to:

* Clone this repo
  * Execute toolboxCompile
* Clone the [multi-view car detection scripts repo](https://github.com/jmbuena/toolbox.badacost.kitti.public) and follow instructions there.
* Clone the [multi-view face detection scripts repo](https://github.com/jmbuena/toolbox.badacost.faces.public) and follow instructions there.
