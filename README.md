# The Effect of Road Bumps on Touch Interaction in Cars
This repository contains the dataset, Python notebooks for training and preprocessing, the model reported in the paper, paper figures, and statictical tests for the paper. 

## Paper Abstract
Touchscreens are a common fixture in current vehicles. With autonomous driving, we can expect touch interaction with such in-vehicle media systems to exponentially increase. In spite of vehicle suspension systems, road perturbations will continue to exert forces that can render in-vehicle touch interaction challenging. Using a motion simulator, we investigate how different vehicle speeds interact with road features (i.e., speed bumps) to influence touch interaction. We determine their effect on pointing accuracy and task completion time. We show that road bumps have a significant effect on touch input and can decrease accuracy by 19%. In light of this, we developed a Random Forest (RF) model that improves touch accuracy by 32.0% on our test set and by 22.5% on our validation set. As the lightweight model uses only features that can easily be determined through inertial measurement units, this model could be easily deployed in current automobiles.

<img src="https://raw.githubusercontent.com/interactionlab/Touch-Interaction-with-Road-Bumps/master/mayer2018touchinacar.jpg" width="900px"/>

This work can be cited as follows:
<pre>
@inproceedings{Mayer:2018:ERB,
 author = {Mayer, Sven and Le, Huy Viet and Nesti, Alessandro and Henze, Niels and B\"{u}lthoff, Heinrich H. and Chuang, Lewis L.},
 title = {The Effect of Road Bumps on Touch Interaction in Cars},
 booktitle = {Proceedings of the 10th International Conference on Automotive User Interfaces and Interactive Vehicular Applications},
 series = {AutomotiveUI '18},
 year = {2018},
 isbn = {978-1-4503-5946-7},
 location = {Toronto, ON, Canada},
 pages = {85--93},
 numpages = {9},
 url = {http://doi.acm.org/10.1145/3239060.3239071},
 doi = {10.1145/3239060.3239071},
 acmid = {3239071},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {Touch accuracy, car, center console, in-vehicle touchscreens, offset correction model, on board entertainment system},
} 

</pre>
