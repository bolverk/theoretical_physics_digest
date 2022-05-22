Let us consider the following solar system: a star of mass $M$, orbited by a massless asteroid on a nearly circular orbit with semi major axis $a$, and a planet of mass $m$ on a perfectly circular orbit with semi major axis $a+x$, where $\left(\frac{m}{M}]right)^{1/3} \ll \frac{x}{a} \ll 1$ (i.e. the semi major axes are very close, but not so close that the asteroid enters the planet’s Hill sphere). In this entry we study how how the orbit of the asteroid evolves if the asteroid and the planet are in a first order mean motion resonance, i.e.

$ p \sqrt{\frac{a^3}{G M}} = \left(p-1\right)\sqrt{\frac{\left(a+x\right)^3}{GM}} \Rightarrow \frac{x}{a} \approx \frac{2}{3p} $

Where $p$ is some large integer. In this case, each conjunction (point where the asteroid is closest to the planet) happen at almost the same place each time.

== Circular Orbi ==
We use the impulse approximation to describe the interaction between the planet and the asteroid. The relative velocity between them is $ \sqrt{\frac{G M}{a}} \frac{x}{a}$, and so when the asteroid passes near the planet it gets a kick in the radial velocity

$ \Delta v_r \approx \frac{G m}{x^2} \sqrt{\frac{a^3}{G M}} $

We can calculate the kick in the tangential direction from the condition that the energy doesn’t change in the reference frame comoving with the planet

$ \Delta v_t \approx \Delta v_r^2 / \sqrt{\frac{G M}{a}} \frac{x}{a} \approx \frac{G^2 m^2}{x^5} \frac{a^4}{G M} / \sqrt{\frac{G M}{a}} $

The relative change in energy (and also semi major axis) is

$ \frac{\Delta a}{a} \approx \frac{\Delta U}{U} \approx \Delta v_t / \sqrt{\frac{G M}{a}} \approx \frac{m^2}{M^2} \frac{a^5}{x^5} $

The distance between neighbouring resonances is $ \delta a \approx a \left(\frac{1}{p} - \frac{1}{p+1}\right) \approx \frac{x^2}{a} $. The asteroid can be kicked to another resonance if

$ \Delta a > \delta a \Rightarrow \frac{x}{a} < \left(\frac{m}{M}\right)^{2/7} $

If this condition is satisfied, then the asteroid can break away from its starting resonance and explore large volumes of phase space. Therefore, this is the condition for chaotic evolution.

== Eccentric Orbit ==
In this section we will show that the resonance excites eccentricity $e$ in an initially circular orbit, and also saturates it at a high enough value. To do so, we will calculate differences in energies between one conjunction and the next one. These differences are due to the fact that the orbit of the asteroid does not close. Will will consider two effects which shift the ending point from the starting point.

=== Periapse Drift ===
We’ve seen in the previous section that the planet gives the asteroid a radial kick velocity. This kick changes the LRL vector by
$ \Delta A \approx \Delta v_r \sqrt{G M a} \approx G m \frac{a^2}{x^2} $
The initial value of the LRL vector is $A=GMe$, so the rotation angle of the periapse is given by

$ \psi \approx \frac{\Delta A}{A} \approx \frac{1}{e} \frac{m}{M} \frac{a^2}{x^2} $

Due to this drift, the asteroid would be at a different radius, and so the potential energy difference would be

$ \Delta U_{pd} \approx \frac{G m}{x + e \cos \theta} - \frac{G m}{x + e \cos \left(\theta+\psi\right)} \approx \frac{G m}{x} \frac{a^3}{x^3} \sin \theta $

Where we assume $1 \gg e \gg \frac{m}{M} \frac{a^2}{x^2} $

=== Mean Motion Shift ===
We’ve shown that each conjunction induces a radial velocity kick $ \Delta v_r $. This velocity changes the eccentricity by

$ \Delta e \approx \frac{\Delta v_r}{\sqrt{G M/a}} \approx \frac{m}{M} \frac{a^2}{x^2} $

In the eccentric case, conjunction happens at a slightly different place compared with the circular case. The difference in time between conjunction in the circular case to conjunction in the eccentric case is given by the ratio between the velocity and acceleration differences in the radial direction

$ \Delta t \approx e \sin \theta \sqrt{\frac{G M}{a}} / \frac{G M}{a^3} x \approx e \frac{a}{x} \sin \theta \sqrt{\frac{a^3}{G M}} $

This time difference translates to a difference in angle of

$ \alpha e \frac{a}{x} \sin \theta $

And so the tangential component of the kick is

$ \Delta v_t \approx \alpha \Delta v_r \approx \frac{G m}{x^2} \sqrt{\frac{a^3}{G M}} e \frac{a}{x} \sin \theta $

The relative change in energy, and therefore in mean motion, is

$ \frac{\Delta n}{n} \approx \frac{\Delta U}{U} \approx \frac{\Delta v_t}{\sqrt{G M/a}} \approx e \frac{m}{M} \frac{a^3}{x^3} \sin \theta $

Since conjunctions happen at roughly the same place each time, there is a connection between the mean motion and the eccentricity

$ \frac{1}{n} \frac{d n}{d e} \approx e \frac{a}{x} \Rightarrow \frac{\Delta n}{n} \approx e^2 \frac{a}{x} $

Between one conjunction and the next one, the difference in mean motion causes a phase shift of $ \beta \approx \frac{\Delta n}{n} \frac{a}{x} $. The difference in potential energies is

$ \Delta U_{mm} \approx \frac{G m}{x + e \cos \theta} - \frac{G m}{x+e \cos \left(\theta + \beta\right)} \approx \frac{G m}{x} \frac{a^3}{x^3} e^3 $

Both potential energies balance each other when

$ \Delta U_{mm} \approx \Delta U_{pd} \Rightarrow e \approx \left(\frac{m}{M}\right)^{1/3} $

Hence, an asteroid starting on a circular orbit will increase its eccentricity until it is comparable to the value obtained above.