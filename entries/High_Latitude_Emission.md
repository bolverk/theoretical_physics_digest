Let us consider a thin spherical shell expanding at a uniform velocity $ v$. At some moment $ t_0 $ (in the lab frame, where the centre of the explosion is stationary) all the matter on the shell emit photons. The spectrum of the photon, in the fluid frame, is assumed to be a power law $ \propto \nu'^{\beta}$. The fluid and lab frame frequencies can be related through the Lorentz transform

$ \nu' = \nu \Gamma \left( 1 - v \mu \right) $

where $ \Gamma = \frac{1}{\sqrt{1 - v^2}} $ is the Lorentz factor and $ \mu $ is the cosine of the angle between the fluid element direction of motion and the line of sight. The flux received by an observer at a distance $ d $ is given by

$ f_{\nu} = \frac{1}{4 \pi d^2} \int d^3 r \varepsilon_{\nu} = \frac{1}{4 \pi d^2} \int d^3 r \frac{\varepsilon'_{\nu'}}{\Gamma^2 \left(1-\beta \mu \right)^2} $

where $ \varepsilon_{\nu} $ is the emissivity in the lab frame and $ \varepsilon'_{\nu'} $ is the emissivity in the fluid rest frame, and we recall that $ \varepsilon_{\nu} / \nu^2 $ is a Lorentz invariant. The emissivity in the rest frame is given by

$ \varepsilon_{\nu'} = C \nu'^{\beta} \frac{\delta \left(r - v t' \right)}{4 \pi r^2} \delta \left(t' - t_0 \right)$

The photon arrival time $ t $ can be related to the photon emission time $ t' $ using

$ t - t' = \sqrt{d^2 + r^2 - 2 r \cdot d \mu} - d \approx - r \mu  \Rightarrow t' = t + r \mu$

Substituting everything into the integral and solving it yields

$ f_{\nu} = \frac{C \nu^{\beta}}{8 \pi d^2 \Gamma^2 } \frac{1}{t_0 - \left( 1+\beta \right)t}  \left( \frac{\beta t}{t_0 - t} \right)^{\beta-2}$

So when $ t \ll t_0 $

$ f_{\nu} \propto \nu^{\beta} / t^{2-\beta} $