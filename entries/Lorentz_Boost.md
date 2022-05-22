The Lorentz boost transforms 4 vectors from one intertial reference frames to the other. The common form of this transformation is

$ c t \rightarrow ct \gamma + \beta \gamma x $

$ x \rightarrow \gamma x + \beta \gamma c t $

$ y \rightarrow y $

$ z \rightarrow z $

where $\gamma = \left(1-\beta^2\right)^{-1/2}$, $ \beta = v/c $, $ v $ is the relative velocity between the two reference frames and $ c $ is the speed of light. We would like to generalise this transformation to a general velocity vector $ \vec{\beta} $. To so this, we split the position vector into a component parallel and perpendicular to $ \vec{\beta} $. The parallel component $ x = \vec{\beta} \cdot \vec{r} / \beta $ transforms in the way described above, and the perpendicular component does not change. Hence 

$ c t \rightarrow c t \gamma + \gamma \vec{\beta} \cdot \vec{r} $

$ \vec{r} \rightarrow \gamma \frac{\vec{\beta} \cdot \vec{r}}{\beta^2} \vec{\beta} + \vec{r} - \frac{\vec{\beta} \cdot \vec{r}}{\beta^2} \vec{\beta} +  \gamma \vec{\beta} c t$

Hence the transformation matrix can be written in the following form

$ \Lambda \left( \vec{\beta} \right) = \begin{pmatrix}
\gamma  & \gamma \vec{\beta}\\ 
\gamma \beta^T & 1 + \left(\gamma-1 \right )\frac{\vec{\beta}^T\vec{\beta}}{\beta^2}
\end{pmatrix} $

where $ \vec{\beta}^T \vec{\beta} $ is an outer an outer product (i.e. a tensor) rather than a scalar.