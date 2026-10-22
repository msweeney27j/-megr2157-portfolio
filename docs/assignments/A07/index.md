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
For Design III, I removed the fillets around the upper and lower linkage connections while keeping the remaining fillets from Design II. The first simulation used 25,667 elements, which was refined to 31,526
#### Bracket Mesh Convergence

### MEGR 2157 Students Only (30%) – Finite Element Method: Linkage

#### Linkage Design Requirements

#### Linkage FEA Setup and Assumptions

#### Design I – Original Linkage

#### Design II – Reduced Thickness

#### Design III – Final Thickness Reduction

#### Linkage Mesh Convergence

## Decide

### Bracket Design Comparison

### Linkage Design Comparison – MEGR 2157

### Final Design Selection

## Communicate

### Lessons Learned

### Mistakes and Challenges

### Time Spent

### CAD Files

### AI Use
