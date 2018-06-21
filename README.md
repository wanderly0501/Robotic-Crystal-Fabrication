# Robotic Crystal Fabrication
## 3D Manipulation of Crystal Growth 

Seminar Work, Princeton University  
Instructor: Ryan Johns  
Collaborator: Ivy Feng, Ji Shi   
Materials: metal salts, water glass.  
Equipment: ABB Robot, water tank, etc  
2015  
Focusing on expanding the material and materializing pro
cess into a broader horizon, we want to construct an intuitive
design-fabrication process which evolves through the inter
play between digital and material processes.
In this project, we design a workflow involving chemical re
action (crystal growth, chemical garden) with its material in
determinacy as well as robotics to model/sculpt 3D physical
form, to explore the possibilities of a consolidated dynamic
design-fabrication approach to achieve augmented materi
ality.
The project is about using certain chemical reaction to fab
ricate physical form. The reaction is commonly known as
chemical garden, an experiment in chemistry normally per
formed by adding solid metal salts such as copper sulfate or
cobalt(II) chloride to an aqueous solution of sodium silicate
(otherwise known as water glass). The salt begins to grow
and generate diverse crystal forms due to the formation of
water-permeable metal silicate membranes and osmotic effects.

The final project shows an experiment to grow crystal along
a helix curve drawn in the Rhino. We drew a 3D irregular spi
ral line in Rhino which consists 7 segments of straight lines
as the path of growth. Each segment corresponds to one
layer of crystal, meaning that crystals grow along this line
and form plates on ends. The robotic-end effector is a simple
platform which can hold the chemical powder and provides a
base plane for the growth. By sending movement command
to the robotic manipulator, the tool held by robot arm moves
through the positions calculated for each step. Metal salt was
fed to the growing crystal in each step.
We calculated the position of the robot arm for each step with
Rhino, and further generated the code for robot with Mussel.
For each step, when the growing crystal reaches the sur
face level, a plate forms at the farther end of this segment,
which is under the dropping point. Then we calculated the
coordinates of the base plane in the coordinate system of
each segment end plate plane. Then we oriented these base
planes from the segment end plane coordinate system to
the plane at the powder dropping point (the position that the
segment end plane should be moved to) and got the position
of base planes for this step in the coordinates system of the
tank. The end effector should move to this position.
The final geometry of the crystal is generally consistent with
the helix drawn in Rhino. But the growth of crystal is not total
ly predictable, so the result is between artificial and natural,
determinate and indeterminate.
