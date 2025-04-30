### XLR-4 mute switch
the NA housing can be used as a project box for a simple switching circuit, in order to allow an intercom user to mute their talk signal without having to reach their remote station or belt pack.  
this project assumes the maker is comfortable drilling holes in metal, deburring, wire cutting, wire stripping, and thru-hole soldering.  

# this project has some electrical errors and will be updated soon to revise.

### suggested parts list  
| Part Designator   | Part Description/Vendor Name | Vendor Link | Qty needed |
|-------------------|------------------------------|-------------|------------|
| Enclosure         | Neutrik NA-Housing           |    [markertek](https://www.markertek.com/product/na-housing/neutrik-na-housing-extrusion-profile-set-for-combination-with-d-shape-connectors)        |       1    |
| XLR-4 panel connector with pins | NC4MD          |   [markertek](https://www.markertek.com/product/nc4md-lx-b/neutrik-nc4md-lx-b-4-pin-xlr-male-panel-chassis-mount-connector-duplex-ground-black-gold)          |      1   |
| XLR-4 panel connector with sockets  | NC4FD      |   [markertek](https://www.markertek.com/product/nc4fdl-1-bag/neutrik-nc4fd-l-bag-1-4-pin-xlr-female-panel-chassis-mount-connector-black-silver)     |      1     |
| SPST toggle switch      | NKK Switches # MN11SS1W01 |   [Mouser](https://www.mouser.com/ProductDetail/633-MN11SS1W01) |       1    |
| connecting wire between connectors, switches      |22 AWG stranded wire|  |       500mm  (includes extra)  |
|3x8 thread forming screws | screws to replace neutrik default screws| [McMaster](https://www.mcmaster.com/94209A356/)|4 (comes in pack of 100)|

### additional parts to build  
this project works best with an XLR-4 extension cable. you may not have one of these in your workplace.  
thankfully, if you can solder, or know someone who does, it is trivial to manufacture your own.

| Part Designator   | Part Description/Vendor Name | Vendor Link | Qty needed |
|-------------------|------------------------------|-------------|------------|
| Wire, 4 conductor with shield, by the foot       | Mogami W2799          |    [Performance Audio](https://www.performanceaudio.com/products/mogami-w2799-neglex-mini-quad-console-cable-by-the-foot)       |       to length, 15' suggested.    |1|
| XLR-4 connector with pins | NC4MX         |   [markertek](https://www.markertek.com/product/nc4mx/neutrik-nc4mx-4-pin-xlr-male-cable-connector)          |      1   |
| XLR-4 connector with sockets  | NC4FXX      |   [markertek](https://www.markertek.com/product/nc4fxx/neutrik-nc4fxx-4-pole-female-cable-connector)     |      1     |
| heat shrink  | for strain relief sizing     |  |      4"    |  

heat shrink is needed for the NC4MX and NC4FXX rear bushing to have enough material to grip the wire jacket of Mogami W2799.  
 [see neutrik XLR assembly information for best practices on installing neutrik connectors on unterminated wire.](https://www.neutrik.com/media/8050/download/xlr-xx-series.pdf?v=1)


### suggested tools list  

| Tool | Purpose | Relevant McMaster-Carr Link |
| ------------- | ------------- |------------- |
| Drill | enclosure machining - drilling hole | |
| Drill bit  | enclosure machining - drilling hole | [6.2mm drill bit @ McMaster](https://www.mcmaster.com/28255A116/)|
| Metal deburring tool | enclosure machining - clearing drilled hole| |
| Phillips-head #1 bit for drill | enclosure assembly - attaching connectors to enclosure|
| Needle nose pliers| enclosure assembly - toggle switch attachment| 
| Bench vise with soft jaws| enclosure assembly - final installation of screw hardware| 
| Soldering iron | electrical connections between switches and sockets, along with 22 AWG stranded wire|
| Calipers | measuring and placing hole location on enclosure|
| Soldering iron | electrical connections between switches and sockets, along with 22 AWG stranded wire|
| Solder| electrical connections between switches and sockets, along with 22 AWG stranded wire|


### process  
tap a hole in the enclosure, 30mm-32.5mm from the edge. be careful to center the hole along the short side so that the retaining lug of the toggle switch can catch in the center slot of the enclosure.  
cut 3 pieces of wire @ 36mm. measure how much casing to strip off of pins 2,3,4. i used 4mm as a starting point.  
cut 2 pieces of wire @ 30mm. test the length of this wire from pin 1 to the switch, and the switch to the opposite pin 1. 
cut 1 piece of 50 wire @ 55mm. measure from ground lug to ground lug. remove excess.  
ensure the switch is mounted in the enclosure with the ON position facing the XLR-4 F side.  
solder connection from pin 1 to the swich, and then the switch to the opposite pin 1.
solder 4 wires to pins, and 1 wire to ground lug, on one side only. 
after visual inspection and continuity test, solder to the opposite connector.  
perform function test on com rig with a listening partner.  
secure both sides of the enclosure together, clamp with vise, and perform final installation of screws.  
