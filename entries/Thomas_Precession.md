This entry is largely based on [https://arxiv.org/pdf/1211.1854v1.pdf this paper].

Suppose we have an object going in a circle, such that its orbital angular momentum is $ \vec{L} $. Suppose further that this object is rotating around itself with angular momentum $ \vec{l} $. According to classical mechanics $ \vec{l} $ should not change in time, but special relativistic corrections cause $ \vec{l} $ to precess around $ \vec{L} $. This is called Thomass precession.

The way to calculate the rate of precession is by considering the action of the centripetal force as a series of infinitesimal boosts in different directions. Classically, if a object was moving at velocity $ \vec{\beta}_1 $ and is then boosted by $ \vec{\beta}_2 $, its velocity (and hence direction) would be given by $ \vec{\beta}_3 = \vec{\beta}_1 + \vec{\beta}_2 $. In relativity, however, the application of two Lorentz boosts yields a slightly different velocity

$ \vec{\beta}_4 = \frac{\gamma_1 \vec{\beta}_1 + \vec{\beta}_2 +\left(\gamma_1-1 \right ) \left(\vec{\beta}_1 \cdot \vec{\beta}_2 \right ) \vec{\beta}_1 / \beta_1^2}{\gamma_1 \left( 1 + \vec{\beta}_1 \cdot \vec{\beta}_2\right)} $

We will be interested in the limit where $ \beta_2 \ll \beta_1 < 1 $. The angle between the classical and relativistic directions is given by

$ \theta \approx \tan \theta = \frac{|\vec{\beta}_3 \times \vec{\beta}_4|}{\vec{\beta}_3 \cdot \vec{\beta}_4} \approx \frac{\gamma_1 - 1}{\gamma_1} \frac{|\vec{\beta}_1\times\vec{\beta}_2|}{\beta_1^2} = \frac{\gamma_1}{\gamma_1 + 1} |\vec{\beta}_1\times\vec{\beta}_2| $

By dividing by the time interval in which the boost happens it is possible to get the precession rate, assuming $ \theta = \Delta t \dot{\theta} $ and 
$ \vec{\beta}_2 = \Delta t \vec{a} $ is the acceleration

$ \dot{\theta} = \frac{\gamma_1}{\gamma_1+1} |\vec{\beta}_1 \times \vec{a}| $