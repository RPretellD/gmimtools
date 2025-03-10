# gmimtools: A suite of Ground Motion Intensity Measure (GMIM) tools

This repository provides a suite of ground motion intensity measure tools. These tools include codes for computing the following ground motion intensity measures based on ground motion records: 

| Function        | Abbreviation | Description                                     |
|-----------------|--------------|-------------------------------------------------| 
| get_PGA_cy      | PGA          | Peak ground acceleration                        |
| get_PGV_cy      | PGV          | Peak ground velocity                            |
| get_Ia_cy       | Ia           | Arias intensity                                 |
| get_Ia_times_cy | Ia_times     | Times to get to a Ia percentage                 |
| get_CAV_cy      | CAV          | Cumulative absolute velocity                    |             
| get_CAVn_cy     | CAVn         | CAV on accelerations after applying a cutoff    |
| get_CAVstd_cy   | CAVstd       | Standardized CAV                                |
| get_CAVdp_cy    | CAVdp        | Damage-potential CAV                            |


## Example
A detailed example on Jupyter Notebooks is presented [here](https://github.com/RPretellD/gmimtools/blob/main/Examples/Example_1_Get_GMIMs.ipynb).


## Relevant references
- Arias A (1970) A measure of earthquake intensity, in Seismic Design for Nuclear Power Plants (Hansen R. J., ed.), The MIT Press, Cambridge, MA. 
- Campbell KW and Bozorgnia Y (2011) Prediction equations for the standardized version of cumulative absolute velocity as adapted for use in the shutdown of U.S. nuclear power plants. Nuclear Engineering and Design 241(2011): 2558–2569.
- EPRI (1988) A criterion for determining exceedance of the operating basis earthquake. EPRI NP-5930, Palo Alto, CA. 
- Kramer SL and Mitchell RA (2006) Ground motion intensity measures for liquefaction hazard evaluation. Earthquake Spectra 22(2): 413–438. 


## Citation
If you use these codes, please cite:<br>
Pretell, R. (2025). gmimtools: A suite of ground motion intensity measure tools (0.2.0). Zenodo. https://doi.org/10.5281/zenodo.10099774 <br>

[![DOI](https://zenodo.org/badge/716446151.svg)](https://doi.org/10.5281/zenodo.10099773)

## Contact
For any questions or comments, contact Renmin Pretell at rpretell@unr.edu.