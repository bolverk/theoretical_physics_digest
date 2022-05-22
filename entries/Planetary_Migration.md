We consider a disk around a star of mass $ M_s $. At a distance $ r $ from that star is a planet of mass $ M_p $. The planet interacts gravitationally with a fluid element at a radius $ r_f $ such that $ b = r - r_f \ll r $. Both the fluid element and the planet are moving along circular Keplerian orbits around the star, so the velocity difference between them is

$ u  = \sqrt{\frac{G M_s}{r}} - \sqrt{\frac{G M_s}{r - b}} \approx \sqrt{\frac{G M_s}{r}} \frac{b}{r}$

Most of the deflection occurs when the distance between the planet and the fluid element is about $ b $, and the time interval when both are that close is about $ b/u $. The velocity deflection perpendicular to the fluid element's original direction of motion is therefore

$ \Delta v_{\perp} \approx \frac{G M_p}{b^2} \frac{b}{u} \approx \frac{G M_p}{b^2} / \sqrt{\frac{G M_s}{r^3}} \approx \sqrt{\frac{G M_s}{r}} \frac{M_p}{M_s} \left( \frac{b}{r} \right)^2 $

Conservation of energy dictates that there must also be a change in the component of velocity parallel to the original trajectory

$ \Delta v_{\parallel} \approx \sqrt{u^2-\Delta_{\perp}^2} - u \approx - \frac{\Delta v_{\perp}^2}{u} \approx - \sqrt{\frac{G M_s}{r}} \left( \frac{M_p}{M_s}\right)^2 \left( \frac{r}{b} \right)^5 $

If the mass of the fluid element is $ d m $, then the exchange of angular momentum is $ \Delta L \approx dm \Delta v_{\parallel} r $. The mass of the fluid element is given by $ dm = 2 \pi \Sigma r \cdot db $, where $ db $ is the width of the annulus. The time it takes the annulus to interact with the planet is just

$ t \approx \frac{2 \pi}{\Omega_p - \Omega_f} = \frac{2 \pi}{\sqrt{G M_s/r^3} - \sqrt{G M_s / \left( r - b\right)^3}} \approx 2 \pi \frac{r /b}{\sqrt{G M_s/r^3}} $

The torque between the annulus and the planet is given by

$ dT = \frac{\Delta L}{t} \approx \sqrt{\frac{G M_s}{r}} \left( \frac{M_p}{M_s}\right)^2 \left( \frac{b}{r}\right)^5 r \cdot r \cdot \Sigma \cdot db \cdot \frac{\sqrt{G M_s / r^3}}{r/b} $

The total torque is

$ T = \int_{b_{\min}}^{\infty} dT \approx G M_s \Sigma r \left(\frac{M_p}{M_s} \right)^2  \left( \frac{r}{b_{\min}} \right)^3 $

The lower limit on the integration is the minimum of either the scale height of the disk or the radius of the Hill sphere. In the case of the latter,

$ b_{\min} \approx r \left( \frac{M_p}{M_s} \right)^{1/3} $

and

$ T = G M_p \Sigma r $