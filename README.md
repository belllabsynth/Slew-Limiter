# Slew Limiter

This is a simple eurorack slew limiter, with a very low parts count that is quick and easy to build. There are no extra frills, just a pot for slew amount, a toggle switch to select between slewing up, down, or both, one input, and one output. 

I drew the schematic from a stripboard layout done by user Mcshafty on the Look Mum No Computer discourse forums ([link here](https://lookmumnocomputer.discourse.group/t/slew-generator-stripboard-confirmed-working/1865)), which is based off of schematics from [Dintree](https://dintree.com) and [YuSynth](https://yusynth.com).

*General Notes:* 

* Current revision (v1.2) of board is untested as of yet, though past versions have worked as expected. I will update and remove this text when I get my new boards in.
* The included Gerber files have been generated for JLCPCB and have not been tested with manufacturers. I have included silkscreen text on the back of both the main board and the panel to avoid JLC printing the batch number on the front. Remove the text saying "JLCJLCJLCJLC" if printing elsewhere and you care to have that removed.
* JLCPCB does not detect the pcb size for the front panel. You can enter it as 128x20mm.
* Depending on your rack, the v1.0 and v1.1 boards may have been too long and not clear your rails. There are no traces below the output jacks ground leg and you can carefully cut a little bit off the board below there if needed. This have been fixed in v1.2.

*Changes In v1.2:*

* Change C4 and C5 from polarized 10uf capacitors to one (now C3) bipolar 4.7uf capacitor
* Resize main board PCB to 100mm height to fix potential clearance issue and reduce manufacturing cost
* Re-design board to make the build a little bit easier
* Change power header footprint to a shrouded header, taken from the [Winterbloom GitHub](https://github.com/wntrblm)
* Increase silkscreen text size and edgecut line thickness to avoid possible issues at certain PCB houses
* Add "JLCJLCJLCJLC" text to main board PCB and front panel so JLC doesn't put their batch number on the front
* Misc schematic changes to improve readability
