A supernova explosion ejects a hot and fast shell from the progenitor star. The ejecta expand with a uniform velocity $v_0$. We are interested in the time evolution of the thermal energy density $u$, and later the luminosity $L$. In the next sections we consider the effect of different processes on the evolution of the shell’s thermal energy.

= Adiabatic Evolution =
The energy of the shell is given by $U = u V$, where $V \approx v_0^3 t^3$ is the volume of the shell. The adiabatic loss is given by $ p \dot{V}$, where $p=u/3$ according to blackbody relations. Hence

$ \frac{d U}{d t}  = -\frac{u}{3} \frac{d V}{d t} \Rightarrow u = u_0 \left(\frac{t}{t_0}\right)^{4}$

Where $u_0$ is the energy density at some initial time $t_0$ (later than the ejection time).

= Radiative Cooling =
The cooling rate is given by

$ L \approx \frac{c R V}{\kappa M} u $

where $M$ is the mass of the ejecta, $c$ is the speed of light, $\kappa$ is the opacity and $ R = v_0 t$ is the radius of the shell. The energy equation with both adiabatic and radiative losses has the form

$ \frac{d U}{d t} = -\frac{u}{3} \frac{d V}{d t} - L $

Solving for $ u $ yields

$ u \approx u_0 \left(\frac{t_0}{t}\right)^{4} \exp \left(-\frac{c v_0}{\kappa M} \left(t^2-t_0^2\right)\right)$

Hence, the evolution is adiabatic up to the point where the photon diffusion time is shorter than the dynamical time $t_d \approx \sqrt{\frac{\kappa M}{c v_0}}$. After that, the radiation escapes almost instantaneously. We note that at $t_d$ the shell is still optically thick (since $c>v$) and only later does it become optically thin.

The luminosity is given by

$ L \approx \frac{u t_0^3 v_0^3}{t_d} \frac{t_0}{t_d} \exp\left(-\frac{t^2-t_0^2}{t_d^2}\right) $

= Heating =
Heat can be continuously injected to the ejecta by radiation from the remnant neutron star or the decay of radioactive material. For our purposes, the exact nature of heating is not important, so long as it does not depend on the conditions of the ejecta, but only on time. We also assume that the heating rate is larger than the energy loss of the residual initial energy calculated in the previous section. If we denote the heating function by $H$, then the energy equation becomes

$\frac{d U}{d t}=-\frac{u}{3} \frac{d V}{d t}-L+H$

When $t>t_d$, we can effectively assume $u=0$, so the luminosity is equal to the heating function $L=H$.

When $t<t_d$, we can neglect the radiative term, and obtain an analytic solution

$ u = u_0 \left(\frac{t_0}{t}\right)^{4} + \frac{1}{v_0^4 t_0^4} \int_{t_0}^{t} \tau H \left(\tau\right) d \tau$

And the luminosity is given by

$ L = \frac{u_0^3 t_0^3 u_0}{\t_d} \frac{t_0}{t_d}+ \frac{1}{t_d^2} \int_{t_0}^t \tau H \left(\tau\right) d \tau $

It is also possible to obtain a complete analytic solution for the entire time range

$ L = \exp(-\frac{t^2-t_0^2}{t_d^2}\right) \left[\frac{u_0^3 t_0^3 u_0}{\t_d} \frac{t_0}{t_d}+ \frac{1}{t_d^2} \int_{t_0}^t \tau H \left(\tau\right) \exp\left(-\frac{\tau^2-t_0^2}{t_d^2}\right) d \tau\right]$