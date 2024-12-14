---
{"dg-publish":true,"permalink":"/topological modular form (TMF)/","dgPassFrontmatter":true,"created":"2024-11-24T14:26:35.033+01:00","updated":"2024-12-14T13:25:45.425+01:00"}
---


$\Omega$-spectrum: a sequence of topological spaces $E_{n}$, equipped with [[weak homotopy equivalence\|weak homotopy equivalence]]s $s_{n}: E_{n}\rightarrow\Omega E_{n+1}$. Namely, it induces isomorphisms: $s_{n}^{*}: \pi_{*}(E_{n})=\pi_{*}(\Omega E_{n+1})=\pi_{*+1}(E_{n+1})$. 

Then, Brown's representability theorem gives a cohomology: $E^{n}(X)=lim_{k\rightarrow\infty}[\Sigma^{k}X,E_{n+k}]$ (homotopy classes), where $\Sigma^{k}X$ is the [[suspension\|suspension]]. eg. For Abelian group, Eilenberg-Maclane spectrum gives the [[singular cohomology\|singular cohomology]]. The elliptic cohomology $Ell_{C/R}$ is given by the elliptic spectrum $Spec(\mathbb{R})\rightarrow \mathscr{M}_{ell}$, where $\mathscr{M}_{ell}$ is the [[moduli stack\|moduli stack]] of [[elliptic curve\|elliptic curve]]s. $Ell_{C/R}$ is a [[presheaf\|presheaf]] ($X$ is the first variable, contravariant; functor: limit has universal property, homomorphism) over (coefficient) $\mathscr{M}_{ell}$. 

$E_{C/R}$ isn't a sheaf, but can be sheafified to a sheaf of $E_{\infty}$-ring spectrum (image) on $\mathscr{M}_{ell}$. Its global section is TMF. 
Conjecture: the theory space of 2d, $\mathscr{N}=1$, anomaly d theories is TMF (spectrum). [[Witten genus\|Witten genus]] can map its 0th homotopy group to weak [[modular form\|modular form]]s, which is an isomorphism when no [[anomaly\|anomaly]]. Witten genus can be viewed as the [[Witten index\|Witten index]] (1d, $\mathscr{N}=1$) on loop space.
[[stable homotopy group\|stable homotopy group]]