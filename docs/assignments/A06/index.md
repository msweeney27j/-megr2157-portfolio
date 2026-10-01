# A6 – Bracket Drawing

## Objective
The objective of this assignment was to create a fully parametric solidworks model and engineering drawing designed in the A5 assignment. The final drawing had be fully dimensioned using the third angle projection with tolerances included for the sliding-fit gaps. The model used the final stress-based dimensions from A5 and are contolled parametrically.

## Analyze

### Design Requirements
The bracket was modeled using the final stress-based dimensions from my A5 assignment. The cad model was set up to be parametric so that dimensions can be controlled through variables. Third angle projection was used to create our fully dimensioned drawing. The sliding fit gaps required tolerances based on the RC3 running/sliding fit values from my machinery's handbook. 

### Parametric Design  
The bracket was modeled in SolidWorks as a single part. The major dimension were linked to global variables so the geometry could automatically update if a value was changed. This made the model easier to modify and kept the cad dimensions consistent with the selected dimensions from A5.
### Global Variables

### Final Bracket Geometry
The final bracket geometry used the stress-based dimensions from the previous assignment.
Feature A used a diameter of 0.848 in.
Feature B used a 0.245 in × 1.25 in cross-section.
Feature C used a thickness of 0.326 in.
Feature D used a 0.173 in × 0.173 in square cross-section.
Feature E used a thickness of 0.326 in.

### Sliding Fit Requirements
The bracket was designed to slide over the rigid T-beam at 3 locations. Each of these gaps required running/sliding fits rather than using the general drawing tolerances. An RC2 running/sliding fit was used so the bracket could move over the T-beam while still maintaing a clearance.

### RC2 Fit Tolerances
The tree sliding fit gaps were given the RC2 running/sliding fit tolerances. These tolerances were found from my machinery's handbook:

0.173 in with +0.0003 / -0.0000
0.245 in with +0.0004 / -0.0000
0.500 in with +0.0004 / -0.0000

These tolerances were added directly to the fit dimension so they wouldn't be interfered by the general tolerance block.

## Decide


### Material Selection
Aluminum 6061-T6 was used for the final bracket model.
This was the same material selected in A5 and kept the CAD model consistent with the material properties used in the original stress and stiffness calculations.

### Final Dimension Selection
The final cad dimensions were carried over from the stress-controlled design previously designed in A5.

## Communicate

### Engineered Tolerances
These tolerances were based on the RC2 running/sliding fit values selected from Machinery’s Handbook. Adding the tolerances directly to the fit dimensions made the required clearances clear on the drawing.

### General Tolerance Block
A general tolerance block was included on the drawing for dimensions that did not have their own engineered tolerance.
The tolerance block used:
- X.X ±  .02
- X.XX ± .01
- X.XXX ± .005
  
## Engineering Lessons Learned
This assignment helped me understand how the dimension from an engineering analysis are used to develop a final Cad model and Drawing. I also learned the importance of using parametric dimensions so that changes to the design can update the model without needing to completely rebuild it. The drawing portion also showed me how engineered tolerances are used differently from general tolerances

## Mistakes Made / Design Changes
One of the main changes I made during this assignment was how I built the upper section. At first, I tired creating each feature together as one sketch. I kept getting an error about an endpoint being undefined. After getting this same issue multiple times I had to change my approach. I then created each piece as its own separate extrusion and then would just sketch onto the different planes the following piece. I found this to be a lot easier than trying to extrude all at once. After completing my model, I had to go back and link the important dimension to global variables after the initial geometry was already made. 

## Time Spent
I spent about 6 hours completing this project
## CAD Files

## AI Use

Input: “How do I add engineered tolerances to dimensions in a SolidWorks drawing?”


Chatgpt: In a SolidWorks drawing, you add an engineered tolerance directly to the dimension through its Dimension PropertyManager.

Click the dimension you want to tolerance in the drawing.
In the left-side Dimension PropertyManager, find the section labeled Tolerance/Precision.
Under Tolerance Type, choose the tolerance format you need:
Symmetric → 25.00 ±0.05
Bilateral → 25.00 +0.05 / -0.02
Limit → shows the maximum and minimum dimensions
FIT / Fit with tolerance → for standard shaft/hole fits such as H7, g6, etc.
Basic → boxes the dimension for GD&T applications
Enter the upper and lower tolerance values.
Set the dimension precision and tolerance precision if needed.
Click elsewhere in the drawing or hit the green check to accept it.
For example, if your nominal hole is Ø8.50 mm and your engineered tolerance is +0.10 / −0.00 mm, select the Ø8.50 dimension → Tolerance/Precision → Bilateral → enter:

Upper: 0.10
Lower: 0.00

It should display approximately:

Ø8.50 +0.10 / −0.00 mm
