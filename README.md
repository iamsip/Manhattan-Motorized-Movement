# Manhattan Mobility Model: Motorized Movement
This repository contains a MATLAB function simulating the Manhattan movement model. It's a mobility model primarily for urban areas, replicating the grid-like movement of vehicles in cities.

## Function:
manhattan(position, rxHeight)

This function replicates the movement based on typical urban vehicle speeds with right-angle turns, encapsulating the grid-based city layout.

## Parameters:

position: A structure detailing the current position and other vital mobility metrics.
rxHeight: Receiver node/device height.
Return:

position: An updated structure with new positional information post-movement.
Usage:
Ensure the myPackageConstant function or its package variant is available, providing necessary constants.
Invoke the manhattan function with the appropriate inputs.


