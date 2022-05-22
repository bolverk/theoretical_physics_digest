The fact that different frequency modes of an electromagnetic wave traveling through a plasma medium, propagate at different group velocities, creates a dispersion that enables us to calculate the distance of different astrophysical sources. Imagine, for instance, a pulsar at a distance $ d$ from earth. The time it takes for a pulse with frequency $ \omega $ to get to earth is:

$ t_p=\int_0^d \frac{ds}{v_g(\omega)} $

where $ ds$ is a path element along the line of sight and $ v_g(\omega) $ is the group velocity for a wave with frequency $ \omega $. The plasma frequency in the ISM is very low (about $ 10^3 $Hz) so we can safely assume $ \omega \gg \omega_p $ for practical purposes. We then ca

$ \omega^2=\omega_p^2+c^2k^2 $ and:

$ v_g(\omega)=\frac{\partial \omega}{\partial k}=c \sqrt{1-\frac{\omega_p^2}{\omega^2}} $

which leads to:

$ \frac{1}{v_g}=\frac{1}{c} (1-\frac{\omega_p^2}{\omega^2})^{-1/2} \approx \frac{1}{c} (1+\frac{1}{2} \frac{\omega_p^2}{\omega^2}) $

and plugging into $ t_p $:

$ t_p=\int_0^d \frac{1}{c}(1+\frac{1}{2} \frac{\omega_p^2}{\omega^2})ds=\frac{d}{c} +\frac{1}{2c\omega^2} \int_0^d \omega_p^2 ds $

The first term is just the time it would take the signal to travel the same distance in a vacum. The second term is the correction for plasma, which is frequency dependent. In practice, one measures the difference in arrival time as a function of frequency $ \frac{dt_p}{d\omega} $. Plugging $ \omega_p $ this is:

$ \frac{dt_p}{d\omega}=-\frac{4 \pi e^2}{c m_e \omega^3} D $

where $ D\equiv \int_0^d n ds $ is known as the dispersion measure of the plasma. Finally, if the density of the plasma is known, one can estimate the distance to the pulsar by measuring $ \frac{dt_p}{d\omega} $.