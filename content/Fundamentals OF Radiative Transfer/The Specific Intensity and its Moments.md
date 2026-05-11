
## Definition of Specific Intensity or Brightness


The flux is a measure of the energy carries by all rays passing through a given area.

Construct an area $dA$ normal to the direction of the given ray and consider all rays passing through $dA$ whose direction is within a solid angle $\Omega$ of the given ray. 

The energy crossing $dA$ in time $dt$ and in frequency range $d\nu$:

$$ dE = I_\nu \ dA \ dt \ d\Omega \ d\nu,$$
where
- $I_\nu$: specific intensity (or brightness)
	- Depends on location in space, on direction, and on frequency


### Dimensional Analysis of $I_\nu$

$$ \begin{split} I_\nu (\nu,\Omega) & =\rm{\ (energy) \ (time)^{-1} \ (area)^{-1} \ (solid \ angle)^{-1} \ (frequency)^{-1}} \\
& = \rm{\ erg \ s^{-1} \ cm^{-2} \ ster^{-1} \ Hz^{-1}} \end{split}.$$



## Net Flux


Now, we have a radiation field. 

Construct a small element of area $dA$ at some arbitrary orientation $\bf{n}$.

The differential amount of flux from the solid angle $\Omega$ reduced by the lowered effective area $\cos \theta \ dA$:

$$ dF_\nu(\rm{erg \ s^{-1} \ cm^{-2} \ Hz^{-1}}) = I_\nu \ \cos\theta \ d\Omega. $$


The net flux in the direction $\bf{n}$, $F_\nu(\bf{n})$ is obtained by integrating $dF$ over all solid angles:

$$ F_\nu = \int I_\nu \cos\theta \ d\Omega.$$

Note, if $I_\nu$ is an isotropic radiation field, then the net flux is zero, since $\int \cos\theta \ d\Omega = 0$.


## Momentum Flux

