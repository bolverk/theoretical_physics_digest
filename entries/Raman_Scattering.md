== Particle in Vacuum ==
Let us consider a charged particle subject to an electromagnetic wave. The equation of motion is

$ \frac{d^2 \mathbf{r}}{d t^2} = \frac{q E}{m} \left[\hat{x} + \frac{1}{c} \frac{d \mathbf{r}}{d t} \times \hat{y} \right] \cos \left(\omega t - z \omega/c\right)$

We define new dimensionless variables $ \mathbf{R} = \mathbf{r} / \frac{q E}{m \omega^2} $, $ \varphi = \omega t $ and $ \delta = \frac{q E}{m \omega c} $ 

Let us expand the solution in $ \delta $. For simplicity, let us assume that at $ t = 0 $ the particle is at the origin, and that its velocity is zero. If we set $ \delta = 0 $ then the solution is

$ \frac{d^2 \mathbf{R}_0}{d \varphi^2} = \hat{x} \cos \varphi \Rightarrow \mathbf{R}_0 = \hat{x} \left(1 - \cos \varphi\right) $

Expanding to first order in $ \delta $

$ \frac{d^2 \mathbf{R}_1}{d \varphi^2} = \delta \sin \varphi \cos \varphi \hat{z} \Rightarrow \mathbf{R}_1 = \frac{\delta}{8} \left[2 \varphi - \sin \left(2 \varphi\right) \right] \hat{z} $

We get that the particle continuously drifts in the longitudinal direction.

== Particle in a Medium ==
Now suppose that a particle is confined to a medium. We model the effect of the medium as a harmonic oscillator with a frequency $ \omega_m \ll \omega $. The equation of motion for the particle to first order in $ \delta $ becomes

$ \frac{d^2 \mathbf{R}_1}{d \varphi^2} + \frac{\omega_m^2}{\omega^2} \mathbf{R}_1 = \delta \sin \varphi \cos \varphi \hat{z} \Rightarrow \mathbf{R}_1 = \frac{\delta}{4} \left[\frac{\omega}{\omega_m} \sin \left(\frac{\omega_m}{\omega} \varphi\right) - \frac{1}{2}\sin \left(2 \varphi\right) \right] \hat{z} $

We see that in addition to exciting a longitudinal wave with a harmonic of the original frequency, an oscillation with the frequency of the medium is excited. The latter is often called a phonon. Continuing the expansion to second order in $ \delta $ yields

$ \frac{d \mathbf{R}_2}{d \varphi^2} = \frac{\delta^2}{4} \left[\frac{\omega}{\omega_m} \sin \left(\frac{\omega_m}{\omega} \varphi\right)-\frac{1}{2} \sin \left(2 \varphi\right)\right] \left(\sin \varphi - \cos \varphi\right) $

The source term on the right hand side contains products of trigonometric functions with argumens $ \varphi $ and <nowiki>$</nowiki> \omega_m \varphi /\omega <nowiki>$</nowiki>. When multiplied, the resulting modes will have arguments of the form $ \varphi \left(1\pm \omega_m/\omega\right) $. These modes will have slightly larger or smaller energies than the incident radiation. This is the inelastic Raman scattering. The amplitude of the acceleration of these modes is

$ a \approx \frac{q E}{m} \left(\frac{q E}{m \omega c}\right)^2 \frac{\omega}{\omega_p} $

and the luminosity of a single particle is given by

$ L_1 \approx \frac{q^2 a^2}{c^3} \approx \frac{q^2}{c} \frac{\omega^4}{\omega_m^2}\left(\frac{q E}{m \omega c}\right)^6$

Contrary to elastic scattering (like Compton scattering), the emitted flux is not linear in the incident flux.