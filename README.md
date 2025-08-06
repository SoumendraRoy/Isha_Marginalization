\noindent
This repository investigates a question that arose during a discussion with Isha Anantpurkar.

\medskip

Let \( x \) and \( y \) be two random variables drawn independently from normal distributions:
\[
x \sim \mathcal{N}(\mu_x, \sigma_x), \quad y \sim \mathcal{N}(\mu_y, \sigma_y).
\]

We introduce correlated parameter estimation errors by drawing the observed values \( x_{\text{obs}} \) and \( y_{\text{obs}} \) from a multivariate normal distribution centered at \( (x, y) \), with covariance matrix \( \text{Cov} \):
\[
(x_{\text{obs}}, y_{\text{obs}}) \sim \mathcal{N}\left((x, y), \text{Cov}\right).
\]

\medskip

The core question is: \textbf{Can we accurately infer \( \mu_y \) and \( \sigma_y \) using only \( y_{\text{obs}} \), while ignoring \( x_{\text{obs}} \)?}
