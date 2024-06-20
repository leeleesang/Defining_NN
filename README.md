Defining Neural Network Architecture through Polytope Structure of Datasets
=============================
This is the supplementary files for the ICML 2024 *Spotlight* paper "***Defining Neural Network Architecture through Polytope Structure of Datasets***"




Algorithm 1 (**Compressing algorithm**) in the paper:
![compressing](https://github.com/leeleesang/Defining_NN/assets/69498771/94cc5806-655b-4429-820f-e82f2fea2ceb.gif)
<div align="center">
  <img src="https://github.com/leeleesang/Defining_NN/assets/69498771/8d5e5037-8281-4a03-b929-08e1b296c034" width="500"/>
</div>

----



# An example of application of the algorithm on a three-layer ReLU network
<img src="https://github.com/leeleesang/Defining_NN/assets/69498771/6ce53f70-6aa7-4a51-93f7-2e60c5a8e806" width="400"/> <img src="https://github.com/leeleesang/Defining_NN/assets/69498771/b54a896f-3603-4963-8854-fb9afa7d2ead" width="400"/> 

<img src="https://github.com/leeleesang/Defining_NN/assets/69498771/408310c5-6e13-486d-800c-241a7aab14a3" width="400"/> <img src="https://github.com/leeleesang/Defining_NN/assets/69498771/b6e909ae-412c-4e86-b727-2a76a4262f44" width="400"/> 

Iteratively applying the algorithm (as described in Algorithm 3, the network is compressed.
The converged network induces a polytope-basis cover, where each two-layer subnetwork represents one convex polytope.

------

# Finding an efficient polytope-basis cover
Below is the implementation of Algorithm 4 in Appendix.

<img src="https://github.com/leeleesang/Defining_NN/assets/69498771/5f6c0665-6d87-4651-89f1-d81d396e3a92" width="200"/> 
<img src="https://github.com/leeleesang/Defining_NN/assets/69498771/6f86d91d-e187-4b1e-9aed-764c1c34e4d2" width="200"/> 
<img src="https://github.com/leeleesang/Defining_NN/assets/69498771/75f9a721-4bb8-4e31-9a44-bac4a211bf0b" width="200"/> 
<img src="https://github.com/leeleesang/Defining_NN/assets/69498771/5dad1f2c-e67b-4739-9807-a41c36f36507" width="200"/> 

<img src="https://github.com/leeleesang/Defining_NN/assets/69498771/d91be162-7f91-471c-b96d-e7a8e5113783" width="200"/> 
<img src="https://github.com/leeleesang/Defining_NN/assets/69498771/2ad223b8-8013-46e1-aad7-861593731101" width="200"/> 
<img src="https://github.com/leeleesang/Defining_NN/assets/69498771/0fe1889b-9886-49cd-b29a-6a200dcb224b" width="200"/> 
<img src="https://github.com/leeleesang/Defining_NN/assets/69498771/15b89912-787a-4a21-a966-7750690716ca" width="200"/> 

## The obtained polytope-basis cover and combinated decision boundary
<div align="center">
  The collaborated decision boundary.
  </div>
<div align="center">
   <img src="https://github.com/leeleesang/Defining_NN/assets/69498771/fdd21e7f-c44f-4287-aa45-c38d8739a61a" width="500"/> 
</div>

<div align="center">
  Polytopes implicitly embedded in the network.
  </div>
<div align="center">
   <img src="https://github.com/leeleesang/Defining_NN/assets/69498771/301afbbb-3c7e-4eb3-ba43-c2a9a62adab2" width="990"/>
</div>
