This entry is largely based on [http://adsabs.harvard.edu/cgi-bin/bib_query?arXiv:astro-ph/9603018 this paper].

Let us think about a star cluster with $ N \gg 1 $ stars, each with mass $ m $. These stars rotate around a super massive black hole with mass $M \gg N m$, so the orbits are nearly Keplerian. The size of the cluster is $ R $, and the density of stars is uniform $ n\approx N / R^3 $. The average orbital velocity is $ v_o \approx \sqrt{G M/R}$, and the orbital period is $ t_o \approx \sqrt{R^3 / G M}$.

We first discuss non resonant relaxation. The simplest way to think about it is like collisions. By collisions, we do not mean that different stars come into contact, but only that they get close enough to alter each other's trajectory considerably. For this to happen, the distance between them has to be smaller than the Bondi radius

$ R_b \approx \frac{G m}{G M/R} \approx R \frac{m}{M} $

The average time between collisions is therefore

$ \tau_c \approx \frac{1}{n R_b^2 v_o} \approx \frac{M}{N m^2} \tau_o \gg \tau_o$

Over this timescale both the energy and angular momentum of each star can change considerably.

We note that due to the fact that the force field decreases as $ r^{-2} $, where $ r $ is the distance between two stars, collisions at any impact parameters contribute as much as collisions with impact parameter $ R_b $. This reduces the collision timescale by the Coulomb logarithm.

In the calculation above the central mass $ M $ only determined the velocity scale. However, it does more than that. It confines each particle to a narrow region in phase space. Thus, instead of thinking of each star as a moving point mass, one can consider a static mass distribution, where the mass of the star is distributed along its trajectory. A static mass distribution cannot change the star's energy, but it can exert torque and change the angular momentum.

Let us consider some star on an elliptical orbit. The orbital plane divides the cluster into two hemispheres. If the stars are randomly distributed, then the difference between the number of stars in each hemisphere is $ \sqrt{N} $. The average specific torque is therefore $ T \approx \sqrt{N} G m / R $. This torque changes on the precession timescale

$ \tau_p \approx \frac{N m}{M} \tau_o $

Precession occurs because each stars deviates from a Keplerian orbit around M because, on average, it feels gravity due to a slightly larger mass $ M + N m$. This precession, on its own, does not alter either the energy or the angular momentum, but it does reshuffle the orientations of the Keplerian ellipses. The change in angular momentum during $ \tau_p $ is $ \Delta L \approx T \tau_p N^{3/2} \sqrt{\frac{G M R}{N}}$. The time it takes for the accumulated change in angular momentum due to this random walk to be comparable to the average specific angular momentum $ L \approx \sqrt{G M R} $ is

$ \tau_r \approx \left(\frac{L}{\Delta L} \right)^2 \tau_p \approx \frac{M}{m} \tau_o $

This time scale is much smaller than the the timescale for non resonant relaxation.