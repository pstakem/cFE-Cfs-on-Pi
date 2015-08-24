# cFE-Cfs-on-Pi
This relates to NASA's Open source core flight system (cFS) and core flight executive (CFE) on the Raspberry PI.
The cFE is the core flight executive, designed for spacecraft onboard computer use.
The cFS is the core flight software, containing software elements for various functions
under the executive.

The cFS and CFE are open source products from NASA-Goddard Space Flight Center.
This repository contains the instructions on how to connect the Raspberry pi,
running some cFE elements, to the Open Source COSMOS software package.

COSMOS, an open source project of Ball Aerospace, implements a satellite control center
on a desktop or laptop. It is sufficient to operate Cubesats. Our Cubesat engineering
model uses a Raspberry Pi as the central processor, although this would be swapped
out before a flight model is built, due to radiation tolerance issues.

For cubesats and other small satellit projects, you now have control center functionality 
(Cosmos) and a way to have the cubesat send telemetry and receive commands. This can easily
be implemented on a desktop or laptop, and the telemetry is served out on the internet.
It can be received on a desktop, laptop, tablet, or phone.

More details will be posted as we complete out presentation paper.

Using this as a model, please use our Pi-side code as a model for other architectures, such
as Arduino and Zynq. 
