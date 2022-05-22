The RT instability occurs when a dense liquid is laid on top of a tenuous fluid. The more exact mathematical condition is that the density gradient is opposite to the gravitational force. 

$ \mathbf{g} \cdot \nabla \rho < 0 $

In the next sections we will develop the growth rate in the linear stage.

== Incompressible ==

Equation of continuity

$ \nabla \mathbf{v} = 0 $

Conservation of momentum

$ \rho \frac{\partial \mathbf{v}}{\partial t} + \rho \mathbf{v} \cdot \nabla \mathbf{v} + \nabla P = \mathbf{g}$

We can simplify the equation by replacing the velocity by a flow potential $ \mathbf{v} = \nabla \varphi $. Substituting in the equations of motion yields

$ \nabla^2 \varphi = 0 $

$ \nabla \left(\rho \frac{\partial \varphi}{\partial t} + \frac{1}{2} \rho \left(\nabla \varphi \right )^2 + P - \rho \mathbf{g} \cdot \mathbf{r} \right ) = 0$

We assume an initial configuration where a heavy fluid of density $ \rho_u $ is on top $ y>0 $ of a lighter fluid of density $ \rho_d $ (which occupies the region $ y<0 $.

Next, we introduce a perturbed flow potential

$ \varphi = \delta \varphi_{u,d} \exp \left[ i \left(t \omega - k x + i q |y| \right) \right] $

From the continuity of the normal velocity on the interface between the two fluids $ \delta \varphi_u = - \delta \varphi_d $. The Bernouli invariant should also be continuous across the interface

\left[\rho \frac{\partial \varphi}{\partial t} + \frac{1}{2} \rho \left(\nabla \varphi \right )^2 + P - \rho g y \right] = 0

where the square brackets denote difference across the interface. The pressure is continuous across the interface, so it vanishes. The kinetic energy term also vanish because it is of a higher order in the perturbation. The position of the interface is

$ y = \frac{1}{i \omega} \frac{\partial \varphi}{\partial y} $

We are thus left with a dispersion equation

$ \omega = -i k g \frac{\rho_u - \rho_d}{\rho_u + \rho_d} $

Since the frequency is complex, the amplitude of this mode grows exponentially if a heavy fluid is on top, and decays if the lighter fluid is on top.