---
layout: page
---

## Simulation of butterfly flapping with the method of dipole domains

### Numerical method of dipole domains

![]({{site.baseurl}}/images/a-1.png)

Numerical scheme:

![]({{site.baseurl}}/images/a-2.png)

The dipole particles interaction:

![]({{site.baseurl}}/images/a-3.png)

### Computing cycle

1. Calculation of the dipole moments of the attached particles
   satisfying the boundary conditions `n*V = n*Vs`.
1. The calculation of the particles velocity.
1. Calculation of changes in the dipole moments as a result of particles
   interactions
1. Displacement of the particles, including particles at the trailing
   edge

### The force calculation

![]({{site.baseurl}}/images/a-5.1.png)

`I` is the hydrodynamic impulse of the fluid

![]({{site.baseurl}}/images/a-5.2.png)

### Testing of the method

The flow around the thin unmoving plate:

![]({{site.baseurl}}/images/a-6.png)

### The butterfly model

![]({{site.baseurl}}/images/a-7.png)

<iframe width="100%" height="390" src="https://www.youtube.com/embed/RZ1KLWyeErM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br/>

![]({{site.baseurl}}/images/a-8.png)

Time dependencies of the force coefficients and the angles

![]({{site.baseurl}}/images/a-9.png)

Dependence of the drag force coefficient on the phase shift

![]({{site.baseurl}}/images/a-10.png)

Dependencies of the average values `Cx`, `Cy` on the attack angle and
the opening angle

![]({{site.baseurl}}/images/a-11.png)

### Scheme of the forces and accelerations directions in different oscillation phase

![]({{site.baseurl}}/images/a-12.png)

### Conclusion

* The mesh-free dipole particles-based methods is developed and applied
  for simulation of the insect flapping wings.
* It is shown that the main cause of the thrust performance is
  interaction of wings with an added mass of fluid at the wings
  acceleration.

### The wake behind the plate performing angular oscillations

![]({{site.baseurl}}/images/a-14.png)

### Acknowlegment

The work was supported by the Russian Science Foundation
(grant No. 18-71-00133).
