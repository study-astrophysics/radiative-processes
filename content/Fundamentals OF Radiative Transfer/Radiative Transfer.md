
If a ray "passes through matter", energy may be added or subtracted from it by emission or absorption, and the specific intensity will not in general remain constant.

"Scattering" of photons into and out of the beam can also affect the intensity.

---
## Emission

### Spontaneous Emission Coefficient $j$

The energy emitted per unit time per unit solid angle per unit volume:

$$ dE = j \, dV \, d\Omega \, dt. $$

- $j = \mathrm{erg \ cm ^{-3} \ s^{-1} \ ster^{-1} }$  

---
#### Monochromatic Emission Coefficient $j_\nu$

$$ dE = j_\nu \, dV \, d\Omega \, dt \, d\nu. $$

- $j_\nu = \mathrm{erg \ cm ^{-3} \ s^{-1} \ ster^{-1} \ Hz^{-1} }$ 

---
### For an isotropic emission

In general, the emission coefficient depends on the direction into which emission takes place.

For an *isotropic* emitter, or for a distribution of randomly oriented emitters:

$$ j_\nu = \frac{1}{4\pi} P_\nu, $$

- $P_\nu$: radiated power per unit volume per unit frequency

---
### (Angle Integrated) Emissivity $\epsilon_\nu$

The energy emitted spontaneously per unit frequency per unit time per unit mass.

If the emission is isotropic:

$$ dE = \epsilon_\nu \, \rho \, dV \, dt \, \frac{d\Omega}{4\pi}  $$

- $[\epsilon_\nu] = \mathrm{erg \ g^{-1} \ s^{-1} \ Hz^{-1}}$: emissivity
- $\rho$: mass density of the emitting medium
- $d\Omega/4\pi$: fraction of energy radiated into $d\Omega$


---
#### Relation between $\epsilon_\nu$ and $j_\nu$ (and $I_\nu$)

For isotropic emission:

$$ j_\nu = \frac{\epsilon_\nu \, \rho}{4\pi} $$

In going a distance $ds$, a beam of cross section $dA$ travels through a volume $dV = dA \, ds$, the intensity added to the beam by spontaneous emission:

$$ dI_\nu = j_\nu \, ds.$$

---
## Absorption


### Absorption Coefficient $\alpha_\nu$

Represents the loss of intensity in a beam as it travels a distance $ds$: 

$$ dI_\nu = - \alpha_\nu \, I_\nu \, ds. $$

- $[\alpha_\nu]=\mathrm{cm}^{-1}$: absorption coefficient (positive for energy taken out of beam) 


---
### Microscopic view

- number density $n$: number per unit volume
	- cross section $\sigma_\nu=\mathrm{cm}^2$: each present an effective absorbing area
- Assumption: the absorbers are assumed to be randomly distributed


Consider a situation that a ray passes through a medium of absorbers through $dA$ within solid angle $d\Omega$. 

The number of absorbers in the element = $n \, dA \, ds$.

The total absorbing area presented by absorbers = $n \, \sigma_\nu \, dA \, ds$.

The energy absorbed out of the beam:

$$ - dI\nu \, dA \, d\Omega \, dt \, d\nu = I_\nu \, (n \,\sigma_\nu \, dA \, ds)\, d\Omega \, dt \, d\nu; $$

thus,

$$ dI\nu = - n \, \sigma_\nu \, I_\nu \, ds. $$
- $\alpha_\nu = n \, \sigma_\nu$

Often $\alpha_\nu$ is written as

$$ \alpha_\nu = \rho \, \kappa_\nu. $$
- $\rho$: mass density
- $[\kappa_\nu] = \mathrm{cm^2 \ g^{-1}}$: mass absorption coefficient, or opacity coefficient

Some conditions of validity for the microscopic picture.

1. The linear scale of the cross section must be small in comparison to the mean interparticle distance $d$.
	1. $\sigma^{1/2}_\nu \ll d \sim n^{-1/3}$ from which follows $\alpha_\nu \, d \ll 1$.
2. The absorbers are independent and randomly distributed.

These conditions are almost always met for astrophysical problems.

We consider "absorption" to include both "true absorption" and "stimulated emission," because both are proportional to the intensity of the incoming beam.
	Thus, the "net absorption" may be positive or negative."


--- 
## The Radiative Transfer Equation

Combining the effects of emission and absorption:

$$ \frac{dI\nu}{ds} = -\alpha_\nu \, I_\nu + j_\nu.$$

A formalism within which to solve for the intensity in an emitting and absorbing medium.

When scattering is present, solution of the radiative transfer equation is more difficult, because emission into $d\Omega$ depends on $I_\nu$ in solid angles $d\Omega'$, integrated over the latter (scattering from $d\Omega\$ into $d\Omega$). The transfer equation then becomes an integrodifferential equation.


---
### Emission Only: $\alpha_\nu = 0$

$$  \frac{dI\nu}{ds} = j_\nu. $$

The solution

$$ I_\nu(s) = I_\nu(s_0) + \int^s_{s_0} j_\nu(s') \, ds'. $$

The increase in brightness = The emission coefficient integrated along the line of sight.

---
### Absorption Only: $j_\nu=0$

