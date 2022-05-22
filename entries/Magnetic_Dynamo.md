One way of generating magnetic fields is amplifying weak fields using the turbulent motion of the fluid the field is embedded in. This process of generating magnetic fields is called a dynamo.
The evolution of a magnetic field in a turbulent medium is given by the induction equation 

$ \frac{\partial \mathbf{B}}{\partial t} = \lambda \nabla^2 \mathbf{B} + \nabla \times \left(\mathbf{u}\times\mathbf{B} \right) $

The first (diffusive) term tends to damp the magnetic field, while the second (advective) term tends to amplify them. Using dimensional analysis, it is possible to determine which dominates. We denote the typical velocity scale by $U$, and the typical length scale by $L$. Advection dominates when

$ \frac{U}{L} B > \frac{\lambda}{L^2} B \Rightarrow \frac{UL}{\lambda} > 1 $

The dimensionless term on the left hand side is sometimes called the magnetic Reynolds number.

The main challenge in solving the induction equation is the advection term. In what follows we will describe a mean field approximation to simplify this term. Let us assume that the velocity field fluctuates on small scales

$ \mathbf{u} = \sum_{\mathbf{q}} \mathbf{u}_q \exp \left(i \mathbf{q} \cdot \mathbf{r} \right)

While the magnetic field has both components that fluctuate on large and small scales

$ \mathbf{B} = \exp \left(\sigma t\right) \left[\mathbf{B}_0 \exp \left(i \mathbf{k} \cdot \mathbf{r} \right) + \sum_{\mathbf{q}} \mathbf{b}_q \exp \left(i \left(\mathbf{k} + \mathbf{q}\right) \cdot \mathbf{r}\right)\right] $

where $ q \gg k $. Substituting into the induction equation and focussing on small scales yields

$ \sigma \mathbf{b}_q = -\lambda q^2 \mathbf{b}_q + i \mathbf{q} \times \left(\mathbf{u}_q \times \mathbf{B}_0\right) $

$ \mathbf{b}_q = \frac{i}{\sigma + \lambda q^2} \mathbf{q} \times \left(\mathbf{u}_q \times \mathbf{B}_0 \right) $

The contribution of the small scales to the large scale advective term can be written in the following way

$ \mathbf{u}_q \times \mathbf{b}_q \approx \mathbf{M} \mathbf{B}_0 $

where the matrix $ \mathbf{M} $ is given by

$ \mathbf{M} = \sum_{\mathbf{q}} \frac{i}{\sigma + \lambda q^2} \left(\mathbf{u}_{-q} \times \mathbf{u}_{q}\right) \otimes \mathbf{q} $

where $ \otimes $ is the outer production. In the limit $ \sigma \gg \lambda q^2 $, the turbulent contribution to the advective term in real space can be written as

$ \mathbf{u} \times \mathbf{B} \approx \alpha \mathbf{B} + \beta \nabla \times \mathbf{B} $

Where $ \alpha = \frac{1}{\sigma} < \mathbf{u} \otimes \left( \nabla \times \mathbf{u}\right)> $ and $ \beta = \frac{1}{\sigma} <\mathbf{u} \otimes \mathbf{u}>$, where triangular brackets imply spatial average. In the case of an isotropic flow, the tensors can be reduced to scalars $ \alpha = \frac{1}{\sigma} <\mathbf{u} \cdot \left(\nabla \times \mathbf{u}\right)> and $\beta = \frac{1}{\sigma} <\mathbf{u} \cdot \mathbf{u}>$.
We can demonstrate the calculation of these coefficients using ABC flow

$ \mathbf{u} = \left[\mathcal{A} \sin \left(q z\right)+\mathcal{C} \cos \left(q y\right) \right] \hat{x} + \left[\mathcal{B} \sin \left(q x\right) + \mathcal{A} \cos \left(q z\right)\right] \hat{y} + \left[ \mathcal{C} \sin \left(q y \right)+ \mathcal{B} \cos \left(q x\right)\right] \hat{z} $

where $ \mathcal{A} $, $ \mathcal{B} $ and $ \mathcal{C} $ are constants. The corresponding coefficients are

$ \alpha = \frac{q}{\sigma} \left(\mathcal{A}^2 + \mathcal{B}^2 + \mathcal{C}^2\right)

$ \beta = \mathcal{A}^2 + \mathcal{B}^2 + \mathcal{C}^2 $

The term with the $ \alpha $ tends to amplify the field, while the term with the $ \beta $ is an additional source of (turbulent) diffusion.