haptic-tactor-strip
===================

Combination of extender and tactor boards with drill hits between boards to make them breakaway. If you break away simply add in connectors to make them into their individual components. 

When combined with a Haptic Controller its an 8 tactor implementation per strip, with the extender hopefully removing capacitance from the bus. Designed for our Haptic Display project. Presumably you can attach a ton of these in a row. Right now theres a software limit of 16 tactors which will be fixed soon. The next limit is voltage drop over wires. I'm not sure what we're looking at for that yet. Finally the next limit is tactors on at a time. The current amperage limit is 1 amp or about 10 tactors on at a time, but feel free to push it. 

Send gerber directory to your favorite PCB house to get your own boards. Try www.oshpark.com for great quality cheap low quantity US boards with quick turn around time.

Utilize BRD file in Eagle 5 to take a look at the board, make changes, and generate your own gerbers. Sorry, transition to Eagle 6 soon probably.

Utilize BOM file to order parts (Part Numbers included for digikey) to build your own or fix existing.

Panelized with arduino copy paste. Over 6 inches, sadly, so its going to take an upgraded copy of eagle to edit :(

See Haptic Tactor and Haptic Controller repository for programming and usage.
