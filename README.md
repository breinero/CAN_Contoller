# Programable CAN Controller Node

This design is a generic Controller Area Network (CAN) controller which can be programmed, and reprogramed for use in a given CAN compliant network. It is designed so that a user can create, or order many, duplicates of this board in batches, and then program each individual board with a specific function within a network. This board has also been designed to be as physically small as possible, so that this same board design can be used through out a given network. This project is purely a hardware design, and does not include an software or firmware to for communicating on a CAN network. 

## Features
1. Compliant with CAN Bus standards
1. The controller node is extensible, where the same unit can be configured and reconfigured to perform different functions
    1. Nodes of this design can collect sensor data, such as oil pressure, fuel level, or vehicle speed, and be able to control components such as turn signals and headlights.
1. Control at least 3 relays independently. E.G. headlights, high beams, turn signal. Or, control one servo 
1. Reprogrammable. The controller code can be updated with bug fixes and improvements
1. Can be added to an existing network with need to reprogram nodes on that network

## Non-Functional Requirements
1. Can be economically ordered via a PCB service
    1. Easy for myself, hobbyests, enthusiasts, or anyone else to acquire in batch sizes between 10 to 100 units
1. Minimal size, so that it can be used in tight spaces or within small component assemblies
1. Suitable for automotive and aircraft applications. 
	1. Components of the design were selected for their quality and reliability
    1. Retrofitting vintage cars
    1. Homebuilt / experimental aircraft

## Non-Goals
1. Easily of assembly. Achieving the smallest footprint and volume takes priority over being able to hand solder this design. Folks have the option to over this part from a PCB assembly service or vendor, if they have difficulty assembling the board. 

# License 
TBD
