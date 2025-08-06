This repository investigates a question that arose during a discussion with Isha Anantpurkar.

Say $x$ and $y$ are two random variables drawn independently from normal distributions:
$x \sim \mathcal{N}(\mu_x, \sigma_x)$, $y \sim \mathcal{N}(\mu_y, \sigma_y)$.

We add correlated parameter estimation error to $x$ and $y$ by drawing observed variables from a multivariate normal distribution centered at $(x, y)$ with covariance matrix $\mathrm{Cov}$:
$(x_{\mathrm{obs}}, y_{\mathrm{obs}}) \sim \mathcal{N}((x, y), \mathrm{Cov})$.

The question is: can we accurately infer $\mu_y$ and $\sigma_y$ using only $y_{\mathrm{obs}}$, ignoring $x_{\mathrm{obs}}$?
