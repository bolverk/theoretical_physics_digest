Bremsstrahlung is the radiation produced when a particle in a plasma scatters of another particle. It is called Free-free emission since the scattered particle is unbound to the scatterer both before and after the scattering process. Consider an electron-proton plasma. Since the rate of scatterings of electrons off either electrons or protons is higher then that of processes where the proton is the scattered particle, the former will be the significant source of radiation and energy loss. For concreteness we shall consider an electron scattering off of a proton.

The time of interaction between the electron and the proton is the approximate time the electron spends in the Coulomb potential of the proton: $ \tau \approx \frac{b}{v} $ where $ b$ is the impact parameter and $ v$ is the velocity of the electron. During this time, the acceleration of the electron is mostly in the direction perpendicular to its motion and is roughly constant. It can be approximated by the force felt by an electron at a distance $ b$ from a proton, divided by its mass $ m_e$: 

$ a=\frac{e^2}{m_e b^2} $

where $ e $ is the electron. The Larmour equation gives as the total emitted power by the electron:

$ P=\frac{2e^2a^2}{3c^3}\approx \frac{e^6}{m_e^2 c^3 b^4} $

where $ c $ is the speed of light. The typical frequency of the radiation is given by:

$ \nu=\frac{2\pi}{\tau}=\frac{2\pi v}{b} $

Since a given impact parameter corresponds to a specific frequency, we can obtain the spectral power by calculating the relative contribution of electrons at different impact parameters. For a distribution of electrons with similar velocities and different impact parameters,  the total energy released from a ring of impact parameter $ b $ is:

$ dU=P N_p n_e v 2 \pi b db $,

where $ N_p $ is the number of proton scatterers contributing to the force. Therefore, using: $ \frac{db}{d\nu}=\frac{v}{2 \pi \nu^2} $ we obtain:

$ U_{\nu}=\frac{dU}{d\nu}\approx N_p n_e \frac{e^6}{c^3 m_e^2 v} $.

Notice that the spectral flux is inversely proportional to the velocity and independent of frequency.

Finally, we calculate the emissivity, i.e. the power radiated by the electrons per unit volume of the plasma. Since the radiation is isotropic we divide by $ 4 \pi $ to obtain the the emission function per unit solid angle:

$ j(\nu)=\frac{n_e n_p}{4 \pi} \frac{e^6}{m_e^2 c^3}\bigg(\frac{m_e}{K_B T}\bigg) ^{1/2} $

One can integrate over $ \nu $ to obtain the total emissivity. The integral depends critically on $ \nu_{max} $. If the electrons have a Maxwellian distribution of velocities, we may reasonably expect $ h \nu_{max}\approx K_B T $. However, there would still be an exponentially falling contribution at higher frequencies. We obtain that:$ j_{tot}\approx j(\nu) \nu \approx \frac{n_e n_p}{4 \pi} \frac{e^6}{m_e^2 c^3}\frac{(m_e K_B T)^{1/2}}{\hbar} $

As we saw, the spectrum is flat below the maximal frequency, and falls of exponentially above it.
[[Category:Radiation mechanisms]]
[[Category:Plasma physics]]