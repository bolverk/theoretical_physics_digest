Let us consider a sun, earth and moon system, in a rotating frame where the earth and moon are fixed, and the sun is rotating around them. As a result, the spin direction of the moon $\mathbf{s}$ would feel a torque that would try to align in parallel to the orbital angular momentum of the moon around the earth (direction $\mathbf{j}$). The moon also experience tides from the sun. These tides tend to align the spin of the moon either parallel or anti parallel to the orbital angular momentum of the earth around the sun (direction $\mathbf{l}$).

The Hamiltonian is given by

$H \approx -g \left(\mathbf{s} \cdot \mathbf{j}\right) - \alpha \left(\mathbf{s} \cdot \mathbf{l}\right)^2 + \Lambda \left(s^2-1\right)$

where $g$ is a constant the measure the strength of the torque from the earth, and $\alpha$ is a constant that measures the strength of the tides from the sun, and the last term is the Largrange multiplier, which allows us to assume $\mathbf{s}$ can have arbitrary magnitudes, and worry later about normalisation. We proceed to find the fixed points

$\frac{\partial H}{\partial \mathbf{s}} = -g \mathbf{j} - 2 \alpha \left(\mathbf{l} \otimes \mathbf{l} \right)  \mathbf{s} + 2 \Lambda \mathbf{s}  = 0$

$\mathbf{s} = \frac{g}{2} \left[\Lambda + \alpha \mathbf{l} \otimes \mathbf{l} \right]^{-1} \mathbf{j}$

Inverting the matrix (using the fact the inverse would be a linear combination of the identity matrix and $\mathbf{l} \otimes \mathbf{l}$) yields

$\left[\Lambda + \alpha \mathbf{l} \otimes \mathbf{l}\right]^{-1} = \frac{1}{\Lambda} - \frac{\alpha}{\Lambda \left(\Lambda + \alpha \right)} \mathbf{l} \otimes \mathbf{l}$

so

$\mathbf{s} = \frac{g}{2} \left[\frac{1}{\Lambda} - \frac{\alpha}{\Lambda \left(\Lambda + \alpha\right)} \mathbf{l} \otimes \mathbf{l} \right] \mathbf{j} = \frac{g}{2 \Lambda} \mathbf{j} - \frac{g \alpha \left(\mathbf{l} \cdot \mathbf{j}\right)}{2 \Lambda \left(\Lambda + \alpha\right)} \mathbf{l}$

We proceed to determine $\Lambda$ from the condition that $s^2 = 1$

$s^2 = \frac{g^2}{4 \Lambda^2} + \frac{g^2 \alpha^2 \left(\mathbf{l} \cdot \mathbf{j}\right)^2}{4 \Lambda^2 \left(\Lambda + \alpha\right)^2} - \frac{g^2 \alpha \left(\mathbf{l} \cdot \mathbf{j}\right)^2}{2 \Lambda^2 \left(\Lambda+\alpha\right)} = 1$

$\frac{g^2}{4 \Lambda^2} \left[1 - \alpha \frac{\alpha + 2 \Lambda}{\left(\alpha + \Lambda\right)^2} \left(\mathbf{l} \cdot \mathbf{j}\right)^2\right] = 1$

One family of solutions is obtained by considering the asymptotic case $\Lambda^2 \gg \alpha^2$

$\Lambda \approx \pm\frac{g}{2}$

$\mathbf{s} \approx \pm \mathbf{j}$

This solution applies when $g \gg \alpha$. Another family of solutions is obtained by considering the asymptotic case $\Lambda^2 \ll \alpha^2$

$\Lambda \approx \pm \frac{g}{2} \sqrt{1-\left(\mathbf{l} \cdot \mathbf{j}\right)^2}$

$\mathbf{s} \approx \pm \frac{\mathbf{j}-\left(\mathbf{j} \cdot \mathbf{l}\right) \mathbf{l} }{\sqrt{1-\left(\mathbf{l} \cdot \mathbf{j}\right)^2}}$

This solution applies when $\alpha \gg g$. Another family of solutions can be found by considering the limit $\alpha + \Lambda \rightarrow 0$

$\Lambda \approx -\alpha \pm \frac{g}{2} \left(\mathbf{l} \cdot \mathbf{j}\right)$

$\mathbf{s} \approx \mathbf{l} - \frac{g}{2 \alpha} \mathbf{j}$

This solution only exists in the limit $\alpha \gg g$.










The end