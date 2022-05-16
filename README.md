# SiPM Carrier Board

Carrier board for a 6mm C-Series MICROFC-60035-SMT silicon photomultiplier by [onsemi](https://www.onsemi.com/pdf/datasheet/microc-series-d.pdf).

PCB size is 18 x 18 mm.

<p align="center">
  <img alt="Front Side PCB" title="Front Side PCB" src="docs/sipm1.PNG" style="width:49%">
  <img alt="Back Side PCB" title="Back Side PCB" src="docs/sipm2.PNG" style="width:49%">
</p>

The PCB includes the recommended SiPM [biasing](https://www.onsemi.com/pub/Collateral/AND9782-D.PDF) and an (optional) 2x3 pin header. On the front side there is only the sensor itself while all the other parts are on the back. This ensures good optical contact and light-tight sealing. Both sides have ground planes and the SiPM pin number 4 is connected to them for some thermal mass.

You can solder the SMT pin header to plug it directly into the [OpenGamma Detector](https://github.com/Open-Gamma-Project/Open-Gamma-Detector) or leave it and use wires according to the pin assignment.
