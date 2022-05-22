== Emission spectrum from given particle spectrum ==
As shown in [[Synchrotron radiation]] the power emitted by a relativistic electron through synchrotron radiation is $ P \propto \gamma^2 $. For a distribution of electrons, this is equivalent to $ P \propto \nu $, where we have assumed that electrons of different energies dominate the emission at their respective synchrotron frequencies (this is equivalent to approximating the contribution of each electron as a delta function emission function around its corresponding synchrotron frequency). In particular it implies that $ \frac{dP}{d\nu}=const$. Assuming a power law distribution of electron energies: $ \frac{dN}{d\gamma} \propto \gamma^{-p} $, we obtain the well known result:

$ F_{\nu}=\int_{\gamma(\nu)}^\infty d\gamma \frac{dN}{d\gamma} P(\nu)\propto \nu^{-(p-1)/2} $

== Effect of synchrotron cooling on the electron distribution ==
A characteristic frequency in the synchrotron spectrum, is the so called "cooling frequency", $ \nu_c=\nu_{syn}(\gamma_c) $. This is the typical frequency of radiation emitted by electrons that are cooling on a given time-scale  $ t $ (this is typically the dynamical time of a system or its life-time). Electrons with $ \gamma>\gamma_c $ are cooled significantly by time $ t $, while lower energy electrons are not. We can estimate $ \gamma_c $ by equating the total energy losses through synchrotron over a time $ t $ with the initial energy in the electron:

$ P t = E \rightarrow \frac{4}{3}\sigma_T c \gamma_e^2 \frac{B^2}{8 \pi} t =\gamma_c m_e c^2 \rightarrow \gamma_c=\frac{6 \pi m_e c}{\sigma_T B^2 t} $.

The distribution of electron energies at $ \gamma>\gamma_c $ will be affected by cooling. This can be seen from the continuity equation for electrons in the energy space:

$ \frac{\partial}{\partial t}\bigg(\frac{dN}{d\gamma}\bigg)+\frac{\partial}{\partial \gamma}\bigg(\dot{\gamma}\frac{dN}{d\gamma}\bigg)=S(\gamma) $

where $ \dot{\gamma}\propto \gamma^2B^2 $ is the cooling rate and $ S(\gamma) $ is the rate at which electrons with Lorentz factor $\gamma $ are injected into the system. A steady state solution ($ \frac{\partial}{\partial t}=0 $) of this equation (assuming a time dependent magnetic field) is $ \frac{dN}{d\gamma} \propto \gamma^{-2} $ for $ \gamma_c <\gamma <\gamma_m $, where $ \gamma_m $ is the minimum Lorentz factor of injected electrons (i.e. $ S(\gamma)=0 $ for $ \gamma <\gamma_m $). The synchrotron spectrum corresponding to this energy range can be calculated as above (with $ p=2 $) and gives: $ F_{\nu}\propto \nu^{-1/2} $.  For $ \gamma>\gamma_m>\gamma_c $ we plug $ S(\gamma)\propto \gamma^{-p} $ in the continuity equation, to get: $ \frac{dN}{d\gamma} \propto \gamma^{-(p+1)} $, leading to $ F_{\nu}\propto \nu^{-p/2} $. These results are known as the fast cooling synchrotron spectrum.
[[Category:Radiation mechanisms]]