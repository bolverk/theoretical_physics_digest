Let us consider an electron (mass $m$ and charge $q$) attached to a spring such that the oscillation frequency is $\omega$. The unperturbed Hamiltonian of this system is

$H_0 = \frac{p^2}{2 m} + \frac{1}{2} m \omega^2 x^2$

Now suppose we introduce an electromagnetic field, described by a vector potential $\mathbf{A}$. The new Hamiltonian would be

$H_1 = \frac{1}{2 m} \left(\mathbf{p}+\frac{q}{c} \mathbf{A}\right)^2 + \frac{1}{2} m \omega^2 x^2 \approx H_0 + \frac{q}{m c} \mathbf{A} \cdot \mathbf{p}$

where we negelct the quadratic terms in the vector potential. We consider a harmonic oscillator at the lowest energy state, and we are interested in the probability that the electromagnetic field will excite this harmonic oscillator to a higher level

$w_{01} = |<1| \exp \left(\frac{i}{\hbar} \int H_1 dt \right) |0>|^2 \approx |<1|\frac{i}{\hbar} \int H_1 dt|0>|^2 \approx$

$\approx \frac{q^2 A^2}{m^2 c^2 \Omega^2 \hbar^2}|<0|p|1>|^2$

where $\Omega$ is the frequency of the electromagnetic field. We can evaluate the matrix element using ladder operators

$<1|p|0> = i\sqrt{\frac{1}{2} \hbar m \omega}<1|a^{\dagger}-a|0> = i\sqrt{\frac{1}{2} \hbar m \omega}$

so the transition probability is

$w_{01} \approx \frac{q^2 A^2 \omega}{m c^2 \Omega^2 \hbar}$

The rate at which energy is absorbed is

$L \approx \hbar \omega \Omega w_{01}$

The incident Poynting flux is

$f \approx \Omega^2 A^2/c$

So the cross section is

$\sigma \approx \frac{q^2 \omega^2}{m c \Omega^3} \approx r_e \lambda \left(\frac{\omega}{\Omega}\right)^3$

where $\lambda \approx c/\omega$ is the wavelength of the electromagnetic radiation and $r_e$ is the classical electron radius. We find that the cross section declines with the radiation frequency as $\Omega^{-3}$. For lower frequency, the cross section should vanish as a single photon cannot excite the system.