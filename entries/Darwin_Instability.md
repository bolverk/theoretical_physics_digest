The Darwin instability is an orbital instability which occurs in binary systems where viscous dissipation exists. It is named after G. H. Darwin, who analyzed this instability in his [http://rspl.royalsocietypublishing.org/content/29/196-199/168 paper] from 1879.

== Derivation ==
Consider a binary system with a separation $a$. A key assumption is that the components are tidally locked - their rotation period about their axis is the same as the orbital period. This assumption is valid if the tidal synchronization timescale is sufficiently short to other orbital evolution timescales that characterize the system. If the total mass of the system is $M_T$, the orbital angular frequency is given by (Keplerian orbit):

$
\omega = \sqrt{\frac{GM_T}{a^3}}
$

If the moments of inertia of the two components are $I_1$ and $I_2$, then the total angular momentum of the system is given by:

$
J_T = J_{spin} + J_{orb} = (I_1 + I_2) \omega + \mu a^2 \omega = I \omega + \mu a^2 \omega
$

where $\mu$ is the reduced mass and $I = I_1 + I_2$.

The effective moment of inertia of the system is given by:

$
I_{eff} = \frac{dJ_T}{d\omega} = I - \frac{1}{3} \mu a^2
$

where we have taken the derivative $\frac{dJ_{orb}}{d\omega} = \mu a^2 + 2\mu a \omega \frac{da}{d\omega} $. Note that we have also assumed that the components' moments of inertia are independent of $\omega$ - meaning that the shapes of the components remain the same as the change their rotational frequency.

We see that for large orbital separations, $I_{eff} < 0$, implying that decrease in the total angular momentum results in an increase in $\omega$, like in Kepler's problem. At this regime, if some angular momentum is removed from the orbit, 

For sufficiently small angular separation - $a_{Darwin} = \sqrt{I/\mu}$.