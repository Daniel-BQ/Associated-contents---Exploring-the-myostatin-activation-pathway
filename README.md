# Associated-contents---Exploring-the-myostatin-activation-pathway

This is the content associated with the article "Exploring the Myostatin Activation Pathway: A Promising Target for Treating Muscle Atrophy". In this material, all inputs used to simulate the systems (MD using amber24 software), calculate the properties (cpptraj package) and the trajectories used in the property calculations (last 100 ns of each simulated system) are available.

The file "MD_protocol.7z" contains all the inputs (*.in files) for the MD simulations used in the work and the protocol used for all systems (file job_MD.csh). The protocol in question was fully described in the methodology section of the paper. Among the available files are all the inputs for the explicit and implicit solvent simulation and the general protocol for both systems.

The files Promyo.7z, latent-complex.7z, TLD-p1.7z, p1-inter.7z, TLD-p2.7z, p2-inter.7z, Inactive-MSTN.7z and Active-MSTN.7z contain the topology file (.prmtop) and the parameter file (.inpcrd) of each system described in the work. In addition, the last 100 ns of simulation were made available for each duplicate for all systems that were used for analysis in the work. Regarding to the trajectories output, the water molecules were stripped with the cpptraj package.

The file "Analysis-inputs.7z" contains all the inputs (*.in files) used in the calculations, with the cpptraj package, to evaluate the properties and interactions of the proteins throughout the simulations.
