 
## Definition of Specific Intensity or Brightness


The flux is a measure of the energy carries by all rays passing through a given area.

Construct an area $dA$ normal to the direction of the given ray and consider all rays passing through $dA$ whose direction is within a solid angle $\Omega$ of the given ray. 

The energy crossing $dA$ in time $dt$ and in frequency range $d\nu$:

$$ dE = I_\nu \ dA \ dt \ d\Omega \ d\nu,$$
where
- $I_\nu$: specific intensity (or brightness)
	- Depends on location in space, on direction, and on frequency


### Dimensional Analysis of $I_\nu$

$$ \begin{aligned} I_\nu (\nu,\Omega) & =\mathrm{\ (energy) \ (time)^{-1} \ (area)^{-1} \ (solid \ angle)^{-1} \ (frequency)^{-1}} \\ & = \mathrm{\ erg \ s^{-1} \ cm^{-2} \ ster^{-1} \ Hz^{-1}} \end{aligned}.$$


---
## Net Flux


Now, we have a radiation field. 

Construct a small element of area $dA$ at some arbitrary orientation $\bf{n}$.

The differential amount of flux from the solid angle $\Omega$ reduced by the lowered effective area $\cos \theta \ dA$:

$$ dF_\nu(\rm{erg \ s^{-1} \ cm^{-2} \ Hz^{-1}}) = I_\nu \ \cos\theta \ d\Omega. $$


The net flux in the direction $\bf{n}$, $F_\nu(\bf{n})$ is obtained by integrating $dF$ over all solid angles:

$$ F_\nu = \int I_\nu \cos\theta \ d\Omega.$$

Note, if $I_\nu$ is an isotropic radiation field, then the net flux is zero, since $\int \cos\theta \ d\Omega = 0$.

---
## Momentum Flux Normal to $dA$ = Pressure

(Momentum flux normal to $dA$)
= (Momentum per unit time per unit area)
= (Pressure)

- (Momentum of a photon) = $E/c$
- (Momentum flux along the ray at angle $\theta$) = $dF_\nu/c$.


To get the component of momentum flux normal to $dA$, we multiply the net flux by another factor of $\cos\theta$. Integrating, we get


$$ \mathrm{(Momentum \ Flux \ Normal \ to \ } dA) = \mathrm{(Net \ Flux)} \times \cos\theta $$

$$ p_\nu \mathrm{(dynes \ cm^{-2} \ Hz^{-1})}  = \frac{1}{c} \int I_\nu \cos^2\theta d\Omega. $$

Note that $F_\nu$ and $p_\nu$ are moments (multiplications by powers of $\cos\theta$ and integration over $d\Omega$) of the intensity $I_\nu$


Then for the total (integrated) values are:

$$ F \,(\mathrm{erg \ s^{-1} \ cm^{-2}}) = \int F_\nu d\nu$$

$$ p \,(\mathrm{dynes \ cm^{-2}}) = \int p_\nu d\nu$$

$$ I \,(\mathrm{erg \ s^{-1} \ cm^{-2} \ ster^{-1}}) = \int I_\nu d\nu$$

---
## Radiative Specific Energy Density ($u_\nu$)

The energy per unit volume per unit frequency range.


### Energy density per unit solid angle ($u_\nu(\Omega)$)

$$ dE = u_\nu(\Omega) \, dV \, d\Omega \, d\nu $$

- $dV$: Volume element.


Consider a cylinder about a ray of length $ct$, and the volume of the cylinder is $dV = dA \, c \, dt$:

$$  dE = u_\nu(\Omega) \, dA \,c \,dt \, d\Omega \, d\nu  $$

Radiation travels at velocity $c$, so in time $dt$, all the radiation in the cylinder will pass out of it:

$$ dE = I_\nu \, dA \, d\Omega \, dt \,d\nu $$

Then,
$$u_\nu(\Omega) = \frac{I_\nu}{c}. $$

Integrating over all solid angle:

$$ u_\nu = \int u_\nu(\Omega) \, d\Omega = \frac{1}{c} \int I_\nu \, d\Omega, $$

or

$$ u_\nu = \frac{4\pi}{c} J_\nu. $$


---
## Mean Intensity $J_\nu$


$$ J_\nu = \frac{1}{4\pi} \int I_\nu \, d\Omega. $$

---
## Total Radiation Density

$$ u = \int u_\nu \, d\nu = \frac{4\pi}{c} \int J_\nu \, d\nu. $$

- Unit: $\mathrm{erg \ cm}^{-3}$ 

---
## Radiation Pressure 


### Radiation Pressure in an Enclosure Containing an Isotropic Radiation Field


In a reflecting enclosure containing an isotropic radiation field, each photon transfers "twice" its normal component of momentum on reflection.

$$ p_\nu = \frac{2}{c} \int I_\nu \, \cos^2 \, \theta \, d\Omega $$ 
Integrating over $2\pi$ steradians, and by isotropy, $I_\nu = J_\nu$,


$$ p = \frac{2}{c} \int J_\nu \, d\nu \int \cos^2 \theta \, d\Omega. $$

The angular integration yields

$$ p = \frac{1}{3}u. $$

**The radiation pressure of an isotropic radiation field is one-third the energy density.**

---
## Constancy of Specific Intensity Along Rays in Free Space


The intensity is constant along a ray:

$$ I_\nu = \mathrm{constant.} $$

$$ \frac{d I_\nu}{ds} = 0, $$

- $ds$: differential element of length along the ray.

---
### Proof of the Inverse Square Law for a Uniformly Bright Sphere


The flux from a uniformly bright sphere:


$$ F = \int I\, \cos \theta \, d\Omega = B \int^{2\pi}_0 d\phi \int^{\theta_c}_0 \sin\theta \cos \theta \, d\theta,  $$
- $\theta_c = \sin^{-1}(R/r)$: angle at which a ray from $P$ is tangent to the sphere

Then,

$$ F = \pi B(1-\cos^2\theta_c) = \pi B \sin^2\theta_c $$
or

$$ F = \pi B \left(  \frac{R}{r} \right)^2. $$

Thus, the specific intensity is constant, but the solid angle subtended by the given object decreases in such a way that the inverse square law is recovered.

If $r = R$, the flux at a surface of uniform brightness $B$ is simply $\pi B$:

$$ F = \pi B.$$


