# Combind projects: Energimåling, autoStart og ProgrammablePulsGenerator

The purpose of this project is to assemble PCB manufacturing at the same PDB for the three projects.

Only information and data explicit required for this process will be collected here.

Informatino and data related the the individual projects will be found in their onwn projects. E.g. There will be not software / firmware in this project.

Project Version history:
 * V0.0.1 - Initial commit. Project structure, submodule and Page settings.
 * V0.0.2 - Local KiCad Libraries added
 * V1.0.0 - Schematics and components placed on BCB for Energimåling added to the project.
 * V2.0.0 - Schematics and components placed on BCB for autoStart added to the project.
 * V.0.0 - Schematics and components placed on BCB for ProgrameablePulseGenerator added to the project.<br>
For this version (3.0.0) all KiCad Local libraries in the submodule were updated:<br>
All [JLCPCB](https://jlcpcb.com/) extended components and all non [JLCPCB](https://jlcpcb.com/) components were update wit the option "Exclude from BO M list.<br>
Further som footprints were modified and fixed for errors.<br>
Several components is all schmatics were replaced with the new modified ones.
 * V3.0.1 - Feature update - Adding critical traces by hand and prepare for autorouter to do the rest.
 * V3.1.0 - Feature update - From V3.0.0: Aoto routed and ctitical tracks modified afterwards.
 * V3.1.1 - Feature update - GND zone filled for Energimåling
 * V3.1.2 - Feature update - GND zone filled for Arduino USB-Serial card.
 * V3.1.3 - Feature update - GND zone filled for autostart og ProgrammablePulsGenerator.
 * V4.0.0 - Final project files including Gerbers and BOM list.<br>Due to the BOM Generation script for creating BOM lists for JLCPCB, has trouble with spaces in the path on Windows, The project has been moved to a full path without spaces.<br>
 To reduce issues with github versioning, the project will from Version 4.0.0. be located as sbv1307/combined-II.<br>
  * V4.0.4 - Version 4.0.1 Documentation update.
 



 