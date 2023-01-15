---
title: "Efficient implementation of the ARKN and ERKN integrators for multi-frequency oscillatory systems with multiple time scales"
authors:
- Wei Shi
- Xinyuan Wu
- admin

date: "2020-05-01T00:00:00Z"
doi: "10.1016/j.apnum.2019.12.014"


publication: "*Appl. Numer. Math.,151, 13-26*"
publication_short: ""

abstract: It is known that, a notable feature of both the multi-frequency and multidimensional ARKN (Runge-Kutta-Nyström methods adapted to oscillatory system) and ERKN (extended Runge-Kutta-Nyström) integrators when they are applied to multi-frequency and multidimensional oscillatory system $q^{\prime \prime}+M q=f(t, q)$ with multiple time scales is that they exactly integrate the multifrequency oscillatory homogeneous system $q^{\prime \prime}+M q=\mathbf{0}$. With regard to the efficient implementation issues of the integrators, it is significant to calculate efficiently the matrix-valued functions $\phi_0(V)$ and $\phi_1(V)$ which are involved in the two kinds of integrators, where $V=h^2 M$ and $h$ is a stepsize. In this paper, we pay attention to efficient implementation issues of the multi-frequency and multidimensional ARKN and ERKN integrators which are closely related to the calculations of $\phi_0(V)$ and $\phi_1(V)$. Using the properties of $\phi_0(V)$ and $\phi_1(V)$ and their relations, we present an efficient algorithm to calculate the two matrix-valued functions at lower cost. Two illuminating numerical examples are accompanied and the numerical results show the remarkable efficiency of the algorithm. We also give an essential stability analysis for ARKN and ERKN integrators on the basis of the different approximations to $\phi_0(V)$ and $\phi_1(V)$ which gains an insight into the importance of the calculations of $\phi_0(V)$ and $\phi_1(V)$.


tags:
- Journal Papers
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0168927419303460
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


---


