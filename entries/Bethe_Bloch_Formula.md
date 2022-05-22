Let us consider a particle with charge $ q $ moving by another, initially stationary particle with charge $ Q $ and mass $ M $, at velocity $ v $ and impact parameter $ b $ (the minimum distance between the particles). Most of the interaction between the particles occurs on a time scale $ \Delta t \approx b/v $, where the force between them is of the order of $ f \approx \frac{q Q}{b^2} $. The momentum $ Q $ receives is $ \Delta p \approx f \Delta t \approx \frac{q Q}{b v}$, and so its kinetic energy is $ \Delta E \approx \frac{\Delta p^2}{M} \approx \frac{q^2 Q^2}{b^2 v^2 M} $. This energy comes at the expense of the kinetic energy of $ q $. The rate at which such collisions occur is $ n v b \cdot db $, where $ n $ is the number density of particles $ Q $. To get the net energy loss rate of $ q$, we integrate over all possible values of $ b $

$ \dot{E} \approx \int_{b_{\min}}^{b_{\max}} \Delta E n v b \cdot d b \approx \frac{q^2 Q^2}{M} n \ln \frac{b_{\max}}{b_{\min}} $

The upper bound is not so interesting, because it depends on the medium. For example, one possible option for this cutoff is the Debye length of the plasma. The lower bound is the impact parameter for which $ q $ loses all of its energy $ E $. Hence,

$ \dot{E} \approx - \frac{q^2 Q^2}{M} n \ln \frac{E}{E_0} $

where $ E_0 $ is some energy scale determined by $ b_{max} $.