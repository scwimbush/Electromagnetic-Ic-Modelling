# Electromagnetic *I*<sub>c</sub> Modelling
This utility takes the output of a [FEMM](https://femm.info) electromagnetic model and analyses it on the basis of a [SuperCurrent](https://figshare.com/collections/A_high_temperature_superconducting_HTS_wire_critical_current_database/2861821) critical current (*I*<sub>c</sub>) dataset to produce a map of the local *I*<sub>c</sub> of the conductor under the particular magnetic field conditions at each point in the model, or the fraction of the conductor *I*<sub>c</sub> constituted by the required operating current.

The Windows utility requires the prior installation of the 64-bit [LabVIEW 2020 Runtime Engine](https://www.ni.com/en-nz/support/downloads/software-products/download.labview-runtime.html#352879) in order to run.

An example input file and *I*<sub>c</sub> dataset is included that should run straight out of the box.
