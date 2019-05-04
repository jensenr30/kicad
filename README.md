# Jensen's KiCAD Projects
I Use KiCad 4 to view/edit my schematics, PCBs, symbols, and footprints.

I Use [gerbv](http://gerbv.geda-project.org/) to view the Gerber files.

I usually generate .pdf files for all my schematics and Gerber files once they are finished, so I can often view my schematics and layouts without having to install KiCad or gerbv.

## library
A collection of KiCad 4 schematic symbols.

## modules
A collection of KiCad 4 PCB footprints.

## XPhone
This is a collection of schematics and PCBs that are used as components of an electric xylophone (technically a glockenspiel).

### Input_Board
This is a module that will do process the input signals. The input signals are transduced by "pickup" coils mounted beneath each xylophone key. The input board:
- Amplifies the signal generated by the xylophone key
- detects the amplitude of the key hit (envelope detector circuit: a "super-diode" and a cap and a bleeder-resistor)
- outputs a pulse when the key is hit (hit detection pulse for a microcontroller to record what is being played by the user)

## SRBOB
This is a shift-register break-out-board. It is a modular, easily expandable shift register board. Each PCB has 4 SRBOB modules that must be cut apart. Each module can be populated with up to 4 74HC595 logic chips. The modules can be "daisy-chained" together to create 
