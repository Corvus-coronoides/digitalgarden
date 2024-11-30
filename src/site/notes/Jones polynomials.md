---
{"dg-publish":true,"permalink":"/Jones polynomials/","dgPassFrontmatter":true,"created":"2024-11-26T08:11:15.085+01:00","updated":"2024-11-30T17:53:41.336+01:00"}
---


1. We can focus on the computations of knots invariants in $S^{3}$, because other three-manifold can be reduced to $S^{3}$ by [[surgery\|surgery]]: cut out a 2d thicken circle $M_{R}$, make a diffeomorphism (glue to create genus?) to its boundary and then stick back (eg. stick a sphere with a handle). This can be seen by considering vice versa: $S^{3}$ can be constructed to any three-manifold by surgery (compare their time slices).

    This operation results in a transformation on the states on  $M_{R}$. By applying surgery to the knots ($M_{R}$), we can make knots move in  $S^{3}$ and do computations.

2. For $S^{3}$, we have expectation values uniquely decided by the [[skein relation\|skein relation]] (isotopic transformation). This can be proved by cutting out a ket with 4 marked points, replacing by other two proper kets (different knots in the same submanifold~different kets in the same Hilbert space), and noticing that the Hilbert space is 2d (4-pt, 2 [[conformal block\|conformal block]]s) so these three kets are linear dependent.

    uniqueness: isotopic transformation may change the topology, so on general manifold change the winding number?
    
3. Similarly, we can prove the multiplicativity for the connected sum of manifolds with the unknotted and unlinked knots (marked points less than 3): cut into $\ket{a}$ and $\bra{b}$, $Z(M)=\braket{b|a}$, $Z(M)\cdot Z(S^{3})=\braket{b|v'}\braket{v|a}=Z(M_{1})\cdot Z(M_{2})$ (Hilbert space is 1d; this $S^{3}$ doesn't have knots). 