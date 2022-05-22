In this entry we'll try to understand why the matter power spectrum scales roughly as $k^1$ at low wavenumbers and as $k^{-3}$ for large wavenumbers.

Initially, the universe was assumed to have some random density field. We denote by $\delta = \frac{\rho - \bar{\rho}}{\bar{\rho}}$ the fractional deviation from uniform distribution. We can describe the random fields using a correlation function $P_h$. This correlation function has units of volume, so we can express it in dimensionless form by multiplying by the wavenumber cubed $\tilde{P}_h = k^3 P_h$. We assume that the early universe was scale invariant, so that the the dimensionless correlation function is constant, and so

$P_h \propto k^{-3}$

Next, we consider the evolution of the perturbations. While outside the horizon, the perturbations are assumed to be frozen, and they begin to evolve once the scale of the horizon becomes comparable to their wavelength. Small scale perturbations enter the horizon early, while the universe is still radiation dominated. In this case, the growth of perturbations is slow, because radiation masks the effect of gravity. In contrast, large scale perturbations entered the horizon when the universe was matter dominated, at which stage the growth was rapid. We proceed to calculate the growth in the matter dominated phase.

First, we find the relation between time and the scale factor. To do this we consider dust collapse onto a point mass

$\ddot{r} = - \frac{G M}{r^2}$

If $r = r_0 a \left(t \right)$, then $a \propto t^{2/3}$. 

Second, we consider the [https://ned.ipac.caltech.edu/level5/Sept03/Peacock/Peacock2.html perturbation equation] for the fractional density difference

$\ddot{\delta} + 2 \frac{\dot{a}}{a} \dot{\delta} = 4 \pi G \bar{\rho} \delta = \frac{3}{2} \frac{\delta}{t^2}$

Looking for power law solutions yields a growing mode $\delta \propto t^{2/3} \propto a$.

The horizon size becomes comparable to the wavelength of the perturbation when

$t_h \approx \frac{a}{k c} \propto a^{3/2} \Rightarrow a_h \propto k^2$

Hence, from the time it crossed the horizon till today, a mode grows by a factor of $k^2$, the correlation function grows by a factor of $k^4$, and so the correlation function in the limit of small wavenumbers is given by

$P_l \propto P_h k^4 \propto k$

This part is sometimes called the Harrison Zeldovich spectrum.