Let us consider a plane electromagnetic wave moving through a magnetised plasma. Suppose further that the uniform magnetic field is perpendicular to the direction of propagation of the wave. Waves polarised along the magnetic field will not be affected, but waves polarised in the perpendicular direction (to both the magnetic field and the wave direction) will be affected. In this entry we calculate the difference in the effective refractive index between them. We note that this problem has three frequency scales: $\omega$ the frequency of the wave, $\omega_p$ the plasma frequency and $\omega_c$ the cyclotron frequency. We assume that $\omega \gg \omega_p, \omega_c$.

Frist, we show that the result has to scale as $\omega_c^2$. We recall the equation of motion for an isolated particle

$ \frac{d v}{d t} = \frac{q}{m} E + \frac{q}{m} \frac{v}{c} \times B $

where $ q $ is the charge, $ m $ is the mass of a single particle, $ c $ is the speed of light, $ E $ is a constant electric field and $ B $ is a constant magnetic field. For a zero magnetic field field, the solution is $ v_1 = \frac{q}{m} E t $. The first order correction in the magnetic field is $ v_2 - v_1 = \frac{q^2}{m^2 c} E \times B $. This velocity is normal to both the electic and the magnetic field. Only the next order correction to the velocity has a component parallel to the electric field.

Next, we determine the dependence on the other frequencies. The governing equations are the conservation of momentum and Maxwell's equations. We use the electric potential $ A $ of the wave instead of the electromagnetic fields. The linearised conservation of momentum is

$ \frac{\partial}{\partial t} v = - \frac{q}{m c} \frac{\partial A}{\partial t} + \frac{q}{m} \frac{v}{c} \times B $

where $ B $ is the uniform, constant magnetic field. The next governing equation is Ampere's equation

$ \nabla \times \nabla \times A = \frac{4 \pi}{c} n q v - \frac{1}{c^2} \frac{\partial^2 A}{\partial t^2}

where $ n $ is the number density of particles. Applying Fourier transform to the momentum equation, we get

$ i \omega v = i \omega \frac{q}{m c} A + \frac{q}{m} \frac{v}{c}\times B \Rightarrow v \approx - \frac{q}{m c} A + \frac{q^2}{i \omega m^2 c^2} B \times A $

Applying Fourier transform to Ampere's equation and eliminating the velocity yields

$ \left(\omega^2 -\omega_p^2 - c^2 k\times k\times \right)A = \omega_p^2 \frac{\omega_c}{i \omega} $

where $ \omega_p^2 = 4 \pi n q^2/m $ and $ \omega_c = \frac{q B}{m c} $. We see that $ \omega_c $ only appears as part of the product $ \omega_c \omega_p^2 $. Combining the fact that the refractive index is dimensionless, and that the answer has to scale as $\omega_c^2$, dimensional analysis reveals that the only allowed combination of the frequencies is $ \Delta n \propto \frac{\omega_c^2 \omega_p^4}{\omega^6}$. 

A linearly polarised wave either parallel or perpendicular to the magnetic field will remain linearly polarised. A linearly polarised wave at an oblique angle will oscillate between elliptic and linear polarisation, because of the phase difference between the components parallel and perpendicular to the magnetic field. When the polarisation angle is $\pi/4$ relative to the magnetic field, then the polarisation can become circularly polarised. In contrast to the Faraday rotation, the effect does not reverse when the magnetic field changes sign.