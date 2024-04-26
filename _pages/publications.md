---
layout: archive
title: #
permalink: /publications/
author_profile: true
---

### Current Projects

### Path-Dependent Closed-Loop Control with Rough Path Signatures

### Deep Learning Methods for Accelerating Optimization and Model Predictive Control

<br />

Preprints and Working Papers
======

### [DARE: The Deep Adaptive Regulator for Closed-Loop Predictive Control](https://harrisonwaldon.github.io/files/dare.pdf)
#### [Fayçal Drissi](https://www.faycaldrissi.com/)\*, **Harrison Waldon**\*, [Yannick Limmer](https://scholar.google.com/citations?user=ArvBldAAAAAJ&hl=en)\*, [Álvaro Cartea](https://sites.google.com/site/alvarocartea/home)

<!-- Abstract: A fundamental challenge in optimal control (OC) and machine learning is how to find the optimal policy of an agent that operates in changing and uncertain environments.Traditional OC methods face challenges in scalability and adaptability due to the curse-of-dimensionality and the reliance on fixed prior models of the environment.  -->
<!-- Model Predictive Control (MPC) addresses these issues but is limited to open-loop controls, i.e., policies without feedback to adapt. Another approach is Reinforcement Learning (RL) which can scale well to high-dimensional applications but is often computationally expensive and can be unreliable in highly stochastic continuous-time setups. This paper presents the Deep Adaptive Regulator (DARE) which combines deep learning with OC to compute closed-loop adaptive policies by solving continuously updated OC problems that explicitly trade off exploration with exploitation. We show that our method effectively transfers learning to unseen environments and is suited for online decision-making in environments that change in real time. We test DARE in various setups and demonstrate its superior performance over traditional methods, especially in scenarios with misspecified priors and nonstationary dynamics. -->


### **[Algorithmic Collusion and a Folk Theorem from Learning with Bounded Rationality](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4293831)** (*Submitted*)
#### [Álvaro Cartea](https://sites.google.com/site/alvarocartea/home)\*, [Patrick Chang](https://sites.google.com/view/patrickchang/home?authuser=1)\*, [Jose Penalva](https://www.josepenalva.com/)\*, **Harrison Waldon**\*
<!-- Abstract: We prove a Folk theorem when players with bounded rationality learn as they play a repeated potential game. We use a dynamic generalization of smooth fictitious play with bounded m-memory strategies to model learning with bounded rationality that is consistent with learning by algorithms. In a repeated potential game with perfect monitoring, we use this learning model to show that for any feasible and individually rational payoff profile, if players have sufficient memory, are sufficiently patient, and best respond with sufficiently few mistakes, then the players have a non-zero probability of learning an m-memory strategy profile that achieves an average payoff close to the specified payoff profile for an appropriate continuation game. Moreover, the strategy profile learned is an m-memory ε-subgame perfect equilibrium of the repeated game. This finding demonstrates that competition authorities are correct in their concern about algorithmic collusion. -->

### **[The Algorithmic Learning Equations: Evolving Strategies in Dynamic Games](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4175239)**
#### [Álvaro Cartea](https://sites.google.com/site/alvarocartea/home)\*, [Patrick Chang](https://sites.google.com/view/patrickchang/home?authuser=1)\*, [Jose Penalva](https://www.josepenalva.com/)\*, **Harrison Waldon**\*
<!-- Abstract: We introduce the algorithmic learning equations, a set of ordinary differential equations which characterizes the finite-time and asymptotic behavior of the stochastic interaction between state-dependent learning algorithms in dynamic games. Our framework allows for a variety of information and memory structures, including noisy, perfect, private, and public monitoring and for the possibility that players use distinct learning algorithms. We prove that play converges to a correlated equilibrium for a family of algorithms under correlated private signals. Finally, we apply our methodology in a repeated 2x2 prisoner's dilemma game with perfect monitoring. We show that algorithms can learn a reward-punishment mechanism to sustain tacit collusion. Additionally, we find that algorithms can also learn to coordinate in cycles of cooperation and defection. -->


