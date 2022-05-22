When atoms in a magnetic field are irradiated by a linearly polarised light, the reflected radiation can have a polarisation that is perpendicular to both the initial polarisation and the magnetic field. This is an inherently quantum effect, but in this entry we will describe a classical analogue.

Let us consider a particle with mass $m$, charge $q$ in a harmonic oscillator with frequency $\Omega$. The particle is in a uniform magnetic field $\mathbf{B}$, and is excited by some alternating electric field $\mathbf{E} \left(t\right)$. The equation of motion is given by

$m \ddot{\mathbf{r}} = q \mathbf{E} \left(t\right) + \frac{q}{c} \dot{\mathbf{r}} \times \mathbf{B} - m \Omega^2 \mathbf{r}$

Applying Fourier transform yields

$-\omega^2 \mathbf{r} = \frac{q}{m} \mathbf{E} \left(\omega\right) + i \frac{q}{mc} \mathbf{r} \times \mathbf{B} - \Omega^2 \mathbf{r}$

We can move to non dimensional variables using the substitution

$f = \omega/\Omega$

$\mathbf{e} = \frac{q \mathbf{E}}{m c \Omega}$

$\mathbf{s} = \frac{\Omega \mathbf{r}}{c}$

$\mathbf{b} = \frac{q \mathbf{B}}{m c \Omega^2}$

We can re write the equation in terms of the new dimensionless variables

$\left(1-f^2\right) \mathbf{s} - i \mathbf{s} \times \mathbf{b} = \mathbf{e}$

We look for a solution of the form

$\mathbf{s} = C_1 \mathbf{e} + C_2 \mathbf{b} + C_3 \mathbf{e} \times \mathbf{b}$

Subsituting this ansatz yields three equations for the scalar coefficients $C_1$, $C_2$ and $C_3$

$C_3 = \frac{i}{\left(1-f^2\right)^2+b^2}$

$C_2 = -\frac{\mathbf{e} \cdot \mathbf{b}}{1-f^2} \frac{1}{\left(1-f^2\right)^2+b^2}$

$C_1 = \frac{1-f^2}{\left(1-f^2\right)^2+b^2}$

We see that if the magnetic field is normal to the electric field $\mathbf{e} \cdot \mathbf{b} = 0$, then close to resonance $f \rightarrow 1$ we get $C_1 = C_2 = 0$ and the radiation is polarised in the $\mathbf{e} \times \mathbf{b}$ direction.