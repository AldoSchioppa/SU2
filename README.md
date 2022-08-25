# SU2 | PERFORMANCE ASSESSMENT IN AERODYNAMIC SHAPES OPTIMISATION THROUGH ADJOINT METHOD 

Continuous adjoint cases, comprising 2D/3D steady transonic and viscid optimisations. The project's scope is to walk the user toward utilizing the design optimiser (driven by the Python code being provided) and through the hiccups and difficulties they might encounter when employing SU2. The folder contains the following directories:

**MESH_Gmsh**: comprising the whole set of geometries being used as test cases for adjoint assessment evaluation. The files' ease and simple implementation permit the user to profusely generalise the mesh structure to any geometry and any grid, albeit numerous amount of cases has been implemented: structured quadrilateral grid, unstructured triangular grid for viscous (prism layers) and inviscid flows, with (unsteady) and without (steady) downstream wake refinement.

**NOTEWORTHY_CFG_FILES**: including the general configuration file (available on SU2's site) and Unsteady_Compressible_Incompressible_OPT.cfg which consists in the most general .cfg file being tailored for aerodynamic regimes of interest, as well as the unsteady solver. The latter might also be executed as CFD solver configuration file for direct solutions only.

**SCRIPT**: including a simple MATLAB script whose purpose is to plot the .csv file outcomes originating, by default, from SU2.

**JUPYTER_NOTEBOOKS**: compilation of all the cases being studied, drawn up in Jupyter Notebooks format, where the user can go through all the parameters of remarkable importance for setting adjoints (or direct) simulation.

**Adjoint_SIM**: containing 4 sub-folders concerning the cases being launched. Because of memory matter, the results are not presented. The sub-folders include: configuration file, mesh, any python script to execute, a TXT_FILES folder storing the .txt files to be coupled with the Jupyter Notebooks.


