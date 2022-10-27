---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Up to date information can be found on my <a href='https://scholar.google.it/citations?user=WG9oe0wAAAAJ&hl=en'> <i class="ai ai-google-scholar"></i>Google Scholar</a> and <a href='https://arxiv.org/a/santin_g_1.html'> <i class="ai ai-arxiv"></i>ArXiv</a> profiles.

Click on the publications below to expand them.

## Submitted
<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary>T. Wenzel, D. Winkle, G. Santin, B. Haasdonk, 
<i>Adaptive meshfree solution of linear partial differential equations with PDE-greedy kernel methods </i> (2022). <a href='https://arxiv.org/abs/2207.13971'> <i class="fa fa-file-pdf"></i> Preprint </a>
</summary>

<small>

<blockquote>
We consider the meshless solution of PDEs via symmetric kernel collocation by using greedy kernel methods. In this way we avoid the need for mesh generation, which can be challenging for non-standard domains or manifolds. We introduce and discuss different kind of greedy selection criteria, such as the PDE-P -greedy and the PDE-f -greedy for collocation point selection. Subsequently we analyze the convergence rates of these algorithms and provide bounds on the approximation error in terms of the number of greedily selected points. Especially we prove that target-data dependent algorithms, i.e. those using knowledge of the right hand side functions of the PDE, exhibit faster convergence rates. The provided analysis is applicable to PDEs both on domains and manifolds. This fact and the advantages of target-data dependent algorithms are highlighted by numerical examples.	
</blockquote>

<pre>
  <code class="bibtex">
