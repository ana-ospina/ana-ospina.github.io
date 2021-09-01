---
layout: splash
title: "Research"
permalink: /research/
author_profile: false
---

{: .text-justify style="font-size: 16pt" reversed="reversed"}
### Time-Varying Optimization of Networked Systems

{: .text-justify style="font-size: 12pt" reversed="reversed"}
| <img src="/assets/images/TV_network.png" width="2800px" alt="TV_network"> | Networked systems that interact with single or multiple users are becoming more complex. In this type of interaction, it is common to have complete (or partial) knowledge of the physical or operational limits of the network, and uncertainties regarding the preferences function of each specific user. In order to solve optimization problems that involve objectives from the network and goals for multiple users, we develop a distributed online optimization algorithm with concurrent learning of the users' functions. In this context, we focus on an online consensus-based algorithm to solve a time-varying optimization problem associated with a network of systems shared by multiple users. The online algorithm is based on a primal-dual method, properly modified to accommodate feedback from the users and measurements from the network. Numerical results are  presented in this [pre-print](https://arxiv.org/pdf/2103.13470.pdf) in the context of real-time management of distributed energy resources. |

{: .text-justify style="font-size: 16pt" reversed="reversed"}
### Personalized Demand Response via Online Learning

{: .text-justify style="font-size: 12pt" reversed="reversed"}
| <img src="/assets/images/GP_ex.png" width="2800px" alt="GP_ex"> | Demand response strategies are key to increase the flexibility and efficiency of power systems by allowing controllable devices to provide services at various time-scales. Nowadays, users have a high level of interaction with most of the controllable devices at the distribution level, then, we can have access to feedback from the user at different time intervals. In this context, we formalize a demand response task as an optimization problem featuring a known time-varying engineering cost - associated with the network- and an unknown (dis)comfort function -relative to the users-. We develop a feedback-based projected gradient descent method to solve the demand response problem in an online fashion by using feedback from the user to learn the (dis)comfort function, and measurements of electrical quantities to estimate the gradient of the known engineering cost. One example of this setting is presented in this [paper](https://ieeexplore.ieee.org/document/9303020). | <img src="/assets/images/SHGP_ex.png" width="2800px" alt="SHGP_ex"> | 

{: .text-justify style="font-size: 16pt" reversed="reversed"}
### Estimation of Matrix Sensitivity 

{: .text-justify style="font-size: 12pt" reversed="reversed"}
| <img src="/assets/images/Fig_intro_R1_1.png" width="2800px" alt="sensitivity"> | Perfect knowledge of power systems parameters is a complex and expensive task, but it is vital to guarantee the proper performance of many systems that interact with the network. In this line of work, we focus on the estimation of sensitivity matrices in electrical transmission systems. We proposed an online proximal-gradient method to estimate sensitivities on-the-fly from real-time measurements by leveraging a nuclear norm minimization approach as well as sparsity-promoting regularization functions. Relative to a least-squares estimation method, the proposed approach allows to obtain meaningful estimates of the sensitivity matrix even when measurements are correlated. This [pre-print](https://arxiv.org/pdf/2006.16346.pdf) is our first approach on that direction. | <img src="/assets/images/Fig_9_BC_LSE_LR.png" width="3200px" alt="9bus_LSE_LR"> |