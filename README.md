### Visual Environmental Perception For Autonomous Road Vehicles


**Discovering drivable surfaces, lane boundaries, objects, and distancing**<br>

#### Mike Knerr
<br>

Autonomous vehicles and robots are becoming more prevalent in complex transportation environments. This includes self-driving cars, small versatile autonomous mobile delivery units, industrial and domestic mobile robots, and other yet to be imagined personal transport vehicles, mobile utilitarian robots, and autonomous terrain based forms.

To reliably and safely traverse their environments, each type of autonomous mobile unit needs to perceive exactly where the navigatable area is. For autonomous highway vehicles this can include roadways, off-road surfaces and other drivable areas in parking lots, garages or structures. An autonomous mobile delivery robot, on the other hand, will have a greater range of possible drivable surfaces than self-driving cars. These units need to perceive sidewalks, curbs, crosswalks, pathways, ramps, flooring, and other interior areas.

Additionally, autonomous vehicles and robots must identify and locate many different types of dynamic and static objects on or immediately adjacent to the current or planned pathways.

What they have in common are several important aspects of environmental perception:

- Where are the actual traversable surfaces and their delimiting boundaries?
- Where and what are the dynamic and static objects in the immediate surroundings?
- How can the object detections be validated with a reliable degree of accuracy?

This [interactive project](visual_environmental_perception_for_autonomous_vehicles.ipynb) explores these aspects of visual perception methods for autonomous road vehicles using semantic segmentation and has two main sections structured as follows:

**Finding and delimiting drivable surfaces**

- Estimate the 3D drivable surface
- Approximate the actual driving lane with delimiting linear boundaries 


**2D Object detection and validation**

- Evaluate the validity of output from 2D object detectors with semantic segmentation
- Calculate minimal distance to impact by determining how far obstacles are from the autonomous vehicle
- Use approximate dimensions of objects to further validate predicted categories from semantic segmentation



</br>

<sub>Project is partially based on and motivated by an assigment for the University Of Toronto course ***Visual Perception For Self-Driving Cars***</sub>

