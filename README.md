# SiPM Carrier Board

Carrier board for a 6 mm C-Series MICROFC-60035-SMT silicon photomultiplier by [onsemi](https://www.onsemi.com/pdf/datasheet/microc-series-d.pdf) designed specifically to work with the [Open Gamma Detector](https://github.com/Open-Gamma-Project/Open-Gamma-Detector).

PCB size is 18 x 18 mm. You can buy all the parts and the PCB using [Kitspace](https://kitspace.org/boards/github.com/open-gamma-project/sipm-carrier-board/).

<p align="center">
  <img alt="Front Side PCB" title="Front Side PCB" src="docs/sipm1.PNG" height="400px">
  <img alt="Back Side PCB" title="Back Side PCB" src="docs/sipm2.PNG" height="400px">
</p>

On the front side there is only the sensor itself while all the other parts are on the back. This ensures good optical contact and light-tight sealing. The unused SiPM pin number 4 is connected to the ground pad for some thermal mass.

The PCB includes the recommended SiPM [biasing](https://www.onsemi.com/pub/Collateral/AND9782-D.PDF) that is optional to use. Enable it by closing the solder jumper `JP1` and then soldering wires to the `VCC` and `GND` pin respectively. The SiPM signal will be anode `A` pad.

If you are connecting straight to the SiPM, do so via the cathode `C` and anode `A` pads and open the jumper `JP1`.
