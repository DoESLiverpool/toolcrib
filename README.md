# Toolcrib

Tools are expensive and easy to lose track of.  Please number then and record their history as they get used here.  

Record who bought them, for how much, where from, catalogue number and any feeds and speeds information provided by the supplier.  We want to make sure that when we find a tool we like, we can get it again.  

You must use the correct collet size and tighten it firmly.  Do not use the 3.125mm collet for 3mm tools or you will need to get it out with a hammer and chisel.

* RPM[rev/min] = Vc[m/min] * 1000/60/(3.14 * tooldia) * 60
* Feedrate = RPM * fz * numflutes

### T1  4mm Flat
Diameter 4mm (flat), Collet 8mm, 1 flute, HSS-E, 
Cutwel: EL612040
Aluminium:  RPM 18000rev/min, Feed 950mm/min, Vc 226 m/min, fz=0.053 mm/tooth
Bought by @goatchurchprime 11 December 2018 for £13
* 2018-12-28  1 hour cutting swan necks full width at 0.2mm stepdown.  Stock came loose on second part and vibrated, heating up everything and melting slivers of aluminium onto the tool, which were picked off.
* 2018-12-31  Tried with 0.4mm stepdown.  Terrible noise after 5mm depth, tore everything apart, and finally snapped.

### T7  5mm Flat
Diameter 5mm (flat), Collet 6mm, 2 flutes, Alu Power, 
Cutwel: E5522050
Bought by @goatchurchprime 11 December 2018 for £13.
Aluminium:  RPM 10000rev/min, Feed 1000mm/min, Vc 155 m/min, fz=0.050 mm/tooth  (up to 2.5mm deep cutting)
* 2018-12-31 4 hours cutting at 0.2mm stepdown on full width cuts.  Feed reduced to 560mm/min due to noise before it broke.  Is capable of G83 drill cycle pecking of 5mm dia hole.  There is some wear at the flat tip in the form of shallow notches on the two blades.

### T2
Diameter 3mm (flat), Collet 6mm, 3 flutes, Alu Power
Bought by @mike in 2018

### T8
Diameter 6 (flat), Collet 6mm, 4 flutes, HSS
Chinese writing

### T9
Diameter 3 (flat), Collet 3mm, 1 flute, Alu Power
Bought by @mike in 2018

### T10
Holz Alu/Kunsstoff 1mm tools, original with Kinetic-NC machine

### T11
Brass coloured rasps 1/8" collet

### T12
Full set of 10: 0.8-3mm PCB engraving bits, 1/8" collet

### T13
HSS 6mm diameter, long, 4 fluke, 6mm collet
4 remaining, one damaged on shaft.  


## Feeds and speeds
 [my calculations here](https://github.com/goatchurchprime/transition-CAM/blob/master/feedsandspeeds.ipynb) a 2-fluke 5mm Carbide tool should cut aluminium at 1577mm/minute with the spindle set at 15524rpm, and a 3mm 1-fluke Carbide tool should cut it at 1314mm.minute with spindle 25874. 
