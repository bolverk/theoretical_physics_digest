The optical depth of a medium of typical size $ R $ can be approximated by $ \frac{R}{l_{mfp}} $ where $ l_{mfp} $ is the mean free path of the medium and is given by $ l_{mfp}= \frac{1}{n \sigma} $ where $ n $ is the density of scatterers and $ \sigma $ is their cross section. The last expression can be easily understood by the following reasoning. Consider a cylinder with area $ S $ and containing a single scatterer with cross section $ \sigma $. If we send a photon in the cylinder, the chance of a collision with the scatterer is $ \frac{\sigma}{S} $. Consider now that the cylinder has scatterers of density $ n $, the chance of collision with a scatterer within a propagation length $ dx $ is now:

$ S dx n \frac{\sigma}{S}=\sigma n dx $

$ l_{mfp} $ is defined as the typical $ dx $traveled by the photon for which the probability of a collision is $ \sim 1 $ from which we obtain the expression $ l_{mfp}= \frac{1}{n \sigma} $.

For an isotropic optically thick medium ($ \tau \gg 1 $), the photon random walks through the medium. The photon's average location does not change, but the typical distance from the start location increases as the square root of the number of collisions. The root mean square length traveled by the photon is given by the mean free path length, and therefore after $ N $ scatterings the photon has typically propagated a length $ \sqrt{N} l_{mfp} $. The photon escapes the medium when the last expression equals $ R $. From this we obtain:

$ N=\bigg(\frac{R}{l_{mfp}}\bigg)^2 \sim \tau^2$. 

In the opposite limit, when $ \tau \ll 1 $ most photons will escape the medium with no scatterings. Let us look at the probability $ P(x) $ of the photon travelling up to a distance $ x $ without collision:$ P(x+dx)=P(x) (1-\frac{dx}{l_{mfp}}) \rightarrow P(x)+ \frac{dP}{dx}dx=P(x)-P(x)\frac{dx}{l_{mfp}} \rightarrow P(x)=e^{-\frac{x}{l_{mfp}}}$.

Thus the chance of the photon not undergoing a scattering process before it escapes the medium is $ e^{-\tau} $. The mean number of scatterings is the chance of the photon having been scattered: $ 1-e^{-\tau}\approx \tau $.

Therefore, for a general optical depth, the mean number of scatterings is: $ N\sim \tau (\tau+1) $.