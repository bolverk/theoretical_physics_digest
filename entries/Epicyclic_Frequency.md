== Definition ==
For a particle in a closed orbit, the epicyclic frequency is the frequency of radial motions due to a small perturbation in the orbit. For example, consider a planet orbiting a star in a circular orbit. If the motion of this planet is slightly perturbed in the radial direction, its orbit will change from circular to elliptical. Thus its distance from the star (the center of the potential) is no longer constant, but oscillating between a maximum and minimum distance (apoapsis and periapsis). The epicyclic frequency is the frequency of these oscillations. 

== Derivation ==
Consider a test particle orbiting in a fixed radial potential, $ \phi(r) $. As is well known, the particle's motion is confined to a plane due to conservation of angular momentum. The Lagrangian in polar coordinates is 

$ {\mathcal{L}} = \frac{1}{2}\left({\dot {r}}^2 + r^2{\dot{\varphi}}^2\right) - \phi(r)$

From the Euler-Lagrange equations we deduce a constant of motion which is the orbital angular momentum (per unit mass) of the test particle, as well as the equation of motion in the radial direction:

$ \frac{\partial {\mathcal{L}}}{\partial {\dot{\varphi}}} = r^2{\dot{\varphi}} = const \equiv L \Rightarrow {\dot{\varphi}}=\frac{L}{r^2}$

$ {\ddot{r}} = -\frac{\partial \phi}{\partial r} + r^2{\dot{\varphi}}^2 = F(r) + r^2{\dot{\varphi}}^2 = F(r) + \frac{L^2}{r^3}$

Where we have defined $ F(r) \equiv -{\partial \phi}/{\partial r}$ the radial force acting on the particle due to the potential. The second term in the above equation is due to the centrifugal force. 

Let us now consider a "nearly circular orbit", whose equilibrium radius is $ R $. As this is the equilibrium radius we have

$ F(R) + \frac{L^2}{R^3} = 0 $

If we now perturb the orbit such that $ r = R + \delta r $ with $ \delta r << R $ we obtain to first order 
$ {\ddot{\delta r}} = -\left[\frac{3 L^2}{R^4} - \left(\frac{d F}{dr}\right)_{r=R}\right]\delta r \equiv \kappa^2 \delta r $

where $ \kappa $ is precisely the epicyclic frequency.

== Relation to Angular Freqency ==
It is useful to relate the epicyclic frequency to the angular frequency of the orbit, $\Omega(r)={\dot{\varphi}}$

Since the radial force is given by $ F(r) = -\frac{L^2}{r^3} = -\Omega(r)^2 r $, we easily obtain

$ \kappa^2 = 4\Omega^2 + r\frac{d \Omega^2}{dr}$

== Examples in Specific Potentials ==

=== Kepler Potential ===
In a Keplerian potential we have $ \Omega(r) \propto r^{-3/2} $ and therefore $ \kappa = \Omega $. Since the angular frequency and the epicyclic, radial, frequencies are equal, the orbits form closed ellipses that return to the same point in space every orbit

=== Solid Body Rotation ===
In solid body rotation we have $ \Omega(r) = const $ and therefore $ \kappa = 2\Omega $. Since the ratio between the angular and epicyclic frequencies is rational, the orbits will be closed as in the case of the Kepler potential.

=== Flat Rotation Curve ===
For a flat rotation curve, as is typical of many disk galaxies, $V(r)=const \Rightarrow \Omega(r) \propto r^{-1} \Rightarrow \kappa = \sqrt{2}\Omega$

Here the ratio of angular to epicyclic frequncies is irrational, and therefore perturbed orbits will not be closed, but will return to a slightly different angle after each radial orbit. This will form a "rosetta" like pattern that will eventually fill a finite area.

=== Constant Angular Momentum ===
If the given potential results in angular momentum which is constant with radius, then $L(r)=const \Rightarrow \Omega(r) \propto r^{-2} \Rightarrow \kappa = 0$

Angular momentum profiles that decrease outwards result in imaginary frequencies, which leads to Rayleigh Instability.[[Category:Orbital mechanics]]
__INDEX__
[[Category:Galactic dynamics]]