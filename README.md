# MAPaper
M.A. Research Paper
A simple matching function:
$$H=m(U,V)$$
Let q denote the daily Poisson arrival rate of a vacancy being filled:
$$q(U,V)=m(U,V)/V$$
We can model job vacancies over time as: <br />
$$v(t)=V_0(1-q)^t$$<br />
where $V_0$ is the inflow of new job vacancies created at $t=0$, and $q$ is the probability of a vacancy being filled during period $t$. The geometric series would be:<br />
$$V_{a,b}=\sum_{t=a}^{b}v(t)$$
$$V_{a,b}={V_0(1-q)^a\left(1-(1-q)^b\right)\over1-(1-q)}$$
