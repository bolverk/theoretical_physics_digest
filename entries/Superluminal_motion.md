Consider a source moving at a velocity $ v=\beta c $and at an angle $ \theta $ relative to the line of sight. We will show that for $ \beta \rightarrow 1 $ it is possible to get apparent velocities larger than the speed of light.

To see this, we look at the time difference between the arrival of two photons, the first emitted at $ t_1 $ and the second emitted at  $ t_2\equiv t_1+\Delta t $.

The arrival time of the first photon is:

$ t_1'=t_1+\frac{D_1}{c} $

where $ D_1 $ is the distance between the location of the source at $ t_1 $ and the observer. However, by the time the second photons is emitted, the distance to the observer has changed. Since for astrophysical purposes, this change is much smaller than $ D_1 $, we can approximate it by calculating the distance covered by the source along the line of sight, during the time interval $ \Delta t $:

$ D_2=D_1-\beta c \Delta t cos(\theta) $

Yielding:

$ t_2'=t_2+\frac{D_2}{c}=t_2+\frac{D_1}{c}-\beta \Delta t cos(\theta) $.

We therefore see that the time between the arrival of the two photons becomes:

$ t_2'-t_1'=\Delta t (1-\beta cos(\theta)) $.

By observing an astrophysical source, we only see its change in position in the transverse direction to the line of sight. The apparent velocity is therefore the change in the transverse position of the source between the arrival time of the photons:

$v_{app}=\frac{\beta c sin(\theta) \Delta t}{\Delta t (1-\beta cos(\theta))}=\frac{\beta c sin(\theta)}{1-\beta cos(\theta)}$.

Due to the difference between emission and observation times, this velocity may be larger than light-speed.

To find the maximum apparent velocity we differentiate this function with respect to $ \theta $ and equate with 0:$\frac{d v_{app}}{d\theta}=\frac{\beta c}{1-\beta cos(\theta)}-\frac{c \beta ^2 sin^2(\theta)}{(1-\beta cos(\theta))^2}=0\rightarrow cos(\theta_{max})=\beta \rightarrow sin(\theta_{max})=1/\gamma$

where $ \gamma $ is the Lorentz factor. Plugging this back to $ v_{app} $ we get that:

$ v_{app,max}= \frac{\beta c sin(\theta_{max})}{1-\beta cos(\theta_{max})}=\frac{\beta c/\gamma}{1-\beta^2}=\beta \gamma c$.

Therefore, for $ \beta>1/\sqrt{2} $ the apparent velocity is greater than light-speed. Observation of high apparent velocities in astrophysical sources provides evidence of relativistic motion and can be used to provide lower limits on their Lorentz factors. This technique has been applied, for instance, to AGN jets.