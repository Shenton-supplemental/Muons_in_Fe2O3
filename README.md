# Supplemental material for _Local Electronic Structure and Dynamics of Muon-Polaron Complexes in Fe<sub>2</sub>O<sub>3</sub>_

M. H. Dehn,<sup>1,2,3</sup> J. K. Shenton,<sup>4,*</sup>  D. J. Arseneau,<sup>^3</sup> W. A. MacFarlane,<sup>2,3,5</sup> G.
D. Morris,<sup>3</sup> A. Maigné,<sup>2</sup> N. A. Spaldin<sup>4</sup> and R. F. Kiefl<sup>1,2,3</sup>


<sup>1</sup>Department of Physics and Astronomy, University of British Columbia, Vancouver, BC V6T 1Z1, Canada    
<sup>2</sup>Stewart Blusson Quantum Matter Institute, University of British Columbia, Vancouver, BC V6T 1Z4, Canada    
<sup>3</sup><span style="font-variant:small-caps;">Triumf</span>, Vancouver, BC V6T 2A3, Canada   
<sup>4</sup>Department of Materials, ETH Zurich, CH-8093 Zürich, Switzerland   
<sup>5</sup>Department of Chemistry, University of British Columbia, Vancouver, BC, V6T 1Z1, Canada    
<sup>*</sup> For queries about the supplemental material in this repository contact [J. Kane Shenton](mailto:john.shenton@mat.ethz.ch).

---
In these notebooks we provide supplemental material for our work on understanding the behaviour of muon-polaron complexes in Fe<sub>2</sub>O<sub>3</sub>.

  We provide <span style="font-variant:small-caps;">vasp</span> input and output files for each of the candidate muon stopping sites and states identified in the paper (also labelled as in the paper). We summarise the muon stopping sites and provide the code for analysing hyperfine tensors in the jupyter notebook: `Muon-site-summary.ipynb`

  We further provide `vasprun.xml` files for some of the tests of convergence with respect to plane-wave cutoff energy and k-point sampling density. These tests are summarised in the jupyter notebook: `Convergence_tests-ENCUT-KPOINTS.ipynb`.

  In the notebook: `Separating_the_muon-polaron_complex.ipynb`, we analyse the separation of muon from the polaron in different configurations. Here again we provide the <span style="font-variant:small-caps;">vasp</span> input and output files as well as the code used to analyse these results.

  Finally, in `muons_wrt_U.ipynb` we investigate the effects of the choice of the Hubbard U correction on the predicted properties of the four charge-neutral muon-polaron complex states. 

These jupyter notebooks may be previewed on [github](https://github.com/Shenton-supplemental/Muons_in_Fe2O3) or via the [jupyter notebook viewer](https://nbviewer.jupyter.org/github/Shenton-supplemental/Muons_in_Fe2O3). 

Note that all of files are currently compressed to save space. These must be uncompressed before the notebooks will run. In each notebook there is a cell one can run to decompress the files needed for that particular notebook.
