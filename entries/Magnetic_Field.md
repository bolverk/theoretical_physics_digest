In this entry we present some lesser known mathematical identities related to magnetic fields.

== Rotation Matrix ==
Let us consider the non relativistic motion of a charged particle in a uniform magnetic field

$ \frac{\partial \mathbf{v}}{\partial t} = \frac{q}{m c} \mathbf{v} \times \mathbf{B} $

where $ \mathbf{v} $ is the velocity, $ q $ is the electric charge of the particle, $ m $ is the mass of the particle, $ c $ is the speed of light and $ \mathbf{B} $ is the magnetic field.

We can write this equation in a different form

$ \frac{\partial \mathbf{v}}{\partial t} = \mathbf{G} \mathbf{v} $

where

$ \mathbf{G} = \frac{q}{m c} \varepsilon \mathbf{B} $

is a generator for a rotation and 

$ \varepsilon \mathbf{B} = \begin{pmatrix} 0 & B_z & -B_y\\ -B_z & 0 & B_x\\ B_y & -B_x & 0 \end{pmatrix}$

is the tensor product of the magnetic field vector and the Levi Civita antisymmetric tensor. The last term is the same as the magnetic field block in the anti-symmetric electromagnetic tensor.

The solution for the equation of motion is

$ \mathbf{v} \left(t\right) = \exp \left(t \mathbf{G} \right) \mathbf{v} \left( 0 \right) $

where a matrix exponent is implied. Because $ \mathbf{G} $ is anti-symmetric, then $ \exp \left( t \mathbf{G} \right) $ is a rotation matrix whose angle increases linearly with time.