Let us consider an atom at some stable state with energy $E$. In this case the phase of the wave function evolves as $\psi \propto \exp \left(i t E/ \hbar \right)$. Suppose that we introduce collisions. The collisional timescale is $\tau \approx \left(n \sigma v\right)^{-1}$, where $n$ is the density, $v$ is the thermal velocity and $\sigma$ is the cross section. In this case the probability of an atom to remain at the same energy level decreases exponentially with time $\psi \propto \exp\left(i E t/ \hbar\right) \exp\left(-\left|t\right| /\tau \right)$. This effect causes a broadening in the frequency domain, which can be calculated by applying a fourier transform to the wave function

${\rm FFT} \left[ \exp\left(i E t / \hbar - \left|t\right|/\tau\right)\right] \approx \frac{\tau}{1+\tau^2\left(\omega+\Omega\right)^2}$

where $\Omega = E/\hbar$. This shape is called a Lorentzian.

In the absence of collisions, or any other broadening mechanism, atoms can only absorb photons exactly at the frequency that corresponds to the transition energy $\Omega_0$, and the absorption coefficient is proportional to a Dirac delta function $a \propto \delta \left(\omega - \Omega_0 \right)$. Collisions broaden this profile to the shape of a Lorentzian

$a \propto \frac{\tau}{1+\tau^2 \Delta \omega^2}$

where $\Delta \omega = \omega - \Omega_0$. The optical depth is given by $\tau \approx a L$, where $L$ is the length of the radiating plasma in a direction perpendicular to the line of sight. As $\tau$ increases, the flux decreases, until $\tau \approx 1$, beyond which further increase of the optical depth does not reduce the flux. The [https://en.wikipedia.org/wiki/Equivalent_width equivalent width] of a collisionally broadened line is therefore determined by the condition $\tau \approx 1$. Assuming $\tau \Delta \omega \gg 1$, the equivalent width scales as $\Delta \omega \propto \sqrt{1/\tau}$.