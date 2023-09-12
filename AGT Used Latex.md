# Latex in AGT

Cost if one flow: $C(f)=\displaystyle\sum_{a \in A} f_{a} \ell_{a}\left(f_{a}\right)$

$I=\left(G=(V, A),\left(\ell_a\right)_{a \in A},\left(s_i, t_i\right)_{i \in[k]},\left(r_i\right)_{i \in[k]}\right)$

$\ell_a : \mathbb{R}_{\geq 0} \rightarrow \mathbb{R}_{\geq 0}
$

Social cost: 
$C(f)=\displaystyle\sum_{P \in \mathcal{P}} f_{P} \ell_{P}\left(f_{P}\right)$

### PS: Social cost is a broader concept than the cost of a flow


(Nash flow): A feasible flow $f$ for a selfish routing instance $I$ is a Nash flow if
$
\forall i \in[k], P, Q \in \mathcal{P}_i, f_P>0, \forall \delta \in\left(0, f_P\right]: \quad \ell_P(f) \leq \ell_Q(\tilde{f}),
$
where $\tilde{f}: \mathcal{P} \rightarrow \mathbb{R}_{\geq 0}$ is a flow defined as
$
\tilde{f}_R= \begin{cases}f_P-\delta & \text { if } R=P \\ f_Q+\delta & \text { if } R=Q \\ f_R & \text { otherwise }\end{cases}
$

Variational inequality $\displaystyle\sum_{a \in A} \ell_{a}\left(f_{a}\right)\left( f_a - x_a \right)\leq 0$

$
\displaystyle \omega(\mathcal{L})=\sup _{0 \neq \ell \in \mathcal{L}} \omega(\ell), \quad \text { where } \omega(\ell)=\sup _{0 \leq x<z} \frac{(\ell(z)-\ell(x)) x}{\ell(z) z}
$