Turbulence is a dissipation mechanism by which a fluid converts energy into heat. Mechanical energy is supplied through some external stirring mechanism which operates at large wavelengths, and dissipation converts said energy at low wavelengths. If the input power is constant, then at late times a steady state energy distribution in k space will emerge. The energy is related to the correlation function of the velocity

$ Q\left(\mathbf{r}\right) = \int \mathbf{u}\left(\mathbf{x}\right)\cdot\mathbf{u}\left(\mathbf{x}+\mathbf{r}\right) d^3x = $

$ = \int \mathbf{\tilde{u}}\left(\mathbf{k}\right)\cdot\mathbf{\tilde{u}}\left(\mathbf{q}\right) \exp\left(i\mathbf{k}\cdot\mathbf{x}\right)\exp\left(i\mathbf{q}\cdot\left(\mathbf{x+r}\right)\right) d^3x \frac{d^3k}{\left(2\pi\right)^3} \frac{d^3q}{\left(2\pi\right)^3} = $

$ = \frac{1}{\left(2\pi\right)^2} \int \mathbf{\tilde{u}}\left(\mathbf{k}\right)\cdot\mathbf{\tilde{u}}\left(\mathbf{q}\right) \delta\left(\mathbf{q}+\mathbf{k}\right)\exp\left(i\mathbf{q}\cdot\mathbf{r}\right) d^3k d^3q = $

$ = \frac{1}{\left(2\pi\right)^2} \int \mathbf{\tilde{u}}\left(\mathbf{k}\right)\cdot\mathbf{\tilde{u}}\left(\mathbf{-k}\right) \exp\left(-i\mathbf{k}\cdot\mathbf{r}\right) d^3k $

To further simplify that expression we will assume an isotropic distribution so $ Q\left(\mathbf{r}\right) = Q\left(r\right) $ and  $ \mathbf{\tilde{u}}\left(\mathbf{k}\right) \cdot \mathbf{\tilde{u}}\left(-\mathbf{k}\right) = E\left(k\right) $

$ Q\left(r\right) = \frac{1}{\left(2\pi\right)^2} \int_{-\infty}^{\infty} dk \int_0^{\pi} \sin \theta d\theta \int_{0}^{2\pi} d\phi E\left(k\right) \exp\left(ikr\cos\theta\right) = $

$ = \frac{1}{2\pi} \int_{-\infty}^{\infty} dk \int_0^{\pi} \sin \theta d\theta E\left(k\right) \exp\left(ikr\cos\theta\right) = $

$ = \frac{1}{\pi} \int_{-\infty}^{\infty} dk \frac{\sin\left(kr\right)}{kr} E\left(k\right) $

The function $ E\left(k\right) $ can now be determined by dimensional analysis. Suppose that the energy dissipation rate per unit mass is $ \varepsilon $, with units $ \left[\varepsilon\right] = \frac{L^2}{T^3} $. The dimesnions of $ E\left(k\right) $ are $ \left[E\right] = \frac{L^3}{T^2} $, and of $ k $ are $ \left[k\right] = \frac{1}{L} $. If $ E\left(k\right) $ only depends on $ \varepsilon $ and $ k $, then from dimensional analysis

$ E\left(k\right) \propto \varepsilon^{2/3} k^{-5/3} $