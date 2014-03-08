---
title: About
---

{% include banner.html %}

**Oh shit son!** This page is still under development!
{: .alert .alert-danger}

* Table of Contents
{:toc}

##Introduction to RemoteTech
RemoteTech is a modification for Squad's 'Kerbal Space Program' which overhauls the unmanned space program. It does this by requiring unmanned vessels have a connection to Kerbal Space Center (KSC) to be able to be controlled. This adds a new layer of difficulty that compensates for the lack of live crewmembers.

##First steps
* -

##Overview of mechanics

###Antennas
Using antennas, it is now possible to set up satellite networks to route your control input. There are two classes of antennas: 'Dishes' and 'Omnidirectionals'.

####Dishes
Dishes are antennas that must be instructed what direction to point at. They do not physically point at something; it is as simple as selecting a target from a list. Dishes tend to be used for long range communication and come with a cone of vision (getting smaller as range gets bigger). Anything inside this cone can achieve a stable connection with the dish.

####Omnidirectionals
Omni antennas radiate in every direction equally, and as such do not require you to point them at anything. A consequence is that they are limited to shorter ranges and have higher power consumption.

###Signal Delay
To comply with Kerbal law, RemoteTech is required to delay your control input so that signalling does not exceed the 'speed of light' (pfft, what a silly law). If you are aware of the consequences of breaking the law (or like being a rebel), you are free to turn this off in the settings file.

###Connections
A 'working connection' is defined as a command center being able to send control input to its destination and back. Connections between neighbouring satellites are referred to as 'links'. To have a link between two satellites, it is required that both satellites can transmit a signal to the other independently. For point A to transmit with a dish, the dish would need to be set to target point B and have sufficient available range. Omnis merely need to have the latter. Note that point B also has to pass these criteria. You have a connection when there is a sequence of links between a command center and the destination.

###Science Transmissions
Transmitting science back to KSC now requires you have a working connection back to KSC. Any other source of control will not be valid.

###Signal Processors
Signal Processors are the backbone of any unmanned vessel. All base game Probe Cores function as one and they are required to process your signal data and control the craft. You will only be able to control a signal processor as long as you have a working connection, and by default you will be subject to [signal delay](#signal_delay).

###Command Stations
For those extra long distance missions, it is possible to set up a team of Kerbals to act as a local command center. This Command Station can not process science, a connection to KSC will still be required for that. However, this allows you to work without the signal delay that might otherwise climb up to several minutes. Command Stations require a special probe part and a minimum number of kerbals to operate. Consult your VAB technicians for more information.

##Downloads
* -

##List of parts
* -

##Credits
* The_Duck, for the precursor to this mod.
* JDP, for RemoteTech 1.x.
* -