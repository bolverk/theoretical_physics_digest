The chirp mass is the effective mass of a binary system, in the context of the [[Quadrupole Gravitational Radiation]] emitted by it.

For a binary system with component masses $M_1, M_2$ the chirp mass is given by:

$M_{ch} = \frac{(M_1 M_2)^{3/5}}{(M_1 + M_2)^{1/5}} $

Alternatively, in terms of the reduced mass, $\mu$ and the total mass $M_T$:

$M_{ch} = (\mu^3 M_T^2)^{1/5} $

A system's chirp mass can be measured by detecting the gravitational wave emitted by it. It can be related to $f$ and $\dot{f}$ - the signal's frequency and the frequency's time derivative.

Along with the final frequency of the GW signal, prior to the final merger of the system, the masses of the individual components of the system can be deduced, giving good constrains on the nature of the system.

== Derivation ==

The power emitted through [[Quadrupole Gravitational Radiation|quadrupole radiation]] by a binary system is:

$P \sim \frac{G}{c^5} (\partial^3 {Q} / \partial t^3)^2 $

The quadrupole moment is the same as the moment of inertia, and so:

$Q = \mu a^2 $

$P \sim \frac{G}{c^5} \mu^2 a^4 \omega^6 $

The energy emitted results in decreasing the orbital energy:

$E_{orb} = -\frac{G M_T \mu}{2a} $

So:

$P = -\dot{E} \sim \frac{G M_T \mu}{a^2} \dot{a}$

In the Keplerian approximation:

$ \omega^2 = \frac{GM_T}{a^3} $

And after some algebra, neglecting numerical pre-factors:

$ \dot{\omega} \sim \frac{\mu}{M_T} (G M_T)^{5/3} \omega^{11/3} c^{-5} $

This is the rate by which the frequency increases, as the orbit shrinks. Collecting all the mass dependence:

$ \mu M_T^{2/3} \sim \frac{c^5}{G^{5/3}} \dot{\omega} \omega^{-11/3} $

Raising this by a power of ${3/5}$:

$ ( \mu M_T^{2/3} )^{3/5} = M_{ch} \sim \frac{c^3}{G} \dot{\omega}^{3/5} \omega^{-11/5} $

More accurately, including the numerical factors:

$ M_{ch} = ( \frac{5}{96}^{3/5} \pi^{-8/5} ) \frac{c^3}{G} \dot{\omega}^{3/5} \omega^{-11/5} $

Thus, by following the frequency evolution of a GW signal ("chirp"), it is possible to estimate the chirp mass of the system. Since the reduced mass is at most a quarter of the total mass: