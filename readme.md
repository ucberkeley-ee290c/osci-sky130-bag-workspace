# osci130-sky130-bag-workspace

Analog design of the UC Berkeley "OsciBear" SoC in SkyWater 130nm

---

*Embarassing: GitHub doesnt like this repository in its current state.*

If you are affiliated with UC Berkeley's BWRC, you can find the source material in its primary home [here](https://bwrcrepo.eecs.berkeley.edu/swtech130/osci-sky130-bag-workspace). 
Otherwise in the meantime, check out the chip's other content in these related repositories:

* [osci-sky130](https://github.com/ucberkeley-ee290c/osci-sky130) is the top-level meta-repo, including chip-level documentation
* [chipyard](./chipyard) contains the Chisel source and VLSI back-end configuration for the digital half of the SoC. (And is also a fork of https://github.com/ucb-bar/chipyard.)
* [bag-workspace](./bag-workspace) (**you are here**) contains the BAG generator code for the Python-generated analog portions of the SoC, plus the OpenAccess views of all other custom-designed portions, including the top integration levels. This is a fork of the starter [Berkeley Wireless Research Center Sky130 BAG Workspace](https://bwrcrepo.eecs.berkeley.edu/swtech130/bag3_skywater130_workspace), which includes both Sky130-tech-specific and BWRC-site-specific setup.
* [caravel_user_project_analog](./caravel_user_project_analog) is a fork of eFabless's [Caravel (Analog) User-Project Starter](https://github.com/efabless/caravel_user_project_analog). It serves as a delivery area, meeting eFabless's expectations for directory and file layout. Note many of its sub-directories targeted for specific tools (magic, xschem, etc) are left empty or unmodified from the template version.

