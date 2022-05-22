Let us consider a plasma in a uniform, constant magnetic field $ \vec{B} $. The equation of motion for an electron in this environment is

$ m \frac{dv}{dt} = q \vec{E} + \frac{q}{c} \vec{v} \times \vec{B} - \frac{m}{\tau} \vec{v} $

where $ q $ is the elementary charge, $ c $ is the speed of light, $ m $ is the electron mass, $ \vec{E} $ is the external electric field and $ \tau $ is the time between collisions (see [[Spitzer Resistivity]]). We are interested in the steady state solution, so we can drop the time derivative. We also want to get rid of as many of the dimensional parameters, so we can massage the equation into the following form

$ \vec{\varepsilon} = \vec{\beta} \times \vec{v} + \vec{v} $

where $ \vec{\varepsilon} = \tau q \vec{E} / m $ and $ \vec{\beta} = \tau q \vec{B} / m c $ is the Bohm parameter. For the component of the velocity and electric field parallel to the magnetic field we get

$ \vec{v}_{\parallel} = \vec{\varepsilon}_{\parallel} $

For the component perpendicular to the magnetic field we get

$ \vec{v}_{\perp} = \frac{\varepsilon_{\perp}-\vec{\beta}\times\vec{\varepsilon}_{\perp}}{1+\beta^2} $

The current density is given by $\vec{j} = q n \vec{v}$, where $n$ is the number density. The magnitude of the current density changes with the angle of the electric field relative to the magnetic field, and it can also be misaligned with the direction of the electric field. For this reason the conductivity in this case is a tensor. When $ \beta \ll 1 $ the plasma is said to be in the resistive regime, when $ \beta \gg 1 $ it is said to be in the ambipolar regime, and when $ \beta \approx 1$ it is said to be in the Hall regime.