Publications
======
### **[Rough Transformers for Continuous and Efficient Time-Series Modelling](https://arxiv.org/abs/2403.10288)** (ICLR TS4H 2024)
#### [Fernando Moreno-Pino](https://fmorenopino.github.io/)\*, [Álvaro Arroyo](https://scholar.google.co.uk/citations?user=P1qHzNYAAAAJ&hl=en)\*, **Harrison Waldon**\*, [Xiaowen Dong](https://web.media.mit.edu/~xdong/), [Álvaro Cartea](https://sites.google.com/site/alvarocartea/home)
<!-- Abstract: Time-series data in real-world medical settings typically exhibit long-range dependencies and are observed at non-uniform intervals. In such contexts, traditional sequence-based recurrent models struggle. To overcome this, researchers replace recurrent architectures with Neural ODE-based models to model irregularly sampled data and use Transformer-based architectures to account for long-range dependencies. Despite the success of these two approaches, both incur very high computational costs for input sequences of moderate lengths and greater. To mitigate this, we introduce the Rough Transformer, a variation of the Transformer model which operates on continuous-time representations of input sequences and incurs significantly reduced computational costs, critical for addressing long-range dependencies common in medical contexts. In particular, we propose multi-view signature attention, which uses path signatures to augment vanilla attention and to capture both local and global dependencies in input data, while remaining robust to changes in the sequence length and sampling frequency. We find that Rough Transformers consistently outperform their vanilla attention counterparts while obtaining the benefits of Neural ODE-based models using a fraction of the computational time and memory resources on synthetic and real-world time-series tasks. -->

### **[Forward robust portfolio selection: The binomial case](https://www.aimsciences.org/article/doi/10.3934/puqr.2024006)** (Probability, Uncertainty and Quantitative Risk, 2024)
#### **Harrison Waldon**
<!-- Abstract: We introduce a new approach for optimal portfolio choice under model ambiguity by incorporating predictable forward preferences in the framework of Angoshtari et al. The investor reassesses and revises the model ambiguity set incrementally in time while, also, updating his risk preferences forward in time. This dynamic alignment of preferences and ambiguity updating results in time-consistent policies and provides a richer, more accurate learning setting. For each investment period, the investor solves a worst-case portfolio optimization over possible market models, which are represented via a Wasserstein neighborhood centered at a binomial distribution. Duality methods from Gao and Kleywegt; Blanchet and Murthy are used to solve the optimization problem over a suitable set of measures, yielding an explicit optimal portfolio in the linear case. We analyze the case of linear and quadratic utilities, and provide numerical results. -->

\* denotes equal contribution

Theses
======

### [The Algorithmic Learning Equations](https://repositories.lib.utexas.edu/items/3405fbe2-c3ec-4f87-8bc6-526e54f6e4c2) (PhD Dissertation)
#### Advisor: [Thaleia Zariphopoulou](https://web.ma.utexas.edu/users/zariphop/)
<!-- Abstract: This thesis presents the Algorithmic Learning Equations (ALEs) to study tacit algorithmic collusion. The ALEs are a set of differential equations that characterizes the finite-time and asymptotic behavior of state-dependent learning algorithms in stochastic and repeated games. The ALEs are derived rigorously, drawing upon stochastic approximation theory. The ALEs are analyzed to show, numerically and theoretically, that decentralized, self-interested learning algorithms can learn to collude. The final chapter of this thesis presents preliminaries using inverse reinforcement learning to detect collusion in a data-driven way. The contents of this thesis are primarily drawn from joint work with Professor Álvaro Cartea, Professor José Penalva, and Patrick Chang during various research visits to the Oxford-Man Institute of Quantitative Finance in 2022 and 2023. -->


### [Degrees of Freedom for Long Time Dynamics of Forced Critical Burgers and SQG Equation](https://dataspace.princeton.edu/handle/88435/dsp0170795b28c) (Senior Thesis)
#### Advisor: [Vlad Vicol](https://cims.nyu.edu/~vicol/)


<!-- {% if site.author.googlescholar %}
  <div class="wordwrap">You can find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
