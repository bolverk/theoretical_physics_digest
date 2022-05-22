Consider a luminous object at some point in space, an observer at another point, and in between is a layer of some medium with randomly varying refractive index, like our atmosphere. Let us suppose, further, that the variation in the refractive index are due to Kolmogorov turbulence. Such a turbulence is characterised by some dissipation term $ \varepsilon $ with units of energy loss per unit mass, or length squared divided by time cubed 

$ \left[ \varepsilon \right] = \frac{L^2}{T^3} $

We want to find the velocity structure function, given by

$ D_v \left(\vec{r}_1, \vec{r}_2 \right) = <|\vec{v} \left(\vec{r}_1 \right) -\vec{v} \left(\vec{r}_2 \right)|^2> $

Due to translational symmetry $ D_v $ can only depend on the magnitude of the difference between two position $ r = |\vec{r}_1 - \vec{r}_2| $. From dimensional analysis

$ D_v \approx \varepsilon^{2/3} r^{2/3} $. We assume that the turbulence is highly subsonic, so the the velocity perturbations cause temperature and density perturbations, such that the dependence of their structure function $r$ is the same. The refractive index $ n $ is some function of the density and temperature, so its structure function also has the same dependence on the distance $ D_n \propto r^{2/3} $.

From $ D_n $ we proceed to obtain the phase structure function $ D_{\phi} $. Since we are dealing with small perturbations, $ D_{\phi} \propto D_n $. The wave number should appear with the same power as the refractive index, so $ D_{\phi} \propto k^2 D_n $. In order to fix the units, we need to multiply by two length scale. We are interested in the difference in phase between two coherent photons that traversed the whole width of the layer, so one length scale should be the width of the layer $ \Delta z $. The other length scale must be $ r $, so

$ D_{\phi} \approx D_n k^2 r^{5/3} \Delta z $