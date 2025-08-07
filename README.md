# Sooner-Rover-Team-Science-Package-Capstone
A Compilation of my experience working on the design of a new science package for the Sooner Rover Team

The Sooner Rover Team is a multi-disciplinary comptetition team from the University of Oklahoma. We compete in the University Rover Challenge, a competition meant to simulate Mars conditions for a rover to navigate, manipulate and study.
The competition is broken up into multiple missions. These are the Extreme Delivery, Equipment Servicing, Science, and Autonomous missions.
Each of these missions has different capability requirements for the rover, so the Sooner Rover Team Designed multiple modules that can be switched out for each mission that attach to the base rover.

![Full_Rover_with_Arm_in_Utah](https://github.com/user-attachments/assets/68ad7121-6c2e-402a-92d4-1172be9c93f0)

This design is actually a new design built just this last year based on a capstone design from Spring 2024. Due to this and changes to rules during the science mission, me and three of my colleagues decided to redesign the life detection module.
This mission involved a few different tasks. The primary task was to collect a soil sample from a depth of 10cm and gather at least 5g. This sample would then have a life detection experiment done on the rover to tell if there is or isn't
life in the sample. A secondary method was also required to ensure there wasn't a false positive. The secondary task was imaging and analyzing the surrounding terrain to theorize what the area may have looked like in the past, mirroring 
investigation into Mars's canals, which seem to have held water at some point.

We worked with our teams science subteam to come up with a set of experiments to perform on the sample. In the end, we decided on the primary detection method to be submerging the sample in a solution of ninhydrin and ethanol. This would
react to any organics in the sample, causing it to turn green, or if it reacts to DNA, it would turn purple. Our secondary method was a set of sensors that would detect conditions conducive to life. These included a temperature and humidity sensor
that would read the enviroment in the soil, as well as a methane sensor that would detect the amount of methane rising from the soil.

With our parameters set, we began concepting our module. We came up with four concepts. Some of the primary features of the different designs were the collection method, and storage method. For collection, designs such as an excavator bucket were considered,
but deemed too expensive for it. We were left with a augur drill surrounded in a sheath that would lift soil up to the point that it would be stored. For storage, it came down to the way to control which container would be being deposited into. Designs included
a linear slide, a carousel, and a belt carrying containers. This resulted in the four concepts shown below, which were evaluated by us and the rover team, which resulted in design 1 being selected.

![IMG_3077](https://github.com/user-attachments/assets/f34281a2-8c99-4cfc-b056-687e274b79a6)

My design task was the collection system. This would involve the drill and auger, as well as the structure to hold the assembly and mount to the rover. I began modeling in solidworks. First came the carriage for the drill and auger. 
Previous designs had used one but had multiple actuating parts which I wanted to reduce to one actuating motion. I designed a carrier plate that would hold the drill and allow it to slide on rails as well as support the sheath surrounding the auger.
This plate would be connected to an actuator mounted on the support structure, seen behind the drill carrier that also held the rails. The upper end of the rails was supported by the support structure, while the lower end would be bolted to the storage
system, which would be mounted under the main chassis. The support structure included the mounting solution to the main chassis based on a previous design. Originally, this design was a hook and pin style mount. However, the structure would be unable to hinge
in the direction needed, so this was forgone for a single pin mount, with the rest of the support coming from the lower end of the rails.

<img width="937" height="718" alt="Drill Assembly" src="https://github.com/user-attachments/assets/6b1e5089-7b4b-4bd1-896b-f6cef78c38c5" />

Before manufacturing the subsystem, I decided to perform some structural analysis on the support structure. My main concerns were significant deflection causing the rails to be bowed and stress concentrations at joints that would be welded.
To my surprise, the stress and deflection were well below any concern. This design likely could have been slimmed down but we were on a fast timeline, and it would suffice, so we proceeded with manufacturing.

A majority of the parts were CNC plasma cut from 1/8" 6061 aluminum. Some parts such as the auger tube and vertical supports were cut from tube or square stock 6061 aluminum. These parts were then welded together where disassembly was not required, and bolted otherwise.
One piece of this that was 3D printed was a bridge designed to transfer the soil from the output of the tube, to a door on the storage subsystem that would open to allow in soil when desired. This went through a few iterations, utilizing 3D printing's rapid
prototyping to test different configurations. These changes ranged from taller walls to prevent soil from overflowing, to a steeper slope to prevent soil from sitting on the ramp.
This resulted in the design seen below.

![PXL_20250228_042317237](https://github.com/user-attachments/assets/6d417e4b-777a-49d3-879b-717fa1d4f580)

As well as on the full rover.

![PXL_20250301_015509526](https://github.com/user-attachments/assets/ad55167a-bb60-4737-b26a-adcd419c15c5)

While this design performed well in testing, collecting large amounts of soil easily, during the mission, the rover had an electrical fault which caused the rover to be non-operational during much of the mission.
