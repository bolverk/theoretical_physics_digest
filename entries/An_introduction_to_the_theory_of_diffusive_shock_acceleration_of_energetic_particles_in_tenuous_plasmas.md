[http://adsabs.harvard.edu/abs/1983RPPh...46..973D Link to ADS entry]

The author goes to great lengths to explain the linear advection and diffusion terms in the Boltzmann equation (equation 2.11), but is content with a vague "hand waving" explanation for the last term on the right hand side

$ \frac{1}{3} \left( \nabla \cdot \mathbf{U} \right) p \frac{\partial f}{\partial p}$

This term guarantees that the number of particles is conserved

$ N = \int d^3 x \int d^3 p \cdot f $

$ \frac{\partial N}{\partial t} = \int d^3 x \int d^3 p \cdot \frac{\partial f}{\partial t} =  $

$ = \int d^3 x \int d^3 p \cdot \left( -\mathbf{U} \cdot \nabla f + \nabla \left( \kappa \nabla f \right) + \frac{1}{3} \nabla \cdot U p \frac{\partial f}{\partial p} \right) = $

$ = 4 \pi \int d^3 x \int p^2 dp \cdot \left( -\mathbf{U} \cdot \nabla f + \frac{1}{3} \nabla \cdot U p \frac{\partial f}{\partial p} \right) = $

$ = 4 \pi \int d^3 x \int dp \cdot \left( -p^2 \mathbf{U} \cdot \nabla f - \frac{1}{3} \nabla \cdot U \left(\frac{\partial}{\partial p}p^3\right) f \right) = $

$ = 4 \pi \int d^3 x \int dp \cdot \left( -p^2 \mathbf{U} \cdot \nabla f - \nabla \cdot U p^2 f \right) = $

$ = - 4 \pi \int d^3 x \int p^2 dp \cdot \left( \mathbf{U} \cdot \nabla f + \nabla \cdot U f \right) = $

$ = - 4 \pi \int d^3 x \int p^2 dp \cdot \left( \nabla \cdot \left( \mathbf{U} f\right) \right) =  0 $

but it is not unique (there may be different terms that restore conservation of particle number). The reason for that particular form is given in [http://adsabs.harvard.edu/abs/1965P%26SS...13....9P Parker 1965].