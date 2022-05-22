In the classical Compton scattering, the probability of a photon to scatter in a certain direction depends only on the scattered photon and electron. However, since photons are bosons, the probability of scattering in a certain direction increases with the number of photons already moving in that direction. Let $ N \left( \mathbf{k} \right) $ be the distribution function of photons, such that the number density of photons (photons per unit volume) is given by $ n = \int \frac{d^3 k}{\left( 2 \pi \right)^3} N \left( \mathbf{k} \right)$, and $ \mathbf{k} $ is the wave - number (and the momentum of the photons). Let the distribution functions of the electrons be $ f \left( \mathbf{p} \right) $, where $ \mathbf{p} $ is the momentum of the electron. Let $ w \left(\mathbf{p}, \mathbf{k}, \mathbf{k}' \right) $ be the probability of scattering an electron with momentum $ \mathbf{p} $ and a photon of momentum $ \mathbf{k} $ to a state where the momentum of the photon is $ \mathbf{k}' $ (and the momentum of the electron is $ \mathbf{p} + \mathbf{k} - \mathbf{k}'$). The rate equation for the photons is given by

$ \frac{\partial N}{\partial t} = \int d^3 p \int \frac{d^3 k}{\left( 2 \pi \right )^3} f \left( \mathbf{p} \right ) N \left( \mathbf{k}' \right ) \left[ 1 + N \left( \mathbf{k} \right ) \right ] w \left(\mathbf{p}, \mathbf{k}', \mathbf{k} \right ) - $

$ \int d^3 p \int \frac{d^3 k}{\left( 2 \pi \right )^3} f \left( \mathbf{p} \right ) N \left( \mathbf{k} \right ) \left[ 1 + N \left( \mathbf{k}' \right ) \right ] w \left(\mathbf{p}, \mathbf{k}, \mathbf{k}' \right ) $

If the electron does not recoil, then the incoming and outgoing photons have the momenta, so detailed balance reads

$ w \left(\mathbf{p}, \mathbf{k}, \mathbf{k}' \right) = w \left(\mathbf{p}, \mathbf{k}', \mathbf{k} \right)$

Substituting into the rate equation eliminates the extra terms (due to symmetry) and only the regular scattering is left.

However, if recoil is taken into account, then detailed balance reads

$ w \left(\mathbf{p}, \mathbf{k}, \mathbf{k}' \right) = w \left(\mathbf{p} - \Delta \mathbf{k}, \mathbf{k}', \mathbf{k} \right) $

where $ \Delta \mathbf{k} = \mathbf{k}' - \mathbf{k}$. Substituting this into the equation, assuming $ k \ll p $ and applying a Taylor expansion yields

$ \frac{\partial N}{\partial t} = \int d^3 p \int \frac{d^3 k}{\left( 2 \pi \right )^3} f \left( \mathbf{p} \right ) \left[ N \left( \mathbf{k}' \right ) - N \left(\mathbf{k} \right ) \right ] w \left(\mathbf{p}, \mathbf{k}, \mathbf{k}' \right ) + $

$ \int d^3 p \int \frac{d^3 k}{\left( 2 \pi \right )^3} \Delta \mathbf{k} \cdot \frac{\partial f}{\partial \mathbf{p}} N \left( \mathbf{k}' \right )  N \left(\mathbf{k} \right )  w \left(\mathbf{p}, \mathbf{k}, \mathbf{k}' \right ) $

The first integral is just the classical Compton scattering. The second term is a correction due to recoil and induced emission.