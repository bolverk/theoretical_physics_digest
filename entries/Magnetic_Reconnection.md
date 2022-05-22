In magnetic reconnection, opposite magnetic field lines embedded in a plasma approach each other and merge. As a result, the configuration of the magnetic field changes. The difference in magnetic energy goes into the acceleration of plasma particles.

== Sweet Parker Model ==
Let us consider a steady state, two dimensional flow, as portrayed in the schematic below.
[[File:Magnetic reconnection.png|thumb|220x220px]]
The region where reconnection happens is marked by a grey rectangle. Outside the grey rectangle the magnetic field gradients are not so large, so that magnetic diffusion can be neglected, and the plasma can be assumed to have infinite conductivity. The electric field is given by Ohm's law

$ E_z \approx B \frac{V_{in}}{c} $.

Inside the reconnection zone, the magnetic field changes on a scale $ \delta $. By Ampere's law 

$ J_z \approx \frac{c}{4 \pi} \frac{B}{\delta} $.

Applying Ohm's law inside the reconnection zone (where the conductivity must be finite)

$ J_z = \sigma E $.

Putting it all together yields

$ V_{in} \approx \frac{c^2}{4 \pi \sigma \delta} $.

Plasma is flowing at a speed $ V_{in} $ to the reconnection region through a sheet of thickness $ L $, carrying with it a magnetic field $ B $. For simplicity we assume that the magnetic field is (anti -) parallel to the $ \hat{y} $ direction. We also assume that the fluid is moving at a speed much lower than the Alfven speed $ V_A $, so the flow can be considered incompressible. The fluid leaves the reconnection region at a speed $ V_{out} $ through a sheet of width $ \delta $. The inflow must match the outflow, hence

$ V_{in} L = V_{out} \delta $.

All the magnetic energy goes into accelerating the fluid

$ B^2 \approx \rho V_{out} \Rightarrow V_{out} \approx \frac{|B|}{\sqrt{\rho}} = V_A $

so we get that the exit velocity is comparable to the Alfven velocity. Combining the two equations for the velocities gives

$ \frac{V_{in}}{V_{out}} \approx \sqrt{\frac{c^2}{4 \pi L \sigma V_A}} = S^{-1/2} $

where $ S = \frac{4 \pi L \sigma V_A}{c^2} $ is the Lundquist number.