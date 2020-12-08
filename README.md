<h1>Output Files from Reactive Transport Models in Benjakul et al. (2020)</h2>

This repository includes the output files (in Tecplot format) of the numerical models in the paper entitled "<b><i>Understanding controls on hydrothermal dolomitisation: insights from 3D Reactive Transport Modelling of geothermal convection</i></b>".

https://doi.org/10.5194/se-2020-99

We used <b>TOUGHREACT</b>, a numerical simulation program developed by the Lawrence Berkeley National Laboratory (LBNL) which is available at: https://tough.lbl.gov/licensing-download/toughreact-licensing-download/ to numerically model the convection of seawater in a single fault within carbonate-hosted system. The parameters used in the numerical models are given in the paper.
 <font size="-2">
|Simulation |	Folder |       Model description	      | Figure |	Flow data<sup>A</sup> |	Flow vector<sup>B</sup> |	Mineral<sup>C</sup> |	Aqconc<sup>D</sup> |	SI<sup>E</sup> |
|:---------:|--------|--------------------------------|:------:|------------------------|-------------------------|---------------------|----------|-----|
| 1 |	2D_Fault_perpendicular |	Fault-perpendicular 2D model |	2 |	Benjakuletal2020_M1_flow |	Benjakuletal2020_M1_vector |	Benjakuletal2020_M1_mineral	| Benjakuletal2020_M1_aqconc |	Benjakuletal2020_M1_SI |
|2|	2D_Fault_parallel|	Fault-parallel 2D model	|2|	Benjakuletal2020_M2_flow	|Benjakuletal2020_M2_vector	|Benjakuletal2020_M2_mineral|	Benjakuletal2020_M2_aqconc	|Benjakuletal2020_M2_SI|
|3|	3D_Baseline|	3D baseline model|	3	|Benjakuletal2020_M3_flow	|Benjakuletal2020_M3_vector|	Benjakuletal2020_M3_mineral|	Benjakuletal2020_M3_aqconc	|Benjakuletal2020_M3_SI|
|4|	3D_Baseline-nopkfb|	3D baseline model with no poro-perm feedback	|7a|	Benjakuletal2020_M4_flow	|Benjakuletal2020_M4_vector|	Benjakuletal2020_M4_mineral	|Benjakuletal2020_M4_aqconc	|Benjakuletal2020_M4_SI
|5|	3D_50%k_base|	50 % lower-permeability basement	|8b|	Benjakuletal2020_M5_flow|	Benjakuletal2020_M5_vector	|Benjakuletal2020_M5_mineral	|Benjakuletal2020_M5_aqconc|	Benjakuletal2020_M5_SI
|6|	3D_10%k_base	|90 % lower-permeability basement	|8c|	Benjakuletal2020_M6_flow	|Benjakuletal2020_M6_vector	|Benjakuletal2020_M6_mineral	|Benjakuletal2020_M6_aqconc	|Benjakuletal2020_M6_SI
|7|	3D_200C_base	|lower basement temperature	|8d|	Benjakuletal2020_M7_flow	|Benjakuletal2020_M7_vector	|Benjakuletal2020_M7_mineral	|Benjakuletal2020_M7_aqconc	|Benjakuletal2020_M7_SI|
|8|	3D_50%k_cap	|50% lower-permeability caprock	|10b	|Benjakuletal2020_M8_flow|	Benjakuletal2020_M8_vector|	Benjakuletal2020_M8_mineral	|Benjakuletal2020_M8_aqconc	|Benjakuletal2020_M8_SI|
|9|	3D-10%k_cap	|90% lower-permeability caprock|	10c|	Benjakuletal2020_M9_flow	|Benjakuletal2020_M9_vector	|Benjakuletal2020_M9_mineral	|Benjakuletal2020_M9_aqconc	|Benjakuletal2020_M9_SI|
</font>
The output files from TOUGHREACT (in Tecplot format) are visualized using <b>trexplot</b>, a python script developed under Hamish Robertson’s initiative which can be found at: https://github.com/hammytheham/trexplot (last access: 5 December 2020).

Please contact me via the following e-mail addresses in case you have any questions:
rb17526@bristol.ac.uk or rbenjaku@gmail.com

[![DOI](https://zenodo.org/badge/318801734.svg)](https://zenodo.org/badge/latestdoi/318801734)
