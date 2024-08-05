# EKV2.6 MOSFET Compact Model 
FOSS EKV2.6 Compact Model 

The EKV2.6 MOSFET compact model has had a considerable impact on the academic and industrial community of analog integrated circuit design, since its inception in 1996. The model is available as a free open-source software (FOSS) tool coded in Verilog-A. The present depository provides a short review of foundations of the model and shows its capabilities via characterization and modeling based on a test chip in 180 nm CMOS fabricated via Europractice.

This repository was forked from [EKV 2.6 rev.15](https://github.com/ekv26/model). Some modifications on [ekv26.va](https://github.com/hung-chi/ekv2.6/ekv26.va) were made correspondingly for ngspice. The npspice-compatible va code can be found in [VA_Models](https://github.com/dwarning/VA-Models/blob/main/code/ekv/vacode/ekv26.va). 

## Examples of ngspice
The simulation examples of using ngspice can be found in [docs/notebooks](.docs/notebooks). The notebook [ekv26_nmos_dc](https://github.com/hung-chi/ekv2.6/docs/notebooks/ekv26_nmos_dc.ipynb) gives a tutorial, covering the installation of ngspice and openVAF and a simple transistor simulation.


## License 

Licensed under the Educational Community License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://opensource.org/licenses/ECL-2.0
