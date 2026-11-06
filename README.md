# 03-computational-modeling-of-buoyancy-driven-flow
# Computational Modelling of Buoyancy Driven Flow

**Daisy Wang | University of Cambridge | May 2012**

## Summary

Developed a coupled mathematical and numerical model of buoyancy-driven recirculating flow in a blocked valley, investigating the interaction between core flow, viscous boundary layers and heat transport.

**Key Contributions**
- Derived and coupled governing momentum and heat transport equations for core flow and boundary layer.
- Developed an alternative power law solution to address limitations in conventional exponential boundary layer assumptions.
- Implemented numerical solutions in MATLAB using fourth order Runge-Kutta integration, shooting methods, and iterative techniques for nonlinear differential equations.
- Computed velocity and temperature fields throughout the geometry and investigated the influence of slope angle on flow behaviour.

**Technical Methods:** Fluid Mechanics · Heat Transfer · Boundary Layer Theory · Governing Equation Derivation · Numerical Modelling · MATLAB · Runge-Kutta Integration · Shooting Methods  · Nonlinear Differential Equations

## Engineering Problem

Buoyancy-driven flow in a confined geometry involves coupled momentum and thermal boundary layers. While established models describe flow in open ended valleys, this research investigated the more complex case of a blocked valley, where the flow must recirculate within the domain.

The objective was to develop a self consistent model linking the core flow to the boundary layer and examine how the resulting velocity and temperature distributions evolve throughout the valley.

## Methodology

1. **Analytical solution:** Developed near origin boundary conditions and a power law formulation to obtain a self consistent solution.
2. **Numerical solution:** Used MATLAB shooting methods and fourth order Runge-Kutta integration to solve the coupled nonlinear differential equations.
3. **Parametric study:** Varied geometric slope angle to assess changes in velocity, temperature and flow development.

## Key Findings

- Predicted velocity and temperature fields across the full geometric domain.
- Identified peak flow velocities within the boundary layer and identified the transition from entrainment to detrainment along the valley.
- Found that steeper slopes produce a larger isothermal region and delay wall jet detrainment.

## Model Limitations and Further Work

The laminar model proved inadequate for the predicted flow regime. Turbulent viscosity and thermal diffusivity were introduced, although some turbulence effects remained unmodelled.  Experimental validation and improved turbulence modelling were identified as important next steps.

## Engineering Relevance

This research demonstrates the application of first principles fluid mechanics, heat transfer, mathematical modelling and numerical methods to a coupled transport problem. These techniques are relevant to engineering analysis involving fluid flow, thermal behaviour and the interpretation of complex physical systems.