@Article{Wenzel2022c,
  author    = {Wenzel, Tizian and Santin, Gabriele and Haasdonk, Bernard},
  title     = {Analysis of Target Data-Dependent Greedy Kernel Algorithms: Convergence Rates for f-, {\$}{\$}f {\backslash}cdot P{\$}{\$}- and f/P-Greedy},
  journal   = {Constructive Approximation},
  year      = {2022},
  month     = {Oct},
  issn      = {1432-0940},
  doi       = {10.1007/s00365-022-09592-3},
  url       = {https://doi.org/10.1007/s00365-022-09592-3},
  day       = {18},
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary>T. Wenzel, G. Santin, B. Haasdonk, 
<i>Stability of convergence rates: Kernel interpolation on non-Lipschitz domains </i> (2022). <a href='https://arxiv.org/abs/2203.12532'> <i class="fa fa-file-pdf"></i> Preprint </a>
</summary>

<small>

<blockquote>
Error estimates for kernel interpolation in Reproducing Kernel Hilbert Spaces (RKHS) usually assume quite restrictive properties on the shape of the domain, especially in the case of infinitely smooth kernels like the popular Gaussian kernel. In this paper we leverage an analysis of greedy kernel algorithms to prove that it is possible to obtain convergence results (in the number of interpolation points) for kernel interpolation for arbitrary domains $\Omega\subset\mathbb{R}^d$, thus allowing for non-Lipschitz domains including e.g. cusps and irregular boundaries. Especially we show that, when going to a smaller domain $\tilde\Omega\subset\Omega\subset\mathbb{R}^d$, the convergence rate does not deteriorate - i.e. the convergence rates are stable with respect to going to a subset. The impact of this result is explained on the examples of kernels of finite as well as infinite smoothness like the Gaussian kernel. A comparison to approximation in Sobolev spaces is drawn, where the shape of the domain Ω has an impact on the approximation properties. Numerical experiments illustrate and confirm the experiments	
</blockquote>

<pre>
  <code class="bibtex">
@Misc{Wenzel2022b,
  author        = {Tizian Wenzel and Gabriele Santin and Bernard Haasdonk},
  title         = {Stability of convergence rates: Kernel interpolation on non-Lipschitz domains},
  year          = {2022},
  eprint        = {2203.12532},
  archiveprefix = {arXiv},
  primaryclass  = {math.NA},
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary>A. Alla, H. Oliveira, G. Santin, 
<i>HJB-RBF based approach for the control of PDEs</i> (2021). <a href='https://arxiv.org/abs/2108.02987'> <i class="fa fa-file-pdf"></i> Preprint </a>
</summary>

<small>

<blockquote>
Semi-lagrangian schemes for discretization of the dynamic programming principle are based on a time discretization projected on a state-space grid. The use of a structured grid makes this approach not feasible for high-dimensional problems due to the curse of dimensionality. Here, we present a new approach for infinite horizon optimal control problems where the value function is computed using Radial Basis Functions (RBF) by the Shepard's moving least squares approximation method on scattered grids. We propose a new method to generate a scattered mesh driven by the dynamics and the selection of the shape parameter in the RBF using an optimization routine. This mesh will help to localize the problem and approximate the dynamic programming principle in high dimension. Error estimates for the value function are also provided. Numerical tests for high dimensional problems will show the effectiveness of the proposed method.	
</blockquote>

<pre>
  <code class="bibtex">
@misc{Alla2021,
      title={HJB-RBF based approach for the control of PDEs}, 
      author={Alessandro Alla and Hugo Oliveira and Gabriele Santin},
      year={2021},
      eprint={2108.02987},
      archivePrefix={arXiv},
      primaryClass={math.NA}
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary>T. Wenzel, G. Santin, B. Haasdonk, 
<i>Universality and optimality of structured deep kernel  networks</i> (2021). <a href='https://arxiv.org/abs/2105.07228'> <i class="fa fa-file-pdf"></i> Preprint </a>
</summary>

<small>

<blockquote>
Kernel based methods yield approximation models that are flexible, efficient and powerful. In particular, they utilize fixed feature maps of the data, being often associated to strong analytical results that prove their accuracy. On the other hand, the recent success of machine learning methods has been driven by deep neural networks (NNs). They achieve a significant accuracy on very high-dimensional data, in that they are able to learn also efficient data representations or data-based feature maps. In this paper, we leverage a recent deep kernel representer theorem to connect the two approaches and understand their interplay. In particular, we show that the use of special types of kernels yield models reminiscent of neural networks that are founded in the same theoretical framework of classical kernel methods, while enjoying many computational properties of deep neural networks. Especially the introduced Structured Deep Kernel Networks (SDKNs) can be viewed as neural networks with optimizable activation functions obeying a representer theorem. Analytic properties show their universal approximation properties in different asymptotic regimes of unbounded number of centers, width and depth. Especially in the case of unbounded depth, the constructions is asymptotically better than corresponding constructions for ReLU neural networks, which is made possible by the flexibility of kernel approximation.	
</blockquote>

<pre>
  <code class="bibtex">
@misc{Wenzel2021c,
      title={Universality and Optimality of Structured Deep Kernel Networks}, 
      author={Tizian Wenzel and Gabriele Santin and Bernard Haasdonk},
      year={2021},
      eprint={2105.07228},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary>S. Cuomo, W. Erb, G. Santin, 
<i>Kernel-Based Models for Influence Maximization on Graphs based on Gaussian Process Variance  Minimization</i> (2021). <a href='https://arxiv.org/abs/2103.01575'> <i class="fa fa-file-pdf"></i> Preprint </a>
</summary>

<small>

<blockquote>
The inference of novel knowledge, the discovery of hidden patterns, and the uncovering of insights from large amounts of data from a multitude of sources make Data Science (DS) to an art rather than just a mere scientific discipline. The study and design of mathematical models able to analyze information represents a central research topic in DS. In this work, we introduce and investigate a novel model for influence maximization (IM) on graphs using ideas from kernel-based approximation, Gaussian process regression, and the minimization of a corresponding variance term. Data-driven approaches can be applied to determine proper kernels for this IM model and machine learning methodologies are adopted to tune the model parameters. Compared to stochastic models in this field that rely on costly Monte-Carlo simulations, our model allows for a simple and cost-efficient update strategy to compute optimal influencing nodes on a graph. In several numerical experiments, we show the properties and benefits of this new model. 	
</blockquote>

<pre>
  <code class="bibtex">
@misc{Cuomo2021,
      title={Kernel-Based Models for Influence Maximization on Graphs based on Gaussian Process Variance Minimization}, 
      author={Salvatore Cuomo and Wolfgang Erb and Gabriele Santin},
      year={2021},
      eprint={2103.01575},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
  </code>
</pre>
</small>

</details>

</p>



## Accepted
<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary>F. Marchetti, G. Santin, 
<i>Convergence results in image interpolation with the continuous SSIM</i>, 
Accepted for publication in SIAM Journal on Imaging Sciences (2022). <a href='https://arxiv.org/abs/2108.03879'> <i class="fa fa-file-pdf"></i> Preprint </a>
</summary>

<small>

<blockquote>
Assessing the similarity of two images is a complex task that attracts significant efforts in the image processing community. The widely used Structural Similarity Index Measure (SSIM) addresses this problem by quantifying a perceptual structural similarity. In this paper we consider a recently introduced continuous SSIM (cSSIM), which allows one to analyse sequences of images of increasingly fine resolutions, and  further extend the definition of the index to encompass the locally weighted version that is used in practice.  For both the local and the global versions, we prove that the continuous index includes the classical SSIM as a special case, and we provide a precise  connection between image similarity measured by the cSSIM and by the $L_2$ norm. Using this connection, we derive bounds on the cSSIM by means of bounds on the $L_2$ error, and we even prove that the two error measures are equivalent in  certain circumstances. We exploit these results to obtain precise rates of convergence with respect to the cSSIM for several concrete image interpolation  methods, and we further validate these findings by different numerical experiments. This newly established connection paves the way to obtain novel insights into the features and limitations of the SSIM, including on the effect of the local  weighted window on the index performances. 	
</blockquote>

<pre>
  <code class="bibtex">
@misc{Marchetti2022,
      title={Convergence results in image interpolation with the continuous SSIM}, 
      author={Francesco Marchetti and Gabriele Santin},
      year={2021},
      eprint={2108.03879},
      archivePrefix={arXiv},
      primaryClass={math.NA}
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary>B. Nobile, G. Santin, B. Lepri, P. Brutti, 
<i>Reprogramming FairGANs with Variational Auto-Encoders: A New Transfer Learning Model</i>, 
Accepted for publication in Proceeding of SIS2022 - 51st Scientific Meeting of the Italian Statistical Society (2022). <a href='https://arxiv.org/abs/2203.05811'> <i class="fa fa-file-pdf"></i> Preprint </a>
</summary>

<small>

<blockquote>
Fairness-aware GANs (FairGANs) exploit the mechanisms of Generative Adversarial Networks (GANs) to impose fairness on the generated data, freeing them from both disparate impact and disparate treatment. Given the model's advantages and performance, we introduce a novel learning framework to transfer a pre-trained FairGAN to other tasks. This reprogramming process has the goal of maintaining the FairGAN's main targets of data utility, classification utility, and data fairness, while widening its applicability and ease of use. In this paper we present the technical extensions required to adapt the original architecture to this new framework (and in particular the use of Variational Auto-Encoders), and discuss the benefits, trade-offs, and limitations of the new model.	
</blockquote>

<pre>
  <code class="bibtex">
@misc{Nobile2022,
      title={Reprogramming FairGANs with Variational Auto-Encoders: A New Transfer Learning Model}, 
      author={Beatrice Nobile and Gabriele Santin and Bruno Lepri and Pierpaolo Brutti},
      year={2022},
      eprint={2203.05811},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
  </code>
</pre>
</small>

</details>

</p>



## Published

<p style='margin-top:-20px;margin-left:5%;'>
<h3 style='margin-left:5%;'> 2022</h3>
</p>
<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary>T. Wenzel, G. Santin, B. Haasdonk, 
<i>Analysis of target data-dependent greedy kernel algorithms: Convergence rates for f-, f P- and  f/P-greedy</i>, 
Constructive Approximation (2022). <a href='https://arxiv.org/abs/2105.07411'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href='https://doi.org/10.1007/s00365-022-09592-3'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
Data-dependent greedy algorithms in kernel spaces are known to provide fast converging interpolants, while being extremely easy to implement and efficient to run. Despite this experimental evidence, no detailed theory has yet been presented. This situation is unsatisfactory especially when compared to the case of the data-independent P-greedy algorithm, for which optimal convergence rates are available, despite its performances being usually inferior to the ones of target data-dependent algorithms. In this work we fill this gap by first defining a new scale of greedy algorithms for interpolation that comprises all the existing ones in a unique analysis, where the degree of dependency of the selection criterion on the functional data is quantified by a real parameter. We then prove new convergence rates where this degree is taken into account and we show that, possibly up to a logarithmic factor, target data-dependent selection strategies provide faster convergence. In particular, for the first time we obtain convergence rates for target data adaptive interpolation that are faster than the ones given by uniform points, without the need of any special assumption on the target function. The rates are confirmed by a number of examples.	
</blockquote>

<pre>
  <code class="bibtex">
@Article{Wenzel2022c,
  author    = {Wenzel, Tizian and Santin, Gabriele and Haasdonk, Bernard},
  title     = {Analysis of Target Data-Dependent Greedy Kernel Algorithms: Convergence Rates for f-, {\$}{\$}f {\backslash}cdot P{\$}{\$}- and f/P-Greedy},
  journal   = {Constructive Approximation},
  year      = {2022},
  month     = {Oct},
  issn      = {1432-0940},
  doi       = {10.1007/s00365-022-09592-3},
  url       = {https://doi.org/10.1007/s00365-022-09592-3},
  day       = {18},
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary>R. Campagna, S. De Marchi, E. Perracchione, G. Santin, 
<i>Stable interpolation with exponential-polynomial splines and node selection via greedy algorithms </i>, 
Advances in Computational Mathematics (2022). <a href='https://arxiv.org/abs/2109.14299'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href='https://doi.org/10.1007/s10444-022-09986-8  '> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
In this work we extend some ideas about greedy algorithms, which are well-established tools for e.g. kernel bases, and exponential-polynomial splines whose main drawback consists in possible overfitting and consequent oscillations of the approximant. To partially overcome this issue, we develop some results on theoretically optimal interpolation points. Moreover, we introduce two algorithms which perform an adaptive selection of the spline interpolation points based on the minimization either of the sample residuals ($f$-greedy), or of an upper bound for the approximation error based on the spline Lebesgue function ($\lambda$-greedy). Both methods allow us to obtain an adaptive selection of the sampling points, i.e. the spline nodes. While the $f$-greedy selection is tailored to one specific target function, the $\lambda$-greedy algorithm enables us to define target-data-independent interpolation nodes.	
</blockquote>

<pre>
  <code class="bibtex">
@Article{Campagna2022,
  author    = {Campagna, R. and De Marchi, S. and Perracchione, E. and Santin, G.},
  title     = {Stable interpolation with exponential-polynomial splines and node selection via greedy algorithms},
  journal   = {Advances in Computational Mathematics},
  year      = {2022},
  volume    = {48},
  number    = {6},
  month     = {Oct},
  pages     = {69},
  issn      = {1572-9044},
  doi       = {10.1007/s10444-022-09986-8},
  url       = {https://doi.org/10.1007/s10444-022-09986-8},
  day       = {27},
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary>G. Santin, I. Skarbovsky, F. Fournier, B. Lepri, 
<i>A Framework for Verifiable and Auditable Collaborative Anomaly Detection</i>, 
IEEE Access (2022). <a href='https://arxiv.org/abs/2203.07802'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href='https://doi.org/10.1109/ACCESS.2022.3196391'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
Collaborative and Federated Leaning are emerging approaches to manage cooperation between a group of agents for the solution of Machine Learning tasks,  with the goal of improving each agent's performance without disclosing any data.  In this paper we present a novel algorithmic architecture that tackle this problem in the particular case of Anomaly Detection (or classification of rare  events), a setting where typical applications often comprise data with sensible information, but where the scarcity of anomalous examples encourages collaboration.  We show how Random Forests can be used as a tool for the development of accurate classifiers with an effective insight-sharing  mechanism that does not break  the data integrity. Moreover, we explain how the new architecture can be readily integrated in a blockchain infrastructure to ensure the verifiable and auditable execution of the algorithm.  Furthermore, we discuss how this work may set the basis for a more general approach for the design of collaborative ensemble-learning methods beyond the specific  task and  architecture discussed in this paper.	
</blockquote>

<pre>
  <code class="bibtex">
@Article{Santin2022,
  author    = {Santin, Gabriele and Skarbovsky, Inna and Fournier, Fabiana and Lepri, Bruno},
  title     = {A Framework for Verifiable and Auditable Collaborative Anomaly Detection},
  journal   = {IEEE Access},
  year      = {2022},
  pages     = {1-1},
  doi       = {10.1109/ACCESS.2022.3196391},
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary>E. Leoni, G. Cencetti, G. Santin, T. Istomin, D. Molteni, G. P. Picco, E. Farella, B. Lepri, A. M. Murphy, 
<i>Measuring close proximity  interactions in summer camps during the COVID-19 pandemic</i>, 
EPJ Data Science (2022). <a href='https://arxiv.org/abs/2106.14750'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href='https://doi.org/10.1140/epjds/s13688-022-00316-y'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
Policy makers have implemented multiple non-pharmaceutical strategies to mitigate the COVID-19 worldwide crisis. Interventions had the aim of reducing close proximity interactions, which drive the spread of the disease. A deeper knowledge of human physical interactions has revealed necessary, especially in all settings involving children, whose education and gathering activities should be preserved.  Despite their relevance,  almost  no  data  are  available on close proximity  contacts among  children  in  schools  or  other  educational  settings during the pandemic. Contact data are usually gathered via Bluetooth, which nonetheless  offers  a  low  temporal  and  spatial  resolution. Recently, ultra-wideband (UWB) radios emerged as a more accurate alternative that nonetheless exhibits a significantly higher energy consumption, limiting  in-field  studies. In this paper, we leverage a novel approach,embodied by the Janus system that combines these radios by exploiting their complementary benefits.  The very accurate proximity data gathered in-field by Janus, once augmented with several metadata, unlocks unprecedented levels of information, enabling the development of novel multi-level risk analyses. By means of this technology, we have collected real contact data of children and educators in three summer camps during summer 2020in the province of Trento, Italy.  The wide variety of performed daily activities induced multiple individual behaviors, allowing a rich investigation  of  social  environments  from  the  contagion  risk  perspective. We  consider  risk  based  on  duration  and  proximity  of  contacts  and classify  interactions  according  to  different  risk  levels. We can then evaluate the summer camps’ organization,  observe the effect of partition in small groups,  or social bubbles,  and identify the organized activities that mitigate the riskier behaviors. Overall, we offer an insight into the educator-child and child-child social interactions  during  the  pandemic,  thus  providing  a  valuable tool  for  schools,  summer  camps,  and  policy makers to  (re)structure educational activities safely.	
</blockquote>

<pre>
  <code class="bibtex">
@Article{Leoni2022,
  author    = {Leoni, Elia and Cencetti, Giulia and Santin, Gabriele and Istomin, Timofei and Molteni, Davide and Picco, Gian Pietro and Farella, Elisabetta and Lepri, Bruno and Murphy, Amy L.},
  title     = {Measuring close proximity interactions in summer camps during the COVID-19 pandemic},
  journal   = {EPJ Data Science},
  year      = {2022},
  volume    = {11},
  number    = {1},
  month     = {Jan},
  pages     = {5},
  issn      = {2193-1127},
  doi       = {10.1140/epjds/s13688-022-00316-y},
  url       = {https://doi.org/10.1140/epjds/s13688-022-00316-y},
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary>T. Wenzel, M. Kurz, A. Beck, G. Santin, B. Haasdonk, 
<i>Structured Deep Kernel Networks for Data-Driven Closure Terms of  Turbulent Flows</i>, 
Proceedings of the 13th International Conference on Large Scale Scientific Computations (2022). <a href='https://arxiv.org/abs/2103.13655'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href='https://doi.org/10.1007/978-3-030-97549-4_47'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
Standard kernel methods for machine learning usually struggle when dealing with large datasets. We review a recently introduced Structured Deep Kernel Network (SDKN) approach that is capable of dealing with high-dimensional and huge datasets - and enjoys typical standard machine learning approximation properties. We extend the SDKN to combine it with standard machine learning modules and compare it with Neural Networks on the scientific challenge of data-driven prediction of closure terms of turbulent flows. We show experimentally that the SDKNs are capable of dealing with large datasets and achieve near-perfect accuracy on the given application.	
</blockquote>

<pre>
  <code class="bibtex">
@InProceedings{Wenzel2022a,
  author    = {Wenzel, Tizian and Kurz, Marius and Beck, Andrea and Santin, Gabriele and Haasdonk, Bernard},
  title     = {Structured Deep Kernel Networks for Data-Driven Closure Terms of Turbulent Flows},
  booktitle = {Large-Scale Scientific Computing},
  year      = {2022},
  editor    = {Lirkov, Ivan and Margenov, Svetozar},
  publisher = {Springer International Publishing},
  isbn      = {978-3-030-97549-4},
  pages     = {410--418},
  address   = {Cham},
}
  </code>
</pre>
</small>

</details>

</p>




<p style='margin-top:-20px;margin-left:5%;'>
<h3 style='margin-left:5%;'> 2021</h3>
</p>
<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary>G. Santin, B. Haasdonk, 
<i>Kernel Methods for Surrogate  Modeling</i>, 
Model Order Reduction, Volume 1: System- and Data-Driven Methods and Algorithms, P. Benner, W. Schilders, S. Grivet-Talocia, A. Quarteroni, G. Rozza, L.  M. Silveira  Eds. (2021). <a href='https://arxiv.org/abs/1907.10556'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href='https://doi.org/10.1515/9783110498967-009'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
This chapter deals with kernel methods as a special class of techniques for surrogate modeling. Kernel methods have proven to be efficient in machine learning, pattern recognition and signal analysis due to their flexibility, excellent experimental performance and elegant functional. analytic background. These data-based techniques provide so called kernel expansions, i.e., linear combinations of kernel functions which are generated from given input-output point samples that may be arbitrarily scattered. In particular, these techniques are meshless, do not require or depend on a grid, hence are less prone to the curse of dimensionality, even for high-dimensional problems. In contrast to projection-based model reduction, we do not necessarily assume a high-dimensional model, but a general function that models input-output behavior within some simulation context. This could be some micro-model in a multiscale-simulation, some submodel in a coupled system, some initialization function for solvers, coefficient function in PDEs, etc. First, kernel surrogates can be useful if the input-output function is expensive to evaluate, e.g. is a result of a finite element simulation. Here, acceleration can be obtained by sparse kernel expansions. Second, if a function is available only via measurements or a few function evaluation samples, kernel approximation techniques can provide function surrogates that allow global evaluation. We present some important kernel approximation techniques, which are kernel interpolation, greedy kernel approximation and support vector regression. Pseudo-code is provided for ease of reproducibility. In order to illustrate the main features, commonalities and differences, we compare these techniques on a real-world application. The experiments clearly indicate the enormous acceleration potential	
</blockquote>

<pre>
  <code class="bibtex">
@inbook{Santin2021b,
      author    = {Gabriele Santin and Bernard Haasdonk},
      title     = {Kernel methods for surrogate modeling},
      booktitle = {Volume 1 System- and Data-Driven Methods and Algorithms},
      year      = {2021},
      editor    = {Peter Benner and Stefano Grivet-Talocia and Alfio Quarteroni and Gianluigi Rozza and Wil Schilders and Luís Miguel Silveira},
      publisher = {De Gruyter},
      pages     = {311--354},
      doi       = {doi:10.1515/9783110498967-009},
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary>B. Haasdonk, B. Hamzi, G. Santin, D. Wittwar, 
<i>Kernel methods for center manifold approximation and a weak data-based version of the Center Manifold Theorem</i>, 
Physica D: Nonlinear Phenomena (2021). <a href='https://arxiv.org/abs/2012.00338'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href='https://doi.org/10.1016/j.physd.2021.133007'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
For dynamical systems with a non hyperbolic equilibrium, it is possible to significantly simplify the study of stability by means of the center manifold theory. This theory allows to isolate the complicated asymptotic behavior of the system close to the equilibrium point and to obtain meaningful predictions of its behavior by analyzing a reduced order system on the so-called center manifold. Since the center manifold is usually not known, good approximation methods are important as the center manifold theorem states that the stability properties of the origin of the reduced order system are the same as those of the origin of the full order system. In this work, we establish a data-based version of the center manifold theorem that works by considering an approximation in place of an exact manifold. Also the error between the approximated and the original reduced dynamics are quantified. We then use an apposite data-based kernel method to construct a suitable approximation of the manifold close to the equilibrium, which is compatible with our general error theory. The data are collected by repeated numerical simulation of the full system by means of a high-accuracy solver, which generates sets of discrete trajectories that are then used as a training set. The method is tested on different examples which show promising performance and good accuracy.	
</blockquote>

<pre>
  <code class="bibtex">
@article{Haasdonk2021b,
      title     = {Kernel methods for center manifold approximation and a weak data-based version of the Center Manifold Theorem},
      author    = {Bernard Haasdonk and Boumediene Hamzi and Gabriele Santin and Dominik Wittwar},
      journal   = {Physica D: Nonlinear Phenomena},
      volume    = {427},
      pages     = {133007},
      year      = {2021},
      issn      = {0167-2789},
      doi       = {https://doi.org/10.1016/j.physd.2021.133007},
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> B. Haasdonk, T. Wenzel, G. Santin, S. Schmitt, 
<i>Biomechanical surrogate modelling using stabilized vectorial greedy kernel methods</i>, 
 Numerical Mathematics and Advanced Applications ENUMATH 2019, F. J. Vermolen, C. Vuik, Eds (2021). <a href='https://arxiv.org/abs/2004.12670'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' https://doi.org/10.1007/978-3-030-55874-1_49'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
Greedy kernel approximation algorithms are successful techniques for sparse and accurate data-based modelling and function approximation. Based on a recent idea of stabilization (Wenzel et al., A novel class of stabilized greedy kernel approximation algorithms: convergence, stability & uniform point distribution. e-prints. arXiv:1911.04352, 2019) of such algorithms in the scalar output case, we here consider the vectorial extension built on VKOGA (Wirtz and Haasdonk, Dolomites Res Notes Approx 6:83–100, 2013. We introduce the so called $\gamma$-restricted VKOGA, comment on analytical properties and present numerical evaluation on data from a clinically relevant application, the modelling of the human spine. The experiments show that the new stabilized algorithms result in improved accuracy and stability over the non-stabilized algorithms.	
</blockquote>

<pre>
  <code class="bibtex">
@InProceedings{Haasdonk2021a,
  author                   = {Haasdonk, Bernard and Wenzel, Tizian and Santin, Gabriele and Schmitt, Syn},
  title                    = {Biomechanical Surrogate Modelling Using Stabilized Vectorial Greedy Kernel Methods},
  booktitle                = {Numerical Mathematics and Advanced Applications ENUMATH 2019},
  year                     = {2021},
  editor                   = {Vermolen, Fred J. and Vuik, Cornelis},
  publisher                = {Springer International Publishing},
  isbn                     = {978-3-030-55874-1},
  pages                    = {499--508},
  doi      		   = {https://doi.org/10.1007/978-3-030-55874-1_49},
  address                  = {Cham},
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> G. Santin, T. Karvonen, B. Haasdonk, 
<i>Sampling based approximation of linear functionals in Reproducing Kernel Hilbert Spaces</i>, 
 BIT (2021). <a href='https://arxiv.org/abs/2004.00556'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' https://doi.org/10.1007/s10543-021-00870-3'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
In this paper we analyze a greedy procedure to approximate a linear functional defined in a reproducing kernel Hilbert space by nodal values. This procedure computes a quadrature rule which can be applied to general functionals. For a large class of functionals, that includes integration functionals and other interesting cases, but does not include differentiation, we prove convergence results for the approximation by means of quasi-uniform and greedy points which generalize in various ways several known results. A perturbation analysis of the weights and node computation is also discussed. Beyond the theoretical investigations, we demonstrate numerically that our algorithm is effective in treating various integration densities, and that it is even very competitive when compared to existing methods for Uncertainty Quantification.	
</blockquote>

<pre>
  <code class="bibtex">
@Article{Santin2021,
  author    = {Santin, Gabriele and Karvonen, Toni and Haasdonk, Bernard},
  title     = {Sampling based approximation of linear functionals in reproducing kernel Hilbert spaces},
  journal   = {BIT Numerical Mathematics},
  year      = {2021},
  month     = {Apr},
  issn      = {1572-9125},
  doi       = {10.1007/s10543-021-00870-3},
  url       = {https://doi.org/10.1007/s10543-021-00870-3},
  day       = {13},
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> G. Cencetti, G. Santin, A. Longa, E. Pigani, A. Barrat, C. Cattuto, S. Lehmann, M. Salath&eacute;, B. Lepri, 
<i>Digital proximity tracing on empirical contact networks for pandemic control</i>, 
 Nature Commun. (2021). <a href=' https://doi.org/10.1038/s41467-021-21809-w'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' https://doi.org/10.1038/s41467-021-21809-w'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
Digital contact tracing is a relevant tool to control infectious disease outbreaks, including the COVID-19 epidemic. Early work evaluating digital contact tracing omitted important features and heterogeneities of real-world contact patterns influencing contagion dynamics. We fill this gap with a modeling framework informed by empirical high-resolution contact data to analyze the impact of digital contact tracing in the COVID-19 pandemic. We investigate how well contact tracing apps, coupled with the quarantine of identified contacts, can mitigate the spread in real environments. We find that restrictive policies are more effective in containing the epidemic but come at the cost of unnecessary large-scale quarantines. Policy evaluation through their efficiency and cost results in optimized solutions which only consider contacts longer than 15–20 minutes and closer than 2–3 meters to be at risk. Our results show that isolation and tracing can help control re-emerging outbreaks when some conditions are met: (i) a reduction of the reproductive number through masks and physical distance; (ii) a low-delay isolation of infected individuals; (iii) a high compliance. Finally, we observe the inefficacy of a less privacy-preserving tracing involving second order contacts. Our results may inform digital contact tracing efforts currently being implemented across several countries worldwide.	
</blockquote>

<pre>
  <code class="bibtex">
@Article{Cencetti2021,
  author		   = {Cencetti, G. and Santin, G. and Longa, A. and Pigani, E. and Barrat, A. and Cattuto, C. and Lehmann, S. and Salath{\'e}, M. and Lepri, B.},
  title  		   = {Digital proximity tracing on empirical contact networks for pandemic control},
  journal  		   = {Nature Communications},
  year     		   = {2021},
  volume   		   = {12},
  number   		   = {1},
  month     		   = {Mar},
  pages    		   = {1655},
  issn     		   = {2041-1723},
  doi      		   = {10.1038/s41467-021-21809-w},
  url      		   = {https://doi.org/10.1038/s41467-021-21809-w},
  day      		   = {12},
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> T. Wenzel, G. Santin, B. Haasdonk, 
<i>A novel class of stabilized greedy kernel approximation algorithms: Convergence, stability and uniform point distribution</i>, 
 J. of Approx. Theory (2021). <a href='https://arxiv.org/abs/1911.04352'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' https://doi.org/10.1016/j.jat.2020.105508'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
Kernel based methods provide a way to reconstruct potentially high-dimensional functions from meshfree samples, i.e., sampling points and corresponding target values. A crucial ingredient for this to be successful is the distribution of the sampling points. Since the computation of an optimal selection of sampling points may be an infeasible task, one promising option is to use greedy methods.  Although these methods may be very effective, depending on the specific greedy criterion the chosen points might quickly lead to instabilities in the computation. To circumvent this problem, we introduce and investigate a new class of stabilized greedy kernel algorithms, which can be used to create a scale of new selection strategies.  We analyze these algorithms, and in particular we prove convergence results and quantify in a precise way the distribution of the selected points. These results allow to prove, in the case of certain Sobolev kernels, that the algorithms have optimal stability and optimal convergence rates, including for functions outside the native space of the kernel. The results also apply to the case of the usual $P$-greedy algorithm, significantly improving state-of-the-art results available in the literature. Illustrative experiments are presented that support the theoretical findings and show improvements of the stabilized algorithms in terms of accuracy due to improved stability.  	
</blockquote>

<pre>
  <code class="bibtex">

  </code>
</pre>
</small>

</details>

</p>




<p style='margin-top:-20px;margin-left:5%;'>
<h3 style='margin-left:5%;'> 2020</h3>
</p>
<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> B. Haasdonk, B. Hamzi, G. Santin, D. Wittwar, 
<i>Greedy kernel methods for center manifold approximation</i>, 
 Spectral and High Order Methods for Partial Differential Equations ICOSAHOM 2018, S. Sherwin, D. Moxey, J. Peir&oacute;, P. E. Vincent, and C. Schwab Eds. (2020). <a href='https://arxiv.org/abs/1810.11329'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' https://doi.org/10.1007/978-3-030-39647-3_6'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
For certain dynamical systems it is possible to significantly simplify the study of stability by means of the center manifold theory. This theory allows to isolate the complicated asymptotic behavior of the system close to a non-hyperbolic equilibrium point, and to obtain meaningful predictions of its behavior by analyzing a reduced dimensional problem. Since the manifold is usually not known, approximation methods are of great interest to obtain qualitative estimates. In this work, we use a data-based greedy kernel method to construct a suitable approximation of the manifold close to the equilibrium. The data are collected by repeated numerical simulation of the full system by means of a high-accuracy solver, which generates sets of discrete trajectories that are then used to construct a surrogate model of the manifold. The method is tested on different examples which show promising performance and good accuracy.	
</blockquote>

<pre>
  <code class="bibtex">
@InProceedings{Haasdonk2020,
  author                   = {Haasdonk, Bernard and Hamzi, Boumediene and Santin, Gabriele and Wittwar, Dominik},
  title                    = {Greedy Kernel Methods for Center Manifold Approximation},
  booktitle                = {Spectral and High Order Methods for Partial Differential Equations ICOSAHOM 2018},
  year                     = {2020},
  editor                   = {Sherwin, Spencer J. and Moxey, David and Peir{\'o}, Joaquim and Vincent, Peter E. and Schwab, Christoph},
  publisher                = {Springer International Publishing},
  isbn                     = {978-3-030-39647-3},
  pages                    = {95--106},
  doi                      = {10.1007/978-3-030-39647-3_6},
  url                      = {http://doi.org/10.1007/978-3-030-39647-3_6},
  address                  = {Cham},

}
  </code>
</pre>
</small>

</details>

</p>




<p style='margin-top:-20px;margin-left:5%;'>
<h3 style='margin-left:5%;'> 2019</h3>
</p>
<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> T. Br&uuml;nnette, G. Santin, and B. Haasdonk, 
<i>Greedy kernel methods for accelerating implicit integrators for parametric ODEs</i>, 
 Numerical Mathematics and Advanced Applications ENUMATH 2017, F.A. Radu, K. Kumar, I. Berre, J.M. Nordbotten, I.S. Pop (2019). <a href='https://arxiv.org/abs/1802.08106'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' https://doi.org/10.1007/978-3-319-96415-7_84'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
We present a novel acceleration method for the solution of parametric ODEs by single-step implicit solvers by means of greedy kernel-based surrogate models. In an offline phase, a set of trajectories is precomputed with a high-accuracy ODE solver for a selected set of parameter samples, and used to train a kernel model which predicts the next point in the trajectory as a function of the last one. This model is cheap to evaluate, and it is used in an online phase for new parameter samples to provide a good initialization point for the nonlinear solver of the implicit integrator. The accuracy of the surrogate reflects into a reduction of the number of iterations until convergence of the solver, thus providing an overall speedup of the full simulation. Interestingly, in addition to providing an acceleration, the accuracy of the solution is maintained, since the ODE solver is still used to guarantee the required precision. Although the method can be applied to a large variety of solvers and different ODEs, we will present in details its use with the Implicit Euler method for the solution of the Burgers equation, which results to be a meaningful test case to demonstrate the method’s features.	
</blockquote>

<pre>
  <code class="bibtex">
@InProceedings{Bruennette2019,
  Title                    = {Greedy Kernel Methods for Accelerating Implicit Integrators for Parametric {ODE}s},
  Author                   = {Br{\"u}nnette, Tim and Santin, Gabriele and Haasdonk, Bernard},
  Booktitle                = {Numerical Mathematics and Advanced Applications - ENUMATH 2017},
  Year                     = {2019},

  Address                  = {Cham},
  Editor                   = {Radu, Florin Adrian and Kumar, Kundan and Berre, Inga and Nordbotten, Jan Martin and Pop, Iuliu Sorin},
  Pages                    = {889--896},
  Publisher                = {Springer International Publishing},
  ISBN                     = {978-3-319-96415-7},
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary>M. K&ouml;ppel, F. Franzelin, I. Kr&ouml;ker, G. Santin, D. Wittwar, S. Oladyshkin, A. Barth, B. Haasdonk, W. Nowak, D. Pfl&uuml;ger, C. Rohde, 
<i>Comparison of data-driven uncertainty quantification methods for a carbon dioxide storage benchmark scenario</i>, 
 Comput. Geosci (2019). <a href='https://arxiv.org/abs/1802.03064'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' https://doi.org/10.1007/s10596-018-9785-x'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
A variety of methods is available to quantify uncertainties arising within the modeling of flow and transport in carbon dioxide storage, but there is a lack of thorough comparisons. Usually, raw data from such storage sites can hardly be described by theoretical statistical distributions since only very limited data is available. Hence, exact information on distribution shapes for all uncertain parameters is very rare in realistic applications. We discuss and compare four different methods tested for data-driven uncertainty quantification based on a benchmark scenario of carbon dioxide storage. In the benchmark, for which we provide data and code, carbon dioxide is injected into a saline aquifer modeled by the nonlinear capillarity-free fractional flow formulation for two incompressible fluid phases, namely carbon dioxide and brine. To cover different aspects of uncertainty quantification, we incorporate various sources of uncertainty such as uncertainty of boundary conditions, of parameters in constitutive relations, and of material properties. We consider recent versions of the following non-intrusive and intrusive uncertainty quantification methods: arbitrary polynomial chaos, spatially adaptive sparse grids, kernel-based greedy interpolation, and hybrid stochastic Galerkin. The performance of each approach is demonstrated assessing expectation value and standard deviation of the carbon dioxide saturation against a reference statistic based on Monte Carlo sampling. We compare the convergence of all methods reporting on accuracy with respect to the number of model runs and resolution. Finally, we offer suggestions about the methods’ advantages and disadvantages that can guide the modeler for uncertainty quantification in carbon dioxide storage and beyond.	
</blockquote>

<pre>
  <code class="bibtex">
@Article{Koeppel2019,
  Title                    = {Comparison of data-driven uncertainty quantification methods for a carbon dioxide storage benchmark scenario},
  Author                   = {K{\"o}ppel, Markus and Franzelin, Fabian and Kr{\"o}ker, Ilja and Oladyshkin, Sergey and Santin, Gabriele and Wittwar, Dominik and Barth, Andrea and Haasdonk, Bernard and Nowak, Wolfgang and Pfl{\"u}ger, Dirk and Rohde, Christian},
  Journal                  = {Computational Geosciences},
  Year                     = {2019},
  Month                    = {Apr},
  Number                   = {2},
  Pages                    = {339--354},
  Volume                   = {23},
  Day                      = {01},
  Doi                      = {10.1007/s10596-018-9785-x},
  Url                      = {https://doi.org/10.1007/s10596-018-9785-x}
}
  </code>
</pre>
</small>

</details>

</p>




<p style='margin-top:-20px;margin-left:5%;'>
<h3 style='margin-left:5%;'> 2018</h3>
</p>
<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> D. Wittwar, G. Santin, B. Haasdonk, 
<i>Interpolation with uncoupled separable matrix-valued kernels</i>, 
 Dolomites Res. Notes Approx. (2018). <a href='https://arxiv.org/abs/1807.09111'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' http://dx.doi.org/10.14658/pupj-drna-2018-3-4'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
In this paper we consider the problem of approximating vector-valued functions over a domain $\Omega$. For this purpose, we use matrix-valued reproducing kernels, which can be related to Reproducing kernel Hilbert spaces of vectorial functions and which can be viewed as an extension of the scalar-valued case. These spaces seem promising, when modelling correlations between the target function components, as the components are not learned independently of each other. We focus on the interpolation with such matrix-valued kernels. We derive error bounds for the interpolation error in terms of a generalized power-function and we introduce a subclass of matrix-valued kernels whose power-functions can be traced back to the power-function of scalar-valued reproducing kernels. Finally, we apply these kind of kernels to some artificial data to illustrate the benefit of interpolation with matrix-valued kernels in comparison to a componentwise approach. 	
</blockquote>

<pre>
  <code class="bibtex">
@Article{Wittwar2018,
  Title                    = {Interpolation with uncoupled separable matrix-valued kernels},
  Author                   = {Wittwar, Dominik and Santin, Gabriele and Haasdonk, Bernard},
  Journal                  = {Dolomites Res. Notes Approx.},
  Year                     = {2018},
  Pages                    = {23--29},
  Volume                   = {11},
  Doi                      = {10.14658/pupj-drna-2018-3-4},
  Fjournal                 = {Dolomites Research Notes on Approximation},
  Sjournal                 = {Dolomites Res.\ Notes Approx.},
  Url                      = {https://drna.padovauniversitypress.it/2018/3/4}
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> T. K&ouml;ppl, G. Santin, B. Haasdonk, R. Helmig, 
<i>Numerical modelling of a peripheral arterial stenosis using dimensionally  reduced models and kernel methods</i>, 
 Int. J. Numer. Meth. Biomed. Engng. (2018). <a href='https://arxiv.org/abs/1802.04628'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' https://doi.org/10.1002/cnm.3095'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
In this work, we consider 2 kinds of model reduction techniques to simulate blood flow through the largest systemic arteries, where a stenosis is located in a peripheral artery, i.e., in an artery that is located far away from the heart. For our simulations, we place the stenosis in one of the tibial arteries belonging to the right lower leg (right posterior tibial artery). The model reduction techniques that are used are on the one hand dimensionally reduced models (1-D and 0-D models, the so-called mixed-dimension model) and on the other hand surrogate models produced by kernel methods. Both methods are combined in such a way that the mixed-dimension models yield training data for the surrogate model, where the surrogate model is parametrised by the degree of narrowing of the peripheral stenosis. By means of a well-trained surrogate model, we show that simulation data can be reproduced with a satisfactory accuracy and that parameter optimisation or state estimation problems can be solved in a very efficient way. Furthermore, it is demonstrated that a surrogate model enables us to present after a very short simulation time the impact of a varying degree of stenosis on blood flow, obtaining a speedup of several orders over the full model.	
</blockquote>

<pre>
  <code class="bibtex">
@Article{Koeppl2018,
  Title                    = {Numerical modelling of a peripheral arterial stenosis using dimensionally reduced models and kernel methods},
  Author                   = {K{\"o}ppl, Tobias and Santin, Gabriele and Haasdonk, Bernard and Helmig, Rainer},
  Journal                  = {International Journal for Numerical Methods in Biomedical Engineering},
  Year                     = {2018},
  Note                     = {e3095 cnm.3095},
  Number                   = {8},
  Pages                    = {e3095},
  Volume                   = {34},
  Doi                      = {10.1002/cnm.3095},
  Eprint                   = {https://onlinelibrary.wiley.com/doi/pdf/10.1002/cnm.3095},
  Keywords                 = {blood flow simulations, peripheral stenosis, dimensionally reduced models, mixed‐dimension models, kernel methods, surrogate models, real‐time simulations},
  Url                      = {https://onlinelibrary.wiley.com/doi/abs/10.1002/cnm.3095}
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> S. De Marchi, A. Iske, G. Santin, 
<i>Image reconstruction from scattered Radon data by weighted positive definite kernel functions</i>, 
 Calcolo (2018). <a href='https://www.math.uni-hamburg.de/home/iske/papers/rbfradon_final.pdf'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' https://doi.org/10.1007/s10092-018-0247-6'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
 Proceedings of Approximation Theory 15, San Antonio (Texas), Springer Proceedings on Mathematics and Statistics	
</blockquote>

<pre>
  <code class="bibtex">
@Article{DeMarchi2018,
  Title                    = {Image reconstruction from scattered Radon data by weighted positive definite kernel functions},
  Author                   = {De Marchi, S. and Iske, A. and Santin, G.},
  Journal                  = {Calcolo},
  Year                     = {2018},
  Month                    = {Feb},
  Number                   = {1},
  Pages                    = {2},
  Volume                   = {55},
  Day                      = {02},
  Doi                      = {10.1007/s10092-018-0247-6},
  ISSN                     = {1126-5434},
  Url                      = {https://doi.org/10.1007/s10092-018-0247-6}
}

﻿
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> G. Santin, B. Haasdonk, 
<i>Greedy kernel approximation for sparse surrogate modelling</i>, 
 Reduced-Order Modeling (ROM) for Simulation and Optimization: Powerful Algorithms as Key Enablers for Scientific Computing, W. Keiper, A. Milde, and S. Volkwein, Eds (2018). <a href=''> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' https://doi.org/10.1007/978-3-319-75319-5_2'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
Modern simulation scenarios frequently require multi-query or real-time responses of simulation models for statistical analysis, optimization, or process control. However, the underlying simulation models may be very time-consuming rendering the simulation task difficult or infeasible. This motivates the need for rapidly computable surrogate models. We address the case of surrogate modeling of functions from vectorial input to vectorial output spaces. These appear, for instance, in simulation of coupled models or in the case of approximating general input–output maps. We review some recent methods and theoretical results in the field of greedy kernel approximation schemes. In particular, we recall the vectorial kernel orthogonal greedy algorithm (VKOGA) for approximating vector-valued functions. We collect some recent convergence statements that provide sound foundation for these algorithms, in particular quasi-optimal convergence rates in case of kernels inducing Sobolev spaces. We provide some initial experiments that can be obtained with non-symmetric greedy kernel approximation schemes. The results indicate better stability and overall more accurate models in situations where the input data locations are not equally distributed.	
</blockquote>

<pre>
  <code class="bibtex">
@InCollection{Haasdonk2018,
  Title                    = {Greedy Kernel Approximation for Sparse Surrogate Modeling},
  Author                   = {Haasdonk, Bernard and Santin, Gabriele},
  Booktitle                = {Reduced-Order Modeling (ROM) for Simulation and Optimization: Powerful Algorithms as Key Enablers for Scientific Computing},
  Publisher                = {Springer International Publishing},
  Year                     = {2018},
  Address                  = {Cham},
  Editor                   = {Keiper, Winfried and Milde, Anja and Volkwein, Stefan},
  Pages                    = {21--45},
  Doi                      = {10.1007/978-3-319-75319-5_2},
  ISBN                     = {978-3-319-75319-5},
  Url                      = {https://doi.org/10.1007/978-3-319-75319-5_2}
}
  </code>
</pre>
</small>

</details>

</p>




<p style='margin-top:-20px;margin-left:5%;'>
<h3 style='margin-left:5%;'> 2017</h3>
</p>
<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> S. De Marchi, A. Idda, G. Santin, 
<i>A rescaled method for RBF approximation</i>, 
 Proceedings of Approximation Theory 15, San Antonio (Texas), Springer Proceedings on Mathematics and Statistics (2017). <a href='https://arxiv.org/abs/1611.10034'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' https://doi.org/10.1007/978-3-319-59912-0_3'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
In the recent paper [1], a new method to compute stable kernel-based interpolants has been presented. This rescaled interpolation method combines the standard kernel interpolation with a properly defined rescaling operation, which smooths the oscillations of the interpolant. Although promising, this procedure lacks a systematic theoretical investigation. Through our analysis, this novel method can be understood as standard kernel interpolation by means of a properly rescaled kernel. This point of view allows us to consider its error and stability properties.	
</blockquote>

<pre>
  <code class="bibtex">
@InBook{DeMarchi2017,
  Title                    = {A Rescaled Method for RBF Approximation},
  Author                   = {De Marchi, Stefano and Idda, Andrea and Santin, Gabriele},
  Editor                   = {Fasshauer, Gregory E. and Schumaker, Larry L.},
  Pages                    = {39--59},
  Publisher                = {Springer International Publishing},
  Year                     = {2017},
  Address                  = {Cham},
  Booktitle                = {Approximation Theory XV: San Antonio 2016},
  Doi                      = {10.1007/978-3-319-59912-0_3},
  ISBN                     = {978-3-319-59912-0},
  Url                      = {https://doi.org/10.1007/978-3-319-59912-0_3}
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> G. Santin, B. Haasdonk, 
<i>Convergence rate of the data-independent P-greedy algorithm in kernel-based spaces</i>, 
 Dolomites Res. Notes Approx. (2017). <a href='https://arxiv.org/abs/1612.02672'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' http://dx.doi.org/10.14658/pupj-drna-2017-Special_Issue-9'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
Kernel-based methods provide flexible and accurate algorithms for the reconstruction of functions from meshless samples. A major question in the use of such methods is the influence of the samples’ locations on the behavior of the approximation, and feasible optimal strategies are not known for general problems.Nevertheless, efficient and greedy point-selection strategies are known. This paper gives a proof of the convergence rate of the data-independent P-greedy algorithm, based on the application of the convergence theory for greedy algorithms in reduced basis methods. The resulting rate of convergence is shown to be quasi-optimal in the case of kernels generating Sobolev spaces.As a consequence, this convergence rate proves that, for kernels of Sobolev spaces, the points selected by the algorithm are asymptotically uniformly distributed, as conjectured in the paper where the algorithm has been introduced.	
</blockquote>

<pre>
  <code class="bibtex">
@Article{Santin2016b,
  Title                    = {Convergence rate of the data-independent {P}-greedy algorithm in kernel-based approximation},
  Author                   = {G. Santin and B. Haasdonk},
  Journal                  = {Dolomites Res. Notes Approx.},
  Year                     = {2017},
  Pages                    = {68--78},
  Volume                   = {10},
  Fjournal                 = {Dolomites Research Notes on Approximation},
  Sjournal                 = {Dolomites Res.\ Notes Approx.},
  Url                      = {www.emis.de/journals/DRNA/9-2.html}
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> R. Cavoretto, S. De Marchi, A. De Rossi, E. Perracchione, G. Santin, 
<i>Partition of unity interpolation using stable kernel-based techniques</i>, 
 Appl. Numer. Math. (2017). <a href='https://arxiv.org/abs/1607.03278'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' https://doi.org/10.1016/j.apnum.2016.07.005'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
In this paper we propose a new stable and accurate approximation technique which is extremely effective for interpolating large scattered data sets. The Partition of Unity (PU) method is performed considering Radial Basis Functions (RBFs) as local approximants and using locally supported weights. In particular, the approach consists in computing, for each PU subdomain, a stable basis. Such technique, taking advantage of the local scheme, leads to a significant benefit in terms of stability, especially for flat kernels. Furthermore, an optimized searching procedure is applied to build the local stable bases, thus rendering the method more efficient.	
</blockquote>

<pre>
  <code class="bibtex">
@Article{Cavoretto2016b,
  Title                    = {Partition of unity interpolation using stable kernel-based techniques},
  Author                   = {Cavoretto, Roberto and De Marchi, Stefano and De Rossi, Alessandra and Perracchione, Emma and Santin, Gabriele},
  Journal                  = {Applied Numerical Mathematics},
  Year                     = {2016},
  Doi                      = {10.1016/j.apnum.2016.07.005},
  Url                      = {http://dx.doi.org/10.1016/j.apnum.2016.07.005}
}
  </code>
</pre>
</small>

</details>

</p>




<p style='margin-top:-20px;margin-left:5%;'>
<h3 style='margin-left:5%;'> 2016</h3>
</p>
<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> R. Cavoretto, S. De Marchi, A. De Rossi, E. Perracchione, G. Santin, 
<i>Approximating basins of attraction for dynamical systems via stable radial bases</i>, 
 AIP Conf. Proc. (2016). <a href='https://www.math.unipd.it/~demarchi/papers/ICNAAM15.pdf'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' https://doi.org/10.1063/1.4952177'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
In applied sciences it is often required to model and supervise temporal evolution of populations via dynamical systems. In this paper, we focus on the problem of approximating the basins of attraction of such models for each stable equilibrium point. We propose to reconstruct the basins via an implicit interpolant using stable radial bases, obtaining the surfaces by partitioning the phase space into disjoint regions. An application to a competition model presenting jointly three stable equilibria is considered. 	
</blockquote>

<pre>
  <code class="bibtex">
@InProceedings{Cavoretto2016a,
  Title                    = {Approximating basins of attraction for dynamical systems via stable radial bases},
  Author                   = {Cavoretto, Roberto and De Marchi, Stefano and De Rossi, Alessandra and Perracchione, Emma and Santin, Gabriele},
  Booktitle                = {AIP Conf. Proc.},
  Year                     = {2016},
  Doi                      = {10.1063/1.4952177},
  Url                      = {http://dx.doi.org/10.1063/1.4952177}
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> G. Santin, R. Schaback, 
<i>Approximation of eigenfunctions in kernel-based spaces</i>, 
 Adv. Comput. Math. (2016). <a href='https://arxiv.org/abs/1411.7656'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' https://doi.org/10.1007/s10444-015-9449-5'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
Kernel-based methods in Numerical Analysis have the advantage of yielding optimal recovery processes in the “native” Hilbert space $\mathcal H$ in which they are reproducing. Continuous kernels on compact domains have an expansion into eigenfunctions that are both $L_2$-orthonormal and orthogonal in $\mathcal H$ (Mercer expansion). This paper examines the corresponding eigenspaces and proves that they have optimality properties among all other subspaces of $\mathcal H$. These results have strong connections to $n$-widths in Approximation Theory, and they establish that errors of optimal approximations are closely related to the decay of the eigenvalues. Though the eigenspaces and eigenvalues are not readily available, they can be well approximated using the standard $n$-dimensional subspaces spanned by translates of the kernel with respect to $n$ nodes or centers. We give error bounds for the numerical approximation of the eigensystem via such subspaces. A series of examples shows that our numerical technique via a greedy point selection strategy allows to calculate the eigensystems with good accuracy.	
</blockquote>

<pre>
  <code class="bibtex">
@Article{Santin2016a,
  author    = {Santin, Gabriele and Schaback, Robert},
  title     = {Approximation of eigenfunctions in kernel-based spaces},
  journal   = {Adv. Comput. Math.},
  year      = {2016},
  volume    = {42},
  number    = {4},
  pages     = {973--993},
  issn      = {1572-9044},
  doi       = {10.1007/s10444-015-9449-5},
  url       = {http://dx.doi.org/10.1007/s10444-015-9449-5},
  fjournal  = {Advances in Computational Mathematics},
}
  </code>
</pre>
</small>

</details>

</p>




<p style='margin-top:-20px;margin-left:5%;'>
<h3 style='margin-left:5%;'> 2015</h3>
</p>
<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> S. De Marchi, G. Santin, 
<i>Fast computation of orthonormal basis for RBF spaces through Krylov space methods</i>, 
 BIT (2015). <a href='http://www.math.unipd.it/~demarchi/papers/FCoOB.pdf'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' https://doi.org/10.1007/s10543-014-0537-6'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
In recent years, in the setting of radial basis function, the study of approximation algorithms has particularly focused on the construction of (stable) bases for the associated Hilbert spaces. One of the ways of describing such spaces and their properties is the study of a particular integral operator and its spectrum. We proposed in a recent work the so-called WSVD basis, which is strictly connected to the eigen-decomposition of this operator and allows to overcome some problems related to the stability of the computation of the approximant for a wide class of radial kernels. Although effective, this basis is computationally expensive to compute. In this paper we discuss a method to improve and compute in a fast way the basis using methods related to Krylov subspaces. After reviewing the connections between the two bases, we concentrate on the properties of the new one, describing its behavior by numerical tests.	
</blockquote>

<pre>
  <code class="bibtex">
@Article{DeMarchi2015a,
  Title                    = {Fast computation of orthonormal basis for RBF spaces through Krylov space methods},
  Author                   = {De Marchi, Stefano and Santin, Gabriele},
  Journal                  = {BIT Numerical Mathematics},
  Year                     = {2015},
  Number                   = {4},
  Pages                    = {949--966},
  Volume                   = {55},
  Doi                      = {10.1007/s10543-014-0537-6},
  ISSN                     = {0006-3835},
  Publisher                = {Springer Netherlands},
  Url                      = {http://dx.doi.org/10.1007/s10543-014-0537-6}
}
  </code>
</pre>
</small>

</details>

</p>



<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> R. Cavoretto, S. De Marchi, A. De Rossi, E. Perracchione, G. Santin, 
<i>RBF approximation of large datasets by partition of unity and local stabilization</i>, 
 CMMSE 2015: Proceedings of the 15th International Conference on  Mathematical Methods in Science and Engineering (2015). <a href='https://www.math.unipd.it/~demarchi/papers/Latex_template_cmmse.pdf'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' https://iris.unito.it/retrieve/handle/2318/1526172/55702/CMMSE_2015.pdf'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
We present an algorithm to approximate large datasets by Radial Basis Function(RBF) techniques. The method couples a fast domain decomposition procedure with a localized stabilization method. The resulting algorithm can efficiently deal with large problems and it is robust with respect to the typical instability of kernel methods.	
</blockquote>

<pre>
  <code class="bibtex">
@InProceedings{Cavoretto2015,
  Title                    = {RBF approximation of large datasets by partition of unity and local stabilization},
  Author                   = {Cavoretto, Roberto and De Marchi, Stefano and De Rossi, Alessandra and Perracchione, Emma and Santin, Gabriele},
  Booktitle                = {CMMSE 2015 : Proceedings of the 15th International Conference on Mathematical Methods in Science and Engineering},
  Year                     = {2015},
  Editor                   = {Vigo-Aguiar, J.},
  Pages                    = {317--326},
  ISBN                     = {978-84-617-2230-3},
  ISSN                     = {2312-0177},
}
  </code>
</pre>
</small>

</details>

</p>




<p style='margin-top:-20px;margin-left:5%;'>
<h3 style='margin-left:5%;'> 2013</h3>
</p>
<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> S. De Marchi, G. Santin, 
<i>A new stable basis for radial basis function interpolation</i>, 
 J. Comput. Appl. (2013). <a href='https://arxiv.org/abs/1210.1682'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' https://doi.org/10.1016/j.cam.2013.03.048'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
It is well-known that radial basis function interpolants suffer of bad conditioning if the basis of translates is used. In the recent work [5], the authors gave a quite general way to build stable and orthonormal bases for the native space ${\mathcal{N}_{\Phi}(\Omega)}$ associated to a  kernel $\Phi$ on a domain  $\Omega \subset \mathbb{R}^s$. The method is simply based on the factorization of the corresponding kernel matrix.  \\Starting from that setting we describe a particular basis which turns out to be orthonormal in ${\mathcal{N}_{\Phi}(\Omega)}$  and in $\ell_{2,w}(X)$, where $X$ is a set of data sites of the domain $\Omega$. The basis arises from a weighted singular value decomposition of the kernel matrix. This  basis is also related to a discretization of the compact operator $T_{\Phi}: {\mathcal{N}_{\Phi}(\Omega)}\rightarrow{\mathcal{N}_{\Phi}(\Omega)}$,  $$T_{\Phi}[f](x) = \int_{\Omega} \Phi(x,y) f(y) dy\quad \forall x\in\Omega$$ and provides a connection with the continuous basis that arises from an  eigen-decomposition of $T_{\Phi}$.  Finally, using the eigenvalues of this operator,  we provide convergence estimates and stability bounds for interpolation and discrete least-squares approximation.	
</blockquote>

<pre>
  <code class="bibtex">
@Article{DeMarchi2013,
  Title                    = {A new stable basis for radial basis function interpolation},
  Author                   = {De Marchi, Stefano and Santin, Gabriele},
  Journal                  = {J. Comput. Appl. Math.},
  Year                     = {2013},
  Pages                    = {1--13},
  Volume                   = {253},
  Doi                      = {10.1016/j.cam.2013.03.048},
  Fjournal                 = {Journal of Computational and Applied Mathematics},
  ISSN                     = {0377--0427},
  Url                      = {http://dx.doi.org/10.1016/j.cam.2013.03.048}
}
  </code>
</pre>
</small>

</details>

</p>




<p style='margin-top:-20px;margin-left:5%;'>
<h3 style='margin-left:5%;'> 2011</h3>
</p>
<p style="margin-top:-20px;"><details style="margin-left:5%;">

<summary> G. Santin, A. Sommariva, M. Vianello, 
<i>An algebraic cubature formula on curvilinear polygons</i>, 
 Appl. Math. Comput. (2011). <a href='https://www.math.unipd.it/~alvise/PAPERS/AnAlgebraicCubatureFormulaOnCurvilinearPolygons.pdf'> <i class="fa fa-file-pdf"></i> Preprint </a> <a href=' https://doi.org/10.1016/j.amc.2011.04.071'> <i class="ai ai-doi"> </i>DOI</a>
</summary>

<small>

<blockquote>
We implement in Matlab a Gauss-like cubature formula on bivariate domains whose boundary is a piecewise smooth Jordan curve (curvilinear polygons). The key tools are Green’s integral formula, together with the recent software package Chebfun to approximate the boundary curve close to machine precision by piecewise Chebyshev interpolation. Several tests are presented, including some comparisons of this new routine ChebfunGauss with the recent SplineGauss that approximates the boundary by splines.	
</blockquote>

<pre>
  <code class="bibtex">
@Article{Santin2011,
  Title                    = {An algebraic cubature formula on curvilinear polygons},
  Author                   = {Santin, Gabriele and Sommariva, Alvise and Vianello, Marco},
  Journal                  = {Applied Mathematics and Computation},
  Year                     = {2011},
  Number                   = {24},
  Pages                    = {10003--10015},
  Volume                   = {217},
  Doi                      = {10.1016/j.amc.2011.04.071},
  Fjournal                 = {Appl. Math. Comput.},
  ISSN                     = {0096-3003},
  Mrclass                  = {65D30 (65D32)},
  Mrnumber                 = {2806387},
  Url                      = {http://dx.doi.org/10.1016/j.amc.2011.04.071}
}
  </code>
</pre>
</small>

</details>

</p>


