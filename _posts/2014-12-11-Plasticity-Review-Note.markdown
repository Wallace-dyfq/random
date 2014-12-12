---
layout: post
title:  "Plastic Review Note"
date:   2014-12-11 09:10:50
categories: jekyll update
---

# Plasticity: assumptions
- plastic flow occurs at constant volume
- plasticity associated with dislocation motion
- one block of material slips over another
- true for fully dense solid
- not true for cellular materials
- material is isotropic

# Yield criteria
- Various theories developed:
   + Rankine (1857): Maximum stress criterion, yield when maximum principle stress equals to yield strength
   + Tresca (1864, 1867): Maximum shear stress criterion, yield when maximum shear stress in component equals to maximum shear stress in uniaxial test at yield
   + von Mises (1913): Maximum distortional energy criterion, yield when equivalent stress equals yield stress in a uniaxial test

# Dislocations

## Geometric aspects: 
- dislocation is a line defect in the stacking of atoms in crystal lattice
- most dislocations are mixed, part edge, part screw
- Burgur's vector of dislocation cannot change
- dislocation line cannot terminate within a crystal
- dislocation line can only terminate at a surface of a surface, e.g., free surface or grain boundary
- dislocation can form closed loops
				  

## Edge dislocation
- extra half plane of atoms in one part of crystal structure
- Burger's vector perpendicular to the vector parallel to dislocation line

## Screw dislocation
- two blocks of material sheared across partial cut through material
- Burger's vector parallel to the vector parallel to dislocation line

## Dislocation motion

### Glide
- dislocation moves in the surface that contains both its line and Burger's vector
- results in slip - sliding of one plane of atoms over another on slip planes
- under shear stress, bonds sequentially break  reform so that dislocation moves through the lattice until it leaves at the surface
- net result is slip step of one atomic distance
- slip planes - most densely packed planes
- slip direction - direction in the slip plane in which atoms are most closely ?????

### Climb
- dislocation moves out of glide surface
- requires diffusion - thermally activated process
- discuss in section on high temp creep in metal + ceremics

### Kinks + Jogs
- if a section of dislocation glides as the slip plane, it acquires kinks
- if a section of dislocation climbs out of the slip plane onto another, parallel split plane, it acquire jogs

# Stress field around a dislocation
- dislocation produce stress field around them, e.g., bottom in
  tension, top in compression
- calculate elastic properties of dislocation
- based on continuum elasticity
- provides explanation of macroscopic plasticity
- screw dislocation has a simple elastic stress field
- stress arises from dislocation of atoms
- stress in absences of external load: "self-stress" of dislocation
- edge dislocation - more complex stress state, but all non-zero component
# Dislocation theory
- elastic stress field around a dislocation
- strain energy of a dislocation
- line tension
- glide force

## Elastic strain energy of a dislocation
- stress field around a dislocation produces strain energy
- screw dislocation: $\sigma_{\theta z} = \frac{Gb}{2\pi r}$
- strain energy /vol = $\frac{1}{2}\sigma_{\theta z} \epsilon_{\theta
z}$
- consider a cylinder of material and find the elastic strain energy
of dislocation (screw)


## Strain energy of a dislocation
- edge dislocation


## Line tension
- line tension is the change in strain energy when the dislocation is
extended by a unit length
- equal to the energy/length
- analogous to surface tension in a fluid

## Glide force f on a dislocation
- force exerted on a dislocation, normal to the dislocation line, when
a stress is applied.
- defined per unit length of dislocation line
- calculate by equating external + internal work done when dislocation
moves completely through a crystal


# Lattice resistance
- stress required to move a dislocation through an otherwise perfect
  crystal
- covalently bonded solids: \sigma_y ~ 10^{-2} to 10^{-1} E
(intrinsically hard)
- ionic material
- metals - need to be strengthened - introduce obstacles to dislocation
motion
  + solid solution hardening
  + precipitation hardening
  + dispersion hardening
  
## Solid solution hardening
- individual solute atoms dissolved in primary metal
- elastic interaction between solute + primary metal
   > geometric misfit
   > modulus misfit
- shear stress required to move dislocation
- interaction energy between dislocation + solute is u_s

## Precipitation hardening
- examples: dural-hard Al, mild steel, nimonics
- precipitates are weak obstacles to dislocation motion
- dislocations can cut through their lattice
- work done in doing so raise $\sigma_y$


## Dispersion hardening
- dispersion - compound introduced into a crystal
- typically choose ceramics that are hard + strong
- dislocations cannot cut through dispersion
- dislocation bow out between dispersion particles (pinned)


## Grain boundary strengthening
- empirical relationship: Hall-Petor
- small grains - stronger
- arises from interaction of grain boundary + dislocation; not well
understood


## Strengthening: summary
- yield strength is lattice resistance + sum of all strengthening
  mechanism in alloy
