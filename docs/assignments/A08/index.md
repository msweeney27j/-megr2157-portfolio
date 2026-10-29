# A8 – Gearbox Design

## Objective
The objective of this assignment was to design a gearbox that could be assembled and disassembled while supporting two meshing gears. The assignment required analyzing the input and output shafts for strength, selecting and sizing journal bearings, and designing a two-piece gearbox housing with enough clearance for the gears to rotate. SolidWorks was used to create parametric arts and assemble the gearbox. Engineering drawings were also created for the shafts, bearings, housing halves, and final assembly.

## Analyze

### MEGR 2156 – Gearbox Design

#### Design Requirements
The gearbox was designed using a gear rato of 24:9, with an output torque of 1.25 in-lbf and an output speed of 1100 rpm. The input shaft diameter was given as 0.125 inches and the output shaft diameter was 0.250 inches, with both shafts having a length of 1 inch. The gear train was assumed to be ideal, and the bending moment caused by the radial gear force was considered small enough to ignore during shaft analysis.

The gearbox also needed journal bearings to support both shafts and a two-piece housing that could be assembles and disassembled. The housing needed enough clearance for the gears to rotate without contacting the walls. Critical features were modeled parametrically in SolidWorks, and the final design required engineering drawings with appropriate dimensions and tolerances.

#### Input Shaft Analysis
##### Knowns, Unknowns, and FBD
The input shaft was analyzed to determine if the given diameter of 0.125 inches was sifficent to withstand the applied torque. The known values included the output torque of 1.25 in-lbf, gear ratio of 24:9, and shaft length of 1 inch. The unknowns included the input torque, maximum torsional shear stress, and whether the shaft diameter was sufficient.

A free body diagram was created showing the input torque and the opposing torque transmitted through the pinion gear.The shaft was analyzed under pure torsion because the assignment allowed the bending moment from the radial gear force to be neglected.

##### Algebraic and Numerical Analysis
The input shaft torque was calculated using the given output torque and gear ratio, resulting in 0.46875 in-lbf. The maximum torsional shear stress was then calculated using the equation for a solid circular shaft, resulting in 1,222.3 psi. Using Machinery's Handbook, page 295, Table 2, the allowable shear stress for commercial steel shafting without keyways was determined to be 8,000 psi.

The calculated stress was below the allowable stress, giving a stress ratio of 6.54 relative to the handbook allowable. Based on these results, the original 0.125-inch input shaft diameter was determined to be sufficient, and no changes were needed.

#### Output Shaft Analysis
##### Knowns, Unknowns, and FBD
The output shaft was analyzed to determine if the given diameter of 0.250 inches was sufficient to withstand the output torque of 1.25 in-lbf. The known values included the shaft diameter, shaft length of 1 inch, and output speed of 1100 rpm. The unknowns included the maximum torsional shear stress and whether the shaft diameter was sufficient.

A free body diagram was created showing the torque applied by the output gear and the opposing torque from the load. Like the input shaft, the output shaft was analyzed under pure torsion, with the bending moment from the radial gear force neglected.

##### Algebraic and Numerical Analysis
The output shaft was analyzed using the torsional shear stress equation for a solid circular shaft. Using the output torque of 1.25 in-lbf and shaft diameter of 0.250 inches, the maximum torsional shear stress was calculated to be 407.44 psi. According to Machinery's Handbook, page 295, Table 2, the allowable shear stress for commercial steel shafting without keyways was 8,000 psi.

The calculated stress was below the allowable stress, giving a stress ratio of 19.63 relative to the handbook allowable. Therefore, the original 0.250-inch output shaft diameter was sufficient, and no modifications were needed.

#### Journal Bearing Design
##### Knowns, Unknowns, and FBD
The journal bearings were designed to support the input and output shafts while allowing them to rotate. The known values included the shaft diameters of 0.125 and 0.250 inches, their rotational speeds, and the gear ratio of 24:9. A preliminary bearing length of 0.250 inches was selected for both bearings. The unknowns included the radial gear force, bearing pressure, surface velocity, and PV rating.

A free body diagram was created showing the radial force applied to the bearing and the opposing reaction from the housing. The radial force was determined using the gear force equations provided in the lecture.

##### Algebraic and Numerical Analysis
The journal bearing calculations were completed using the gear force equations from the lecture. The tangential gear force was calculated to be 2.50 lbf, and using a 20-degree pressure angle, the radial force was determined to be 0.910 lbf. This radial force was used to calculate the bearing pressure for both shafts.

