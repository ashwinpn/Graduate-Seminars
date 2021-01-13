# Graduate Seminars and Courses, Mathematics and Data Group
Grad Seminars I attended at NYU Courant.

The Mad (Math and Data) group was created in fall 2016 by Afonso Bandeira, Joan Bruna and Carlos Fernandez-Granda, three Assistant Professors at the Courant Institute of Mathematical Sciences and the Center for Data Science at New York University.

Location: <ins> 60 5th Avenue [NYU Center for Data Science] </ins>

![cds](https://github.com/ashwinpn/Graduate-Seminars/blob/main/cds.png)

## Spring 2020

### Seminar - On the Effectiveness of Richardson Extrapolation in Machine Learning (Francis Bach, INRIA and Ecole Normale Superieure)

Richardson extrapolation is a classical technique from numerical analysis that can improve the approximation error of an estimation method by combining linearly several estimates obtained from different values of one of its hyperparameters, without the need to know in details the inner structure of the original estimation method. The main goal of this presentation is to study when Richardson extrapolation can be used within machine learning. We identify two situations where Richardson interpolation can be useful: (1) when the hyperparameter is the number of iterations of an existing iterative optimization algorithm, with applications to averaged gradient descent and Frank-Wolfe algorithms, and (2) when it is a regularization parameter, with applications to Nesterov smoothing techniques for minimizing non-smooth functions and ridge regression. In all these cases, I will show that extrapolation techniques come with no significant loss in performance, but with sometimes strong gains.

### Seminar - Overlap Gap Property: a Provable Barrier to Fast Optimization in Probabilistic Combinatorial Structures (David Gamarnik, MIT)

Many combinatorial optimization problems defined on random instances exhibit an apparent gap between the optimal values, which can be computed by non-constructive means, and the best values achievable by fast (polynomial time) algorithms. Through a combined effort of mathematicians, computer scientists and statistical physicists, it became apparent that a potential barrier for designing fast algorithms bridging this gap is an intricate topology of nearly optimal solutions, in particular the presence of the Overlap Gap Property (OGP), which we will introduce in this talk. We will discuss how for many such problems the onset of the OGP phase transition introduces indeed a provable barrier to a broad class of polynomial time algorithms. Examples of such problems include the problem of finding a largest independent set of a random graph, finding a largest cut in a random hypergrah, the problem of finding a ground state of a p-spin model, and also many problems in high-dimensional statistics field. In this talk we will demonstrate in particular why OGP is a barrier for three classes of algorithms designed to find a near ground state in p-spin models arising in the field of spin glass theory: Approximate Message Passing algorithms, algorithms based on low-degree polynomial and Langevin dynamics. Joint work with Aukosh Jagannath and Alex Wein.

### Seminar - Statistical and Computational aspects of Wasserstein Barycenters (Philippe Rigollet, MIT)

The notion of average is central to most statistical methods. In this talk we study a generalization of this notion over the non-Euclidean space of probability measures equipped with a certain Wasserstein distance. This generalization is often called Wasserstein Barycenters and empirical evidence suggests that these barycenters allow to capture interesting notions of averages in graphics, data assimilation and morphometrics. However the statistical (rates of convergence) and computational (efficient algorithms) for these Wasserstein barycenters are largely unexplored. The goal of this talk is to review two recent results: 
- 1. Fast rates of convergence for empirical barycenters in general geodesic spaces, and, 
- 2. Provable guarantees for gradient descent and stochastic gradient descent to compute Wasserstein barycenters. Both results leverage geometric aspects of optimal transport.

Based on joint works (arXiv:1908.00828, arXiv:2001.01700) with Chewi, Le Gouic, Maunu, Paris, and Stromme.

## Fall 2020

### Seminar - Constantinos Daskalakis (MIT): Equilibrium Computation and the Foundations of Deep Learning

Speaker : Constantinos Daskalakis [http://people.csail.mit.edu/costis/]

Video : https://www.youtube.com/watch?v=2l5OAEyF17o

Deep Learning has recently yielded important advances in single-agent learning challenges, much of that progress being fueled by the empirical success of gradient descent and its variants in computing local optima of non-convex optimization problems. In multi-agent learning applications, the role of single-objective optimization is played by equilibrium computation, yet our understanding of its complexity in settings that are relevant for Deep Learning remains sparse. In this talk we focus on min-max optimization of nonconvex-nonconcave objectives, which has found applications in GANs, and other adversarial learning problems. Here, not only are there no known gradient-descent based methods converging to even local and approximate min-max equilibria, but the computational complexity of identifying them remains poorly understood. We show that finding approximate local min-max equilibria of Lipschitz and smooth objectives requires a number of queries to the function and its gradient that is exponential in the relevant parameters, in sharp contrast to the polynomial number of queries required to find approximate local minima of non-convex objectives. Our oracle lower bound is a byproduct of a complexity-theoretic result showing that finding approximate local min-max equilibria is computationally equivalent to finding Brouwer fixed points, and Nash equilibria in non zero-sum games, and thus PPAD-complete. Minimal complexity theory knowledge will be assumed in the talk.

Joint work with Stratis Skoulakis and Manolis Zampetakis.

### Seminar - Anna Seigal (University of Oxford): Algebraic methods in statistics and data analysis
Speaker : Anna Seigal [https://people.maths.ox.ac.uk/seigal/]

Algebraic structure is at the heart of many problems in statistics and data analysis. We aim to fit data to a model, or to approximate data by a point on some locus of interest. I will discuss how algebraic structure can be used to capture the existence and uniqueness of a solution to these problems, as well as to suggest suitable algorithms. I will first consider parameter estimation in statistical models via maximum likelihood estimation. We will see connections between maximum likelihood estimation and invariant theory. I will then discuss tensors, the higher dimensional analogues of matrices. The loci of tensors that are of interest in applications often define semi-algebraic sets, given by polynomial equations and inequalities. One example is the signature, tensors that can be used to encode a path of time series data. We will see the algebraic structure that relates a path to its signature.

# Graduate Seminars and Courses, Courant Institute of Mathematical Sciences

Location: <ins> 251 Mercer St # 801, New York, NY 10012 [beside Gould Plaza] </ins>

### Advanced Topics in Numerical Analysis: Convex and Non-smooth Optimization [CSCI-GA.2945-001]
