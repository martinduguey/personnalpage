---
layout: default
---
After getting my french Baccalaureate in 2016, I decided to develop my scientific knowledge by studying Mathematics, Physics and Engineering Sciences 
through intensive courses preparing for french Engineering Schools (CPGE). It allowed me to create an interest in Applied Mathematics and helped me 
being received at Sup Galilée Engineering School in MACS programm, Applied Mathematics and Scientific Calculus. 
Deeply interested in quantitative finance, I am currently working in a consulting firm that provides tools and analytics for 
risk management (IPV, PVA and Reserves related topics) after graduating from the Université Paris Cité with a Master 2 degree in
Random Modelling, Finance and Statistics (ex-DEA Laure ELIE).

# Projects

### Calibration and simulation of the Heston model
Improvement of the internal pricing tool by adding the Heston model. Study and implementation of diffusion schemes.
Comparison and implementation of several methods to calculate Heston's analytical formula for vanilla options. 
Use of several calibration procedure, including market surface interpolation with SVI and variance Swaps approach.

[Available here](./Projects/memoire_DUGUEY_Martin.pdf).

### Unsupervised learning for space equation on unstructured mesh
Study of several parameters of the finite volume space discretization in a compressible steady Euler case and use of gaussian process regression and efficient global optimization 
to find optimal values according to a specific criterion.

[Available here](./Projects/Rapport_DUGUEY_Martin.pdf).

Supervisor: [Jacques Peter](./https://www.onera.fr/en/staff/jacques-peter), Ph.D, accredidation to supervise research (HDR) – ONERA The French Aerospace Lab, DAAA Department, DEFI Unit.

### Numerical solution of a coupled thermal-neutronic problem
Study of the operation of a nuclear reactor requiring the simultaneous use of two types of phenomena: one, thermal, and the other, neutronic. These two models can be written as a coupled system of two equations. 
Analytical solution of the system of two equations, which coupled together form a non-linear differential equation.

[Available here](./Projects/DUGUEY_Martin_StageMAP5.pdf).

Supervisor: [Olivier Lafitte](./https://www.math.univ-paris13.fr/~lafitte/wiki/index.php?n=Main.HomePage), Director of the International Joint Unit 3457 and Researcher at LAGA UMR 7539, Sorbonne Paris Nord University.

### Domain decomposition with Schwarz's algorithm
Study of both steady and unsteady advection-diffusion problems throughout Schwarz's algorithm iterations with Robin's boundary condition. Well-posedness study, numerical implementation and convergence's proof with an energy method. Work done with [Imad BADDA](./https://www.linkedin.com/in/imad-badda/).

[Available here](./Projects/Projet_DD_MACS_2.pdf).

Supervisor: [Caroline Japhet](./https://www.math.univ-paris13.fr/~japhet/cjaphetmain.htm), CNRS, UMR 7539, LAGA, Université Sorbonne Paris Nord.

# Exercises

1.  American options pricing
2.  Numerical Finance
3.  Implementation of a multi-layer perceptron model with Numpy for Call Option Pricing
4.  Beta distribution adjustment
5.  Analysis of components failure's Data
6.  Simulation of an outbreak's spread
7.  A nuclear power plant game using Object-Oriented Programming
8.  Payment of public transport's ticket with QRCode

### American options pricing
Study and development of the Longstaff-Schwartz's algorithm as well as tests cases on different options. Work done with 
<a href="https://www.linkedin.com/in/chloé-amar-30569a199/">Chloé AMAR</a>.

[PDF](./Exercises/American_Pricing_project.pdf).

### Numerical Finance
Study of several europeans options (asian option, delayed start option). Computation of the estimation price of an american option with Longstaff-Schwartz's algorithm.

[Jupyter Notebook](./Exercises/NumFi.html), [PDF](./Exercises/NumFi_BADDA_DUGUEY.pdf).

### Implementation of a multi-layer perceptron model with Numpy for Call Option Pricing
Creation of a multi-layer perceptron model with Numpy. The aim is to build the best model to fit the analytical price of 
a Call option using a Black-Scholes framework.

[Git Repository](./https://github.com/martinduguey/PricingCallMLP).

### Beta distribution adjustment
In a context of uncertainties quantification, we might need to estimate a distribution (Step C of a V&V-QU process, see [here](./https://github.com/mbaudin47/otsupgalilee-eleve/blob/master/0-Deroulement/MethodologieIncertitude-EN_arial.pdf")). It is the case here, we started from measured data about relative humidity in Bordeaux in 2018. The aim is to properly estimate the parameters of the distribution, in our case a Beta distribution. Work done with [Nicolas HU](./https://www.linkedin.com/in/nicolas-hu/).

[Notebook](./Exercises/ExerciceOpenTURNS_HU_DUGUEY.html), [Git Repository](./https://github.com/martinduguey/Projet-OT).

### Analysis of components failure's Data
Flights reduce components life expectancy, the idea here is to find which component needs to be evaluated by the company in order to optimize maintenance fees. This is a study of two datasets: one describing 
each part with their components and some valuables data such as usage time. The second dataset gives repair costs for each mechanical part.

[PDF](./Exercises/Rapport_ProjetSD.pdf), [Git Repository](./https://github.com/martinduguey/StatistiquesDescriptives).
          
### Simulation of an outbreak's spread
Algorithmic study and simulation of spread based on some Covid-19 data, using tools studied and described in course.
This work doesn't involve PDE numerical resolution.

[PDF](./Exercises/Projet__Algo.pdf), [Git Repository](./https://github.com/martinduguey/Projet_AlgoComplexite).

### A nuclear power plant game using Object-Oriented Programming
Introduction to Object-Oriented with C++ through a programming challenge. The implementation of nuclear power plant game from scratch based on specific terms and conditions. 
Work done with [Nicolas HU](./https://www.linkedin.com/in/nicolas-hu/), 
[Imad BADDA](./https://www.linkedin.com/in/imad-badda/), [Christophe SIVE](./https://www.linkedin.com/in/christophe-sive-6a6386ab/), [Matthieu GRONDIN](./https://www.linkedin.com/in/matthieu-grondin-8138a41b6/) & [Haris MEDJAHED](./https://www.linkedin.com/in/haris-medjahed-b80427167/).

[Class Diagramm](./Exercises/classdiagram.jpeg), [Documentation Doxygen](./Exercises/html_NuclearPPGame/index.html).

### Payment of public transport's ticket with QRCode
Work followed by an oral presentation about QR Code. TIPE Competitive Exam for french Engineering Schools (CPGE).

[Github Repository](./https://github.com/martinduguey/TIPE).