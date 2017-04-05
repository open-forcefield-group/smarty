# Examples for Bayesian atomtype sampler

## Manifest
* `parm@frosst/` - example illustrating attempt to recover parm@frosst atom types
* `smarty_simulations/` - examples to implement smarty, a tool to rediscover parm@frosst atomtypes on the AlkEthOH molecules set 
* `SMIRNOFF_comparison/` - temporary example (waiting for permanent home) of cross-comparison of molecule energies from SMIRNOFF with same molecule energies from .prmtop and .crd.
* `SMIRNOFF_simulation/` - gives a simple example of simulating a molecule in the gas phase beginning from a molecular structure and the SMIRNOFF forcefield format.
* `forcefield_modification/` - gives example of modifying a forcefield parameter, evaluating how it changes an energy (IPython notebook).
* `chemicalEnvironments/` - contains an example and documentation of using chemical environment objects to manipulate environment being considered, generate example SMIRKS, etc. Also contains IPython notebook using the chemical environment for depiction.
* `partial_bondorder/` - example of using partial bond orders for parameterizing molecules, and showing how the SMIRFF format extends. (See issue #53 on Smarty).
* `smirky_simulations/` - example usage of the smirky sampling tool to rediscover the SMIRNOFF99Frosst parameter types
