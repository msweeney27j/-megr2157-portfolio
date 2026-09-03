# A2 – Truss Stress Analysis

## Objective
The Objective for this assignment is to design a lightweight planar truss that supports the load and meets the specific geometric and material constraints. This design will use static equilibrium analysis to determine the internal forces in each truss member then stress analysis will be used to determine the required pin and member sizes using the factor of safety. After that, a CAD model will be created to verify the geometry and compare the predicted weight to the calculated weight. 

## Analyze
### Truss Geometry and Design Constraints
The Truss Geometry was designed to support the loads applied at point C and D while still staying within the dimensional constraints. The locations of points A, B, C, and D were determined using the dimensions a = 0.4m and b = 0.3m, and all members were connected to create a simple and stable truss. This Geometry will be used to calculate the internal forces throughout the truss as well as the length of each member. There is an applied load of P=20kn.  The 20KN force is applied upward at joint C and applied downward at joint D. 
### Truss Free-Body Diagram
A Free-body diagram of the entire truss was made to determine the reaction forces at support A and B. Support A is a pin support meaning it has 2 reaction forcers and support B is a rolling pin meaning it has 1 support force.  Using static equilibrium equations, I was able to find out that there was no horizontal force being applied at A Ax= 0.0kN and the vertical support of A is Ay= 6.67KN upward which is opposite of the B support force By= 6.67KN downward. These reaction forces where then used in methods of joints to figure out the forces applied at each joint. 
### Joint Free-Body Diagrams
Individual free body diagrams were then created for joints A, B, C, and D to find internal forces at each point. Member forces were initially assumed to be act in tension, with a positive result meaning tension and a negative result meaning compression. The method of joints and static equilibrium equations were used to solve member forces. Solving all the joint showed that our calculations maintained equalibrium throughout the entire truss.
### Internal Force Analysis 
The internal forces were found using the method of joints after the support forces were found. The resulting forces were AB= 8.89KN in tension, BC= 11.11KN in compression, CD= 26.67KN in tension, DA= 33.33KN in tension, and AC= 37.96 KN in compression. Member AC has the largest internal force and was selected as the critical member for determining minimum required cross-sectional area. First the symbolic relationships between load, geometry and member forces were obtained then numerical values were entered. 
### Member Cross-Section Analysis
The required member cross-sectional area was determined using the greatest internal force. Member AC is our critical member with the largest internal force of 37.96kn in compression. Using a safety factor of 3.5 and AISI 1020 yield strength of 351.57 MPa, the minimum cross-sectional area was calculated to be approximately 378mm^2. A practical cross-section of 20mm x 20mm was selected for the solid works model giving an actual member area of 400mm^2. This area is slightly larger than the calculated minimum and therefore satisfies the constrains while keeping a simple member geometry throughout.
### Truss weight analysis
The approximate weight was calculated using the 400mm^2 cross-sectional area, the total length of all 5 truss members and the density of AISI 1020 steel. The total length of member was found by adding member AB, BC, CD, DA and AC giving a total length of 3454.4mm. I then found the volume of the truss and multiplied it by the density of AISI 1020 steel which is 7900 kg/m^3 to find the mass. Once I found the mass gravity was applied to convert to weight. My total weight was 107N. This hand calculated value will later be compared to the solid works mass-property result.
### Pin Analysis
The connecting pins were designed for single shear using the largest joint reaction load in the truss. Joint C was selected as the critical pin location with a resultant sheer force of 20kn. A safety factor of 4 was applied with the specific hardened tool steel shear yield strength of 170ksi to determine the minimum required pin area and diameter. The minimum area was calculated to be 68.45mm^2 and the diameter 9.32mm. A practical pin of 10mm diameter was chosen, giving an actual area of 78.54mm^2, which exceeds the calculated minimum. Four identical pins were used for this design, each modeled at a length of 20mm.
## Decide
### Truss Geometry Selection
The final truss geometry was selected using a simple trapezoid using points A, B, C, and D with diagonal member AC. This layout was chosen because it satisfies the given constraints with keeping the number of members low which in return is keeping the weight down. Adding member AC stabilizes the four-sided frame by divinding it into 2 triangles without adding unnecessary members.  
### Member Cross-Section Selection
The minimum required cross-sectional area was calculated to be approximately 378mm^2. A 20mm x 20mm square cross section was selected for the final design, giving an actual area of 400mm^2. This size exceeds the calculated minimum, satisfies the required factor of safety, and provides uniform geometry that can be consistently modeled in SolidWorks. 
### Pin Size Selection
The minimum calculated pin diameter was 9.32mm based on the critical single-shear load at joint C. A 10 mm diameter pin was selected to provide a practical size that exceeds the calculated minimum while maintaining the required factor of safety. All four pins were modeled with the same diameter and a length of 20 mm to maintain consistency throughout the design.
## Communicate
### CAD Model
A 3D CAD model of the truss was created in solid works using the final geometry and dimensions from hand calculations. The truss modeled as a single part with all members using the 20mm x 20mm cross sectional area and the 4 pin locations were included at joints A, B, C, and D. The pins were modeled separately as 10mm diameter cylinders with a length of 20mm to match the calculated design.  
### Mass Properties and Weight Comparison
The solid works mass properties tool was used to determine the predicted mass of the completed truss and pins. The truss model has a mass of 11.492kg which corresponds to a weight of 112.7N. Each pin had a mass of approximately 12.35g making the combined pin weight 49.4g for all 4 pins. The hand calcul
### Engineering Lessons Learned 
### Time Spent
### CAD Files
## MEGR 2157 - Failure Mode Analysis
### Truss Member Failure Modes
### Pin Connection Failure Mode
### Sources
### AI Use
