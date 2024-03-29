# MAPaper
M.A. Research Paper

A simple matching function between the number of unemployed workers ("U") and the number of job vacancies ("V") can be written as:
$$H=m(U,V)$$
where $H$ is the number of new hires. Let $q$ denote the Poisson arrival rate of a vacancy being filled:
$$q(U,V)={m(U,V)\over V}$$
We can model job vacancies over time as:
$$v(t)=V_0(1-q)^t$$
where $V_0$ is the inflow of new job vacancies created at $t=0$. The geometric series would be:
$$V_{a,b}=\sum_{t=a}^{b}v(t)$$
$$V_{a,b}={V_0(1-q)^a\left(1-(1-q)^b\right)\over1-(1-q)}$$
