# A7 – Bracket and Linkage FEA

## Objective
The objective of this assignment was to use Finite Element Analysis (FEA) in SolidWorks to analyze and improve the bracket designed in A5 and A6. Three different designs were tested to determine how geometric changes affected the brackets strength, stiffness, and safety factor results converged within 7%. For the MEGR 2157 requirement, the same process was repeated for the linkage. The final results were compared to determine how the design modifications affected the performance of each component. 

## Analyze

### Design Requirements
The design requirements for A7 were to use the FEA to improve the strength, stiffness, and weight of the bracket from A5 and A6 without changing the assigned material. Three designs were required with geometric modifications made between each design. Each design had to undergo a static stress analysis using proper fixtures, loading and mesh selection. The maximum stress, maximum deflection, safety factor, mass, and number of elements were recorded. Before modifying the geometry, the FEA results had to converge within 7% by refining the mesh, with a maximum of three attempts. For the MEGR 2157 portion, the same process was completed on the linkage. 

### FEA Setup and Assumptions
Both the linkage and bracket were analyzed in SolidWorks using a static simulation with Aluminum 6061-T6 as the assigned material. For the bracket, the back mounting surface was fixed, and a 600 lbf downward force was applied to the lower cylindrical feature based on the feature A FBD. For the linkage, the inside surface of 1.000 in hole was fixed, and a 600 lbf force was applied downward to the inside surface of the 0.848 in hole. The fixed connection was assumed to have no movement, and the material assumed to behave linearly elastically. Each design was tested using an initial mesh and a finer mesh without changing the fixtures or loading conditions. The stress, displacement, and safety factor results were compared to determine if they converged within 7%.

### Bracket FEA – MEGR 2156

#### Design I – Original Bracket
For Design I, I used the original bracket from A6 without making any changes to the geometry. The first simulation used to mesh with 8,355 elements, which was then refined to 13,822 elements. The maximum stress increased from 38.35 mpa to 40.14 mpa, while the maximum displacement increased slightly from 0.01056 to 0.01058 mm. The minimum safety factor decreased from 7.17003 to 6.85086. All three results converged within the required 7% so a third mesh was not needed.

The maximum stress occurred near the connection between the lower cylinder and the vertical arm, while the maximum displacement occurred at the free end of the cylinder. The final safety factor was above the required value of 4, and the bracket has a mass of 0.1601 lb. These results were used as the starting point for comparing the geometric changed made in Design II and III.

#### Design II – Filleted Bracket
For Design II, I added fillets to the edges of the original bracket to see how rounding the corners would affect its strength, stiffness, and weight. The first simulation used 35,799 elements, which was refined to 40,411 elements. The maximum stress increased from 57.65 mpa to 58.08 moa, while the maximum displacement changed from 0.01056 to 0.01057 mm. The minimum safety factor decreased from 4.77049 to 4.73473. All three results converged within 7%, so a third mesh was not needed. 

The maximum stress remained near the lower cylinder to arm connection, and the maximum displacement occurred at the free end of the cylinder. The brackets mass decreased to 0.1592 lb, but the maximum stress increased compared to Design I. The safety factor was still above the required value of 4. These results showed that adding fillets to every edge did not necessarily improve the brackets strength.

#### Design III – Modified Fillets
For Design III, I removed the fillets around the upper and lower linkage connections while keeping the remaining fillets from Design II. The first simulation used 25,667 elements, which was refined to 31,526 elements. The maximum stress decreased from 53.75 mpa to 50.47 mpa, while the maximum deflection increased slightly from 0.01044 mm to 0.01046 mm. The minimum safety factor increased from 5.11658 to 5.44827. All three results converged within 7% so a third mesh was not needed

The maximum stress remained near the lower cylinder to arm connection, while the maximum displacement occurred at the free end of the cylinder. The final mass was 0.1592 lb, which was unchanged from Design II at four decimal places. Compared to Design II, the maximum stress decreased and the safety factor increased without adding measureable weight. However, Design I still had the highest overall safety factor. This showed that modifying the location of the fillets affected the brackets strength without significantly changing its stiffness or mass.

#### Bracket Mesh Convergence
Mesh convergence was performed for all three bracket designs to verify the accuracy of the FEA results. Each design was initially tested with a coarser mesh and then refined by increasing the number of elements. The maximum stress, displacement, and safety factor were compared between the two meshes using the required 7% difference.

For Design I, the stress, displacement, and safety factor differences were 4.46%, 0.19%, and 4.66%. Design II had differences of 0.74%, 0.09%, and 0.75%, while Design III had differences of 6.50%, 0.19%, and 6.09%. All three designs met the convergence requirement after two meshes, so no third mesh was necessary. The results from the finer mesh were used for the final design comparisons. 

### MEGR 2157 Students Only (30%) – Finite Element Method: Linkage

#### Linkage Design Requirements
For the MEGR 2157 portion of A7, the same FEA process was repeated for the linkage designed in A5. The original linkage had a width of 2in, a thickness of 0.250 in, and a center-to-center hole distance of 1.25. The two holes had diameters of 0.848 in and 1.00 in. Aluminum 6061-T6 was used as the material with an applied load of 600 lbf and a required safety factor of 4.

Three linkage designs were tested to determine how reducing thickness affected stress, displacement, safety factor, and mass. Each design was analyzed using a static simulation, and the mesh was refined until results converged within 7%. The goal was to reduce the linkages weight while maintaining the requires strength and stiffness.

#### Linkage FEA Setup and Assumptions
For the linkage FEA, the inside surface of the 1.00 in hole was fixed, while a 600 lbf downward force was applied to the inside surface of the 0.848 in hole. This was used to represent the load transferred through the linkage. Aluminum 6061-T6 was used for all three designs. Each simulation was performed using two mesh sizes to check that the stress, displacement, and safety factor results within 7%. 

#### Design I – Original Linkage
For Design I, I used the original linkage from A5 with a thickness of 0.250 in. The initial mess contained 9,130 elements and was refined to 19,216 elements. The final maximum stress was 26.30 mpa, maximum displacement was 0.009267mm and a minimum safety factor was 10.4549. All three results converged within 7%, and the linkage had a mass of 0.1046 lb. These results were used as the starting point for the next 2 designs. 

#### Design II – Reduced Thickness
For Design II, I reduced the linkage thickness from 0.250in to 0.225in to decrease the weight. The first mesh contained 5,898 elements and was refined to 13,694 elements. The final maximum stress was 29.61 mpa, maximum displacement was 0.01029mm and the minimum safety factor was 9.2874. All three results converged within 7%. The mass decreased t 0.0942 lb, showing that reducing the thickness lowered the weight while maintaining a safety factor above 4. 

#### Design III – Final Thickness Reduction
For Design III, I further reduced the linkage thickness from 0.225inn to 0.200in. The initial mesh contained 6,334 elements and was refined to 14,576 elements. The final maximum stress was 33.14 mpa, maximum displacement was 0.01156mm, and the minimum safety factor was 8.29933. All 3 results converged within 7%. The final mass was 0.0837 lb, which is approximately 20% than Design I. Although stress and displacement increased, the linkage maintained a safety factor above 4.

#### Linkage Mesh Convergence
Mesh convergence was performed for all three linkage designs by comparing the results from the initial and refined meshes. Design I had differences of 0.23% for stress, 0.09% for displacement, and 0.24% for safety factor. Design II had differences of 2.53%, 0.10%, and 2.60%, while Design III had differences of 2.35%, 0.09%, and 2.42%. All three designs converged within the required 7% after two meshes. The results from the finer meshes were used for the final design comparison.

## Decide

### Bracket Design Comparison
The results from all three bracket designs were compared to determine how the geometric modifications affected performance. Design I had the lowest maximum stress at 40.14 MPa and the highest safety factor of 6.85086. Design II reduced the mass from 0.1601 lb to 0.1592 lb, but the maximum stress increased to 58.08 MPa. Design III maintained the same mass as Design II while reducing the maximum stress to 50.47 MPa and increasing the safety factor to 5.44827. All three designs met the required safety factor of 4 and had very similar displacement values. Design I provided the greatest strength, while Design III offered a small weight reduction compared to the original design.

### Linkage Design Comparison – MEGR 2157
The results from all three linkage designs were compared to determine how reducing the thickness affected performance. Design I had the lowest maximum stress of 26.30 MPa and the highest safety factor of 10.4549. Design II reduced the mass to 0.0942 lb, while Design III further reduced it to 0.0837 lb. As the thickness decreased, the maximum stress and displacement increased, while the safety factor decreased. However, all three designs maintained a safety factor above 4 and met the mesh convergence requirement. Design III achieved approximately a 20% weight reduction compared to the original linkage.

### Final Design Selection
Based on the FEA results, I selected Design I for the bracket because it had the lowest maximum stress and highest safety factor. Although Designs II and III reduced the mass slightly the reduction was only 0.0009 lb and came with higher stress. For the linkage, I selected Design III because it reduced the mass by approximately 20% while maintaining a safety factor of 8.29833. The maximum displacement also remained below the allowable limit from A5. These results showed that the best design depends on balancing strength, stiffness, and weight rather than focusing on only one factor. 
## Communicate

### Lessons Learned
One thing I learned from this assignment was how FEA can be used to evaluate geometric changes before selecting a final design. I also learned that increasing the number of mesh elements can change the stress and displacement results, which is why checking convergence is important. The bracket analysis showed that adding fillets does not always reduce stress, depending on their location. For the linkage, reducing the thickness decreased the mass but increased the stress and displacement. This showed me the importance of balancing strength, stiffness, and weight when optimizing a design. 

### Mistakes and Challenges
One challenge I had during this assignment was setting up the correct fixtures and loading conditions in SolidWorks. I initially attempted to use a bearing load on the bracket but had difficulty defining the coordinate system so I switched to a regular force. Another mistake was adding fillets to nearly every edge of the bracket in Design II, which increased the maximum stress instead of reducing it. For Design III, I removed some of those fillets and was able to lower the stress without increasing the mass. I also had to make sure the mesh was refined enough to meet the 7% convergence requirements before making any geometric changes. 

### Time Spent
Overall, I spent 7.5 hours completing this assignment with most of the time spent setting up the FEA simulation, refining meshes and recording the results. 

### CAD Files

### AI Use
Prompt: What geometric changes can be made to a mechanical bracket to increase its strength and reduce stress concentrations?

Chatgpt: Several geometric changes can improve a mechanical bracket’s strength and reduce stress concentrations:

1. Increase fillet radii: Add larger rounded transitions at sharp corners, especially where the horizontal arm meets the vertical mounting plate. This distributes stress more evenly and reduces localized stress concentrations.

2. Add reinforcing ribs or gussets: Place triangular supports between the bracket's horizontal and vertical sections to increase stiffness and reduce bending stresses.

3. Increase thickness in critical areas: Add material near highly stressed regions, particularly around the bracket's base and mounting connections, without unnecessarily increasing the thickness of the entire part.

4. Optimize mounting holes: Increase the distance between holes and nearby edges, maintain sufficient material around each hole, and avoid placing holes in regions of high stress.

5. Improve cross-sectional geometry: Use wider sections, tapered profiles, or reinforced shapes to increase the bracket's moment of inertia and resistance to bending.

6. Eliminate abrupt geometry changes: Replace sudden changes in thickness or width with gradual transitions to prevent localized stress concentrations.

Follow up prompt: Explain why adding fillets could cause higher stress in certain areas and how fillet location and radius affect stress distribution.

Chatgpt: Adding fillets to a mechanical bracket generally reduces stress concentrations by replacing sharp corners with smooth, rounded transitions. However, fillets do not always reduce the maximum stress throughout the bracket because they change how forces travel through the material.

Why fillets can increase stress in certain areas:
- Stress redistribution: A fillet may reduce stress at the original sharp corner while shifting the highest stress to another location, such as the edge of the fillet or a nearby mounting hole.
- Changes in stiffness: Adding a fillet changes the local geometry and stiffness, potentially redirecting more load through adjacent regions.
- Reduced cross-sectional area: If a fillet removes material from a load-bearing section, it can increase local bending stress.
- Fillet transitions: Stress may become concentrated near the points where the curved fillet meets the straight surfaces, especially if the transition is poorly designed.
How fillet radius and location affect stress:
- Small-radius fillets provide limited stress relief because the change in geometry remains relatively abrupt.
- Larger-radius fillets generally distribute stress more gradually, reducing the stress concentration factor.
- Fillet location is critical. Fillets are usually most effective near highly stressed corners, particularly where the horizontal and vertical sections of a bracket meet.
- Excessively large fillets can sometimes increase stress elsewhere by changing the bracket's stiffness, interfering with nearby features, or reducing material in critical areas.
