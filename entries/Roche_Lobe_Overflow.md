We consider two stars of similar mass $ M $. The separation between the stars is $ a $. The size of the Roche lobe around each star is also comparable to $ a $. One star expands until its envelope extends beyond the Roche lobe by $\Delta R \ll a$. We want to calculate the mass transfer rate between the stars. First, we calculate the radius of the aperture through which matter flows from the primary to the companion. We assume that stellar matter has so little energy that it travels along equipotential lines. In this analysis we will only take into account gravitational potential, and neglect the contribution of rotation. Both Roche lobes touch at a point on the line connecting the stars where the potential has a saddle point. We denote by $ y $ the distance perpendicular to that line. Close to the saddle point, the potential changes like

$ \Delta \phi \approx \frac{G M}{a^3} y^2 $.

The difference between the potential energy of the Roche lobe and that of the stellar edge is 

$ \Delta \phi_s \approx \frac{G M}{a^2} \Delta R$.

The maximum value of $ y $ for this difference in potential sets the size of the aperture

$ \Delta \phi \approx \Delta \phi_s \Rightarrow \frac{y_s}{a} \approx \sqrt{\frac{\Delta R}{a}}$

The mass flux through the aperture is given by Bernouli's equation with three terms: kinetic, potential and thermal. The kinetic term is given by $ v^2 $, the potential term by $ \Delta \phi $ and the thermal by $ p/\rho $, where $ p $ is the pressure and $ \rho $ is the density. We assume that the flow is isentropic, so $ p = S \rho^{\gamma} $ where $ S $ is a constant that depends only on the entropy and $ \gamma $ is the adiabatic index. Bernouli's equation is therefore

$ v^2 + S \rho^{\gamma-1} \approx \Delta \phi $.

Very close to the saddle point the potential is almost constant, so

$ v dv \approx - S \rho^{\gamma-2} d \rho$.

We can close this set of equations with the conservation of matter in steady state

$ \rho dv + v d\rho = 0 $

So the flux is given by

$ F_m = \rho v \approx \Delta \phi^{\frac{1}{\gamma-1}+\frac{1}{2}}/S^{\frac{1}{\gamma-1}} \approx \left(\frac{G M \Delta R}{a^2} \right )^{\frac{1}{\gamma-1}+\frac{1}{2}}/S^{\frac{1}{\gamma-1}} $

The mass flux is therefore given by

$ \dot{M} \approx y_s^2 F_m = a \Delta R \left(\frac{G M \Delta R}{a^2} \right )^{\frac{1}{\gamma-1}+\frac{1}{2}}/S^{\frac{1}{\gamma-1}} \approx \frac{a^3}{G M} \left(\frac{G M \Delta R}{a^2} \right)^{\frac{1}{\gamma-1}+\frac{3}{2}}/S^{\frac{1}{\gamma-1}}$

The radius of the star is very close to $ a $, so $ \frac{\Delta R}{a} \approx \frac{\Delta R}{R} $. If $ \frac{\Delta R}{R} \propto \frac{\Delta M}{M} $ where $ \Delta M = M_0 - M $ is the difference from equilibrium mass, then 

$ \dot{M} \propto \left(M_0 - M\right)^{\frac{1}{\gamma-1}+\frac{3}{2}} \propto \left(t_0 - t\right)^{\frac{3 \gamma - 1}{\gamma + 1}}$

where $ t_0 $ is a constant.