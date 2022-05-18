	This model is published in

	E.E. Saftenku "Modeling of slow glutamate diffusion and AMPA
	receptor activation in the cerebellar glomerulus", J. Theor.
	Biol, 2005, vol. 234, N 3,P. 363-382 (PMID 15784271).

     Synaptic conductances are influenced markedly by the geometry
     of the space surrounding the synapse since the transient
     glutamate concentration in the synaptic cleft is determined by
     this geometry. In our paper we attempted to understand the
     reasons for slow glutamate diffusion in the cerebellar
     glomerulus, a structure situated around the enlarged mossy fiber
     terminal in the cerebellum and surrounded by a glial sheath.
     For this purpose, analytical expressions for glutamate diffusion
     in the glomerulus were considered in the models with two-(2D),
     three- (3D), and fractional two-three dimensional (2D-3D)
     geometry with an absorbing boundary. The time course of average
     glutamate concentration in the synaptic cleft of the mossy
     fiber-granule cell connection was calculated for both direct
     release of glutamate from the synaptic unit, and for cumulative
     spillover of glutamate from neighboring release sites. Several
     kinetic schemes were examined, and the parameters of the
     diffusion models were estimated by identifying theoretical
     activation of AMPA receptors with direct release and spillover
     components of published experimental AMPA receptor-mediated
     EPSCs (DiGregorio, Nusser, Silver, 2002). We assumed that
     anomalous diffusion of glutamate occurs in the glomerulus. Our
     assumption was confirmed by a good fit and match of experimental
     estimations and theoretical parameters, obtained in the
     simulations that use an approximation of anomalous diffusion by
     a solution for fractional Brownian motion.

Keywords: Glutamate diffusion, Cerebellar granule cells, Spillover.

Simulations.
    Begin from mosinit.hoc.
    Clicking on buttons, you can choose the models with absorbing
    boundary, closed boundary or without boundary. For each model you
    can choose the simulation of glutamate diffusion in the
    environment with 2D, 3D or 2D-3D geometry and compute direct
    release and spillover components of AMPAR activation as in our
    Fig. 7. Only simple 3-state kinetic schemes of AMPARs with rate
    constants extracted from receptor kinetics during exposure of
    definite glutamate concentrations to outside-out patches from
    cultured granule cells are used in our examples. Clicking on
    button "Fractional Brownian motion" you can simulate anomalous
    glutamate diffusion in the model with absorbing boundary
    (Fig. 12a,b). Clicking on "Direct summation of glutamate", you
    can reproduce four possible combinations of direct release and
    spillover AMPAR-mediated EPSCs (Fig. 10). These EPSCs are evoked
    by two consecutive stimuli with time interval 10 ms and can be
    observed under assumption of 2 vesicles in the ready-release pool
    and the hypothesis of one vesicle release per AP. The density of
    active release sites is calculated in accordance with changes of
    release probability at each AP. If there is only one vesicle in
    the pool, then Markram and Tsodyks model for determination of
    release probability can be used. The use of the calculated
    release probability in the expression for ionic current will give
    incorrect result as such a kind of modeling assumes that AMPARs
    are desensitized to such an extent for the second AP as if all
    release sites had released vesicles on the first AP.  In reality
    not more than P1*100% synaptic units can be desensitized by a
    direct release of glutamate, but synaptic units are desensitized
    to a lesser extent by spillover glutamate. All parameters of the
    model can be changed in the respective boxes.

Update
------

Mod files compatibility fixes for upcoming NEURON 9.0, 8.2 and 8.1