Using the selected bearing length of 0.250 inches, the input bearing pressure was calculated to be 29.12 psi, with a surface velocity of 95.99 ft/min and a PV rating of 2,795 psi-ft/min. The output bearing pressure was 14.56 psi, with a surface velocity of 71.99 ft/min and a PV rating of 1,048 psi-ft/min. These values were used to determine whether the selected bearing material would be sufficient.

##### Bearing Material Selection
Porous bronze was selected as the material for both journal bearings using the material table provided in the Gearbox lecture and Machinery's Handbook. The material has a maximum allowable pressure of 4,500 psi, a maximum surface velocity of 1,500 ft/min, and a maximum PV rating of 50,000 psi-ft/min.

The calculated pressure, velocity, and PV values for both bearings were compared to these limits. All three values were below the allowable limits for both bearings. Based on these results, porous bronze was determined to be a suitable material for the gearbox journal bearings.

#### Journal Bearing Thickness
##### Knowns, Unknowns, and Stress FBD
The journal bearing wall thickness was analyzed to determine appropriate dimensions for both bearings. The known values included the shaft diameters of 0.125 and 0.250 inches, the selected bearing lengths of 0.250 inches, and the radial gear force of 0.910 lbf. Porous bronze was selected as the bearing material. The unknowns included the required wall thickness and the outside diameter of each bearing.

A free body diagram was created showing the radial force applied by the shaft and the opposing reaction from the gearbox housing. The bearing wall thickness was evaluated using the dimensional guidelines for copper-base sintered bearings from Machinery's Handbook, page 2445, Table 5b. This provided a preliminary thickness requirement, although it did not directly determine the stresses within the bearing wall.

##### Algebraic and Numerical Analysis
The journal bearing thickness was determined using the dimensional guidelines for copper-base sintered bearings from Machinery's Handbook, page 2445, Table 5b. The handbook specifies a maximum length-to-wall-thickness ratio of 24:1. Using the selected bearing length of 0.250 inches, the minimum wall thickness based on this ratio was calculated to be 0.01042 inches.

The final selected wall thickness was 0.03125 inches for both bearings. This resulted in an outside diameter of 0.1875 inches for the input bearing and 0.3125 inches for the output bearing. Both bearings had a length-to-wall-thickness ratio of 8:1, which satisfied the handbook's 24:1 dimensional limit. These values were used for the bearing selection and SolidWorks models.

#### McMaster-Carr Bearing Selection
Two oil-embedded SAE 841 bronze sleeve bearings were selected from McMaster-Carr for the input and output shafts. The input bearing selected was part 6391K753, with an inside diameter of 0.125 inches, outside diameter of 0.1875 inches, and length of 0.250 inches. The output bearing selected was part 6391K126, with an inside diameter of 0.250 inches, outside diameter of 0.3125 inches, and length of 0.250 inches.

Both bearings have a wall thickness of 0.03125 inches, which satisfies the dimensional guidelines from Machinery's Handbook. These bearings were selected because they fit the shaft dimensions and met the calculated pressure, velocity, and PV requirements.

#### Gearbox Housing Design
The gearbox housing was designed as two separate halves that could be assembled and disassmebled. I decided to use a rounded housing profile that followed the general shape of the two gears instead of a rectangular box. The larger circualr section was designed around the output gear, while the smaller section surrounded the input pinion. The center distance between the two sections was set to 0.6875 inches to match the gear spacing.The housing was designed with an internal cavity to provide clearance around the gears. Holes were added for the journal bearings to support the shafts while allowing them to extend outside the housing. The two housing halves were designed to fit together around the gears, keeping the overall gearbox compact while allowing it to be taken apart.

#### Parametric SolidWorks Modeling
The gearbox components were modeled in SolidWorks using the dimensions determined during the design process. The input and output shafts were created using global variables to control their diameters and lengths, allowing the dimensions to be changed without rebuilding the parts. The gears and journal bearings were downloaded from McMaster-Carr and incorporated into the model.

The two housing halves were modeled using circular profiles centered around the gear locations. Tangent lines connected the circular sections, and the profiles were extruded to create the housing geometry. The internal cavities were created using extruded cuts, with a 0.100-inch wall thickness and holes positioned to support the journal bearings.

#### Gearbox Assembly
The gearbox assembly was completed in SolidWorks using the two shafts, spur gears, journal bearings, and housing halves. The shafts were positioned concentrically inside the gear hubs, and the two gears were aligned using a center distance of 0.6875 inches. The journal bearings were then positioned around the shafts and aligned with the bearing holes in the housing.

During the assembly process, I had to adjust several mates to get the gears and shafts positioned correctly. I also used interference detection to check the gear teeth and adjusted their positions to reduce interference. Once the components were aligned, the housing halves were added to enclose the gears while allowing the shafts to extend outside the housing. The final assembly showed how the components fit together and allowed the gearbox housing to be separated for disassembly.

### MEGR 2157 – Engineering Drawings

#### Input Shaft Drawing
The input shaft drawing was created using third-angle projection with multiview and isometric views. The shaft was dimensioned with a diameter of 0.125 inches and a length of 1 inch. An RC2 sliding fit tolerance was applied to the shaft diameter to allow it to rotate inside the journal bearing.

#### Output Shaft Drawing
The output shaft drawing followed the same format as the input shaft, with a diameter of 0.250 inches and a length of 1 inch. An RC2 sliding fit tolerance was also applied to the diameter. Both shaft drawings included the required general tolerance block and critical dimensions.

#### Input Journal Bearing Drawing
The input journal bearing drawing was created using third-angle projection with multiview and isometric views. The bearing was dimensioned with an inside diameter of 0.125 inches, an outside diameter of 0.1875 inches, and a length of 0.250 inches. The drawing included the general tolerance block and dimensions needed to identify the bearing and its fit with the input shaft.

#### Output Journal Bearing Drawing
The output journal bearing drawing followed the same format as the input bearing. The bearing had an inside diameter of 0.250 inches, an outside diameter of 0.3125 inches, and a length of 0.250 inches. Both bearing drawings included the necessary dimensions and tolerancing information for the selected McMaster-Carr components.

#### Housing Half 1 Drawing
The first housing half drawing was created using third-angle projection with multiview and isometric views. The drawing included dimensions for the rounded housing profile, internal cavity, wall thickness, and bearing holes. The shaft center distance was dimensioned at 0.6875 inches to maintain the correct gear spacing. A section view was also used to show the internal cavity and housing depth.

#### Housing Half 2 Drawing
The second housing half drawing followed the same format as the first housing half. The drawing showed the dimensions of the outer profile, internal cavity, and bearing openings. The two housing halves were designed to fit together around the gears while allowing the shafts to extend outside the housing. The drawings included the required general tolerance block and dimensions needed for assembly.

#### Gearbox Assembly Drawing
The final gearbox assembly drawing was created in SolidWorks using third-angle projection with multiview and isometric views. The drawing showed how the two shafts, gears, journal bearings, and housing halves fit together. A section view was used to show the internal components and how they were positioned inside the housing. The assembly drawing included the overall dimensions, shaft spacing, and the required tolerance block. This drawing helped show how the gearbox was assembled and how the two housing halves could be separated for maintenance or disassembly.

## Decide
Based on the shaft stress calculations, I decided to keep the original input and output shaft diameters of 0.125 and 0.250 inches because both were below the allowable stress from Machinery's Handbook. Porous bronze was selected for the journal bearings because the calculated pressure, velocity, and PV values were all below the material limits. The final bearings were selected from McMaster-Carr using the shaft diameters and required bearing dimensions.

For the housing, I decided to use a rounded two-piece design instead of a rectangular box to keep the gearbox more compact. The housing was designed with a 0.100-inch wall thickness and enough internal clearance for the gears and hubs. The two halves were designed to fit together while allowing the shafts to extend outside the housing. The final design was assembled in SolidWorks and used to create the required engineering drawings.

## Communicate
The gearbox design process was documented through handwritten calculations, free body diagrams, SolidWorks models, and engineering drawings. The calculations were used to verify the shaft diameters and select the journal bearings, while the CAD models showed the development of the housing and final assembly. The seven engineering drawings were created to communicate the dimensions, tolerances, and arrangement of the components.

All calculations, design decisions, drawings, and CAD files were organized in the design portfolio to show the process from the initial requirements to the completed gearbox. The SolidWorks files were also included so the individual parts and final assembly could be downloaded.


### Lessons Learned
Throughout this assignment, I learned more about designing shafts, selecting journal bearings, and creating a gearbox assembly in SolidWorks. One of the biggest challenges was getting the assembly mates correct. I initially had trouble positioning the gears and shafts, and had to remove several mates and restart the assembly process. This helped me better understand how concentric, coincident, and distance mates work together.

Another challenge was getting the gears to align correctly. Even after setting the center distance, the gear teeth were not fully aligned. I used interference detection to identify where the gears overlapped and adjusted their positions to reduce the interference.

The housing design also took some trial and error. I originally considered a rectangular housing but decided a rounded profile would be more compact and better fit the shape of the gears. I also learned how important it was to account for the gear hubs, bearing locations, and shaft clearances when designing the housing. Overall, this assignment helped me better understand how individual components need to be designed together to create a functional assembly.

### Time Spent
Overall I spent 8 hours working on this project with most of the time being spent in SolidWorks.
### AI Usage

### CAD Files and Drawings
