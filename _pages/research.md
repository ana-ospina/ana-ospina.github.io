---
layout: splash
title: "Research"
permalink: /research/
author_profile: false
---

{: .text-justify style="font-size: 13pt" reversed="reversed"}
### Time-Varying Optimization of Networked Systems

{: .text-justify style="font-size: 12pt" reversed="reversed"}
| <img src="/assets/images/TV_network.png" width="3000px" alt="TV_network"> | We consider a time-varying optimization problem associated with a network of systems, with each of the systems shared by (and affecting) a number of individuals. The objective is to minimize cost functions associated with the individuals' preferences, which are unknown, subject to time-varying constraints that capture physical or operational limits of the network. To this end, we develop a distributed online optimization algorithm with concurrent learning of the cost functions. The cost functions are learned on-the-fly based on the users' feedback (provided at irregular intervals) by leveraging tools from shape-constrained Gaussian Processes. The online algorithm is based on a primal-dual method, and acts effectively in a closed-loop fashion where: i) users' feedback is utilized to estimate the cost, and ii) measurements from the network are utilized in the algorithmic steps to bypass the need for sensing of (unknown) exogenous inputs of the network. The performance of the algorithm is analyzed in terms of dynamic network regret and constraint violation. Numerical examples are presented in the context of real-time optimization of distributed energy resources. |


{: .text-justify style="font-size: 13pt" reversed="reversed"}
### Personalized Demand Response via Online Learning

{: .text-justify style="font-size: 12pt" reversed="reversed"}
| <img src="/assets/images/GP_ex.png" width="2500px" alt="GP_ex"> | We formalize a demand response task as an optimization problem featuring a known time-varying engineering cost and an unknown (dis)comfort function. Based on this model, we develop a feedback-based projected gradient method to solve the demand response problem in an online fashion, where: i) feedback from the user is leveraged to learn the (dis)comfort function concurrently with the execution of the algorithm; and, ii) measurements of electrical quantities are used to estimate the gradient of the known engineering cost. To learn the unknown function, a shape-constrained Gaussian Process is leveraged; this approach allows one to obtain an estimated function that is strongly convex and smooth. The performance of the online algorithm is analyzed by using metrics such as the tracking error and the dynamic regret.  | <img src="/assets/images/SHGP_ex.png" width="2400px" alt="SHGP_ex"> | 


{: .text-justify style="font-size: 13pt" reversed="reversed"} 
### Estimation of Matrix Sensitivity 

{: .text-justify style="font-size: 12pt" reversed="reversed"}
| <img src="/assets/images/Fig_intro_R1_1.png" width="2400px" alt="sensitivity"> | In this work we focus on the estimation of sensitivity matrices in electrical transmission systems. By leveraging a low-rank approximation of certain classes of sensitivity matrices, we propose a robust nuclear norm minimization method to estimate sensitivities from measurements. Relative to existing methods based on the least-squares approach, the proposed method can obtain meaningful estimates with a smaller number of measurements and when the regression model is underdetermined; the method can also identify faulty measurements and handle missing data. An online proximal-gradient method is proposed to estimate sensitivities on-the-fly from real-time measurements; convergence results in terms of dynamic regret are offered in this case. | <img src="/assets/images/Fig_9_BC_LSE_LR.png" width="3200px" alt="9bus_LSE_LR"> |