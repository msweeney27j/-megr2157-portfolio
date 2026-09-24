# A5 – Bracket and Linkage Design

## Objective
The objective of this assignment was to design a bracket that supports an applied horizontal load. The bracket was divided into five features that were analyzed for both strength and stiffness using strength of materials equations. A factor of safety of 4 and a maximum of 0.005 in per feature were used throughout the design. A linkage was also designed to connect Feature A to a 1-in Shaft, including strength, deflection and fit analyses. 

## Analyze

### Design Requirements
The bracket was designed for an applied load of 600lbf. A factor of safety of 4 was used for all strength calculations, and each feature has a maximum deflection of 0.005in. Each of the 5 bracket features must be analyzed separately for both stress and stiffness to find required dimensions. Direct shear failure was neglected as listed in instructions. The final dimesnions were determined by either stress or stiffness requirements depending on each feature.

### Material Properties
Aluminum 6061-T6 was selected for the bracket and linkage. The material properties used in the calculations were a young's Modulus of 10.0 x 10^6 psi and a yield strength of 40,000 psi. With the required factor of safety of 4 the allowable stress used was 10,000 Psi.

### Feature A Analysis

#### Known and Unknown Values / Free-Body Diagram 
Feature A was modeled as a cantilever beam with a solid circular cross section. The applied load was 600lbf and acted at an assumed moment arm of 1.00in from a fixed connection. The unknown variables were the require diameter. The free body diagram shows the applied load, the support reaction and the reaction moment at the fixed end.

![Feature A known and unknown values and free-body diagram](IMG_2523.jpeg)

#### Stress Analysis
Feature A was analyzed for bending stress using the assumed 1.00 in moment arm. The minimim required diameter from the stress analysis was 0.848in. 

![Feature A stress analysis](IMG_2524.jpeg)

#### Stiffness Analysis
Feature A was analyzed for deflection using the assumed 1.00 in length. The minimum required diameter from the stiffness analysis was 0.534 in.

![Feature A stiffness analysis](IMG_2522.jpeg)

#### Feature A Cross-Section Selection
The stress analysis required a larger diameter of 0.848 in compared to 0.534 in from the stiffness analysis. Therefore, stress governed and the selected diameter for Feature A was 0.848 in.


### Feature B Analysis

#### Known and Unknown Values / Free-Body Diagram
Feature B was modeled as an axially loadedd member carrying 600lbf load trasnferred from freature A. A square cross-section was used with an assumed memeberlength of 0.848.

![Feature B known and unknown values and free-body diagram](IMG_2521.jpeg)

#### Stress Analysis
Feature B was analyzed for axial stress under the 600 lbf load. The minimum required square cross-section from the stress analysis was 0.245 in × 0.245 in.
![Feature B stress analysis](IMG_2520.jpeg)
#### Stiffness Analysis
Feature B was analyzed for axial deflection using an assumed length of 0.848 in. The minimum required square cross-section dimension from the stiffness analysis was 0.101 in × 0.101 in.

![Feature B stiffness analysis](IMG_2519.jpeg)

#### Feature B Cross-Section Selection
The stress analysis required a larger square cross-section of 0.245 in × 0.245 in compared to 0.101 in × 0.101 in from the stiffness analysis. Therefore, stress governed and 0.245 in × 0.245 in was selected for Feature B.



### Feature C Analysis

#### Known and Unknown Values / Free-Body Diagram
Feature C was modeled as a simply supported beam with a 600 lbf concentrated load at its center. The load produced two support reactions of 300 lbf, and a span of 0.9992 in was used for the analysis.

![Feature C known and unknown values and free-body diagram](IMG_2518.jpeg)

#### Stress Analysis
Feature C was analyzed for bending stress as a simply supported beam with a 600 lbf center load. The minimum required thickness from the stress analysis was 0.326 in.

![Feature C stress analysis](IMG_2517.jpeg)

#### Stiffness Analysis
Feature C was modeled as a simply supported beam with a center load and a span of 0.9992 in. The minimum required thickness from the stiffness analysis was 0.152 in.

![Feature C stiffness analysis](IMG_2516.jpeg)

#### Feature C Cross-Section Selection
The stress analysis required a larger thickness of 0.326 in compared to 0.152 in from the stiffness analysis. Therefore, stress governed and a thickness of 0.326 in was selected for Feature C.


### Feature D Analysis

#### Known and Unknown Values / Free-Body Diagram
Feature D was modeled as an axially loaded member carrying one of the 300 lbf support reactions from Feature C. A square cross-section and an assumed member length of 1.499 in were used.

![Feature D known and unknown values and free-body diagram](IMG_2515.jpeg)

#### Stress Analysis
Feature D was analyzed for axial stress under the 300 lbf reaction force from Feature C. The minimum required square cross-section from the stress analysis was 0.173 in × 0.173 in.

![Feature D stress analysis](IMG_2514.jpeg)

#### Stiffness Analysis
Feature D was modeled as an axially loaded member carrying a 300 lbf reaction force. Using an assumed length of 1.499 in, the minimum required square cross-section dimension from the stiffness analysis was 0.095 in × 0.095 in.

![Feature D stiffness analysis](IMG_2513.jpeg)

#### Feature D Cross-Section Selection
The stress analysis required a larger square cross-section of 0.173 in × 0.173 in compared to 0.095 in × 0.095 in from the stiffness analysis. Therefore, stress governed and 0.173 in × 0.173 in was selected for Feature D.


### Feature E Analysis

#### Known and Unknown Values / Free-Body Diagram
Feature E was modeled as a cantilever carrying the 300 lbf load transferred through Feature D. An assumed length of 0.50 in was used to determine the required thickness for both stress and stiffness.

![Feature E known and unknown values and free-body diagram](IMG_2512.jpeg)

#### Stress Analysis
Feature E was analyzed for bending stress using the 300 lbf transferred load and assumed 0.50 in length. The minimum required thickness from the stress analysis was 0.326 in.

![Feature E stress analysis](IMG_2511.jpeg)

#### Stiffness Analysis
Feature E was modeled as a cantilever carrying a 300 lbf load. Using an assumed length of 0.50 in, the minimum required thickness from the stiffness analysis was 0.152 in.

![Feature E stiffness analysis](IMG_2510.jpeg)

#### Feature E Cross-Section Selection
The stress analysis required a larger thickness of 0.326 in compared to 0.152 in from the stiffness analysis. Therefore, stress governed and a thickness of 0.326 in was selected for Feature E.


### Linkage Analysis

#### Known and Unknown Values
The known and unknown values used for the linkage are shown in my notebook calculations below. The linkage carries the same 600 lbf applied load and was designed using Aluminum 6061-T6 with a factor of safety of 4. I selected a thickness of 0.250 in for the linkage.

![Linkage known and unknown values](IMG_2509.jpeg)

#### Strength Analysis
The linkage was analyzed for stress at the smallest cross-sectional area around both holes. The 1.00 in hole produced the smallest area and controlled the design. The minimum calculated width was 1.240 in, so I selected a final width of 1.250 in. The stress with the selected dimensions was 9,600 psi.

![Linkage strength analysis](IMG_2508.jpeg)

![Linkage stress check at both holes](IMG_2507.jpeg)

#### Deflection Analysis
The linkage was also analyzed for axial deflection. I selected a length of 2.00 in between the center of each hole. The calculated deflection was 0.00192 in, which was below the maximum allowable deflection of 0.005 in.

![Linkage deflection analysis](IMG_2506.jpeg)

#### Linkage Geometry Selection
The final linkage geometry used a thickness of 0.250 in, a width of 1.250 in, and a center-to-center hole distance of 2.00 in. The final hole dimensions were determined using the required fits.


### Linkage Fits

#### Feature A Running/Sliding Fit
I selected an RC2 running fit between Feature A and the linkage so that the linkage would be able to move freely around Feature A. From the Machinery’s Handbook table, the linkage hole limits were 0.8480–0.8485 in and the Feature A shaft limits were 0.8473–0.8477 in. This gives a clearance of 0.0003–0.0012 in.

#### 1-Inch Shaft Light Force Fit
I selected an FN1 light force fit between the linkage and the 1.00 in shaft. From the Machinery’s Handbook table, the linkage hole limits were 1.0000–1.0005 in and the shaft limits were 1.0008–1.0012 in. This gives an interference of 0.0003–0.0012 in.

![Selected linkage fits and additional dimensions](IMG_2505.jpeg)

#### Manufacturing Methods
The holes in the linkage would be drilled and then reamed to get the required dimensions. Feature A and the 1.00 in shaft could be turned on a lathe to get the required shaft dimensions. The FN1 connection would then be pressed together to create the interference fit.


## Decide

### Stress vs. Stiffness Comparison
The stress and stiffness results were compared for all five features to determine which dimensions would control the final design. The stress calculations produced the larger required dimensions for all five features, so stress controlled the final bracket geometry. The stress dimensions were used for my final design.

### Final Bracket Geometry
The final bracket geometry was based on the dimensions from the stress analysis since stress controlled all five features. Feature A used a diameter of 0.848 in, Feature B used a 0.245 in × 0.245 in square cross-section, Feature C used a thickness of 0.326 in, Feature D used a 0.173 in × 0.173 in square cross-section, and Feature E used a thickness of 0.326 in.

### Final Linkage Geometry
The final linkage geometry used a thickness of 0.250 in, a width of 1.250 in, and a center-to-center hole distance of 2.00 in. The hole sizes were based on the RC2 running fit for Feature A and the FN1 light force fit for the 1.00 in shaft.


## Communicate

### Stress-Based Multiview Sketch
The stress-based multiview sketch shows the bracket using the dimensions calculated from the stress analysis. The sketch includes the top, front, and right side views with the calculated dimensions for Features A through E.

![Stress-based bracket multiview sketch](IMG_2504.jpeg)

### Stiffness-Based Multiview Sketch
The stifness-based multiview sketch shows the bracket using the dimensions calculated from the stiffnessM analysis. The sketch includes the top, front, and right side views with the calculated dimensions for Features A through E.

![Stiffness-based bracket multiview sketch](IMG_2503.jpeg)


## Engineering Lessons Learned
One thing I learned from this assignment was the importance of checking both stress and stiffness when designing each feature. For my design, stress controlled all five features because the stress calculations required larger dimensions than the stiffness calculations. This showed me that the governing requirement depends on the load, geometry, and material being used.

### Governing Failure Mode
This assignment showed me how an error in one part of the analysis can affect the features that come after it. The dimensions and forces calculated for the earlier features were used to help analyze the later features. This means that an incorrect assumption or calculation early in the design could change multiple dimensions in the final bracket.

### Error Propagation
This assignment showed me that the assumptions made when setting up each feature can have a large effect on the final dimensions. Some dimensions and loading conditions were not directly given, so I had to make assumptions to complete the analysis. Changing these assumed lengths could change the stress or deflection results.

### Sensitivity to Assumptions
This assignment showed me that the assumptions made when setting up each feature can have a large effect on the final dimensions. Some dimensions and loading conditions were not directly given, so I had to make assumptions to complete the analysis. Changing these assumed lengths or the way a feature was modeled would change the stress and deflection results.


## Mistakes Made / Design Changes
One of the main changes I made during this assignment was how I interpreted the geometry of the upper part of the bracket. At first I treated Feature E as a shorter section, but after looking back at the provided figures I realized that Feature E continued through the upper bracket. I changed my sketches to better match the geometry shown in the assignment.

## Time Spent
I spent about 6-7 hours completing this project with the calculations taking a bulk of the time.

## AI Use
Prompt: What is the difference between a running/sliding fit and a force fit, and what manufacturing methods are commonly used to achieve each type of fit? Do not select a fit or make any design decisions for me.

Claude:**Running/sliding fit** — intentional clearance between mating parts so they move relative to each other. The shaft is always smaller than the hole.

**Force fit** — intentional interference; the shaft is larger than the hole so assembly requires pressing, heating, or freezing. Parts resist separation permanently.

---

**Common manufacturing methods to achieve each:**

**Running/sliding fits:**
- Precision turning + grinding to tight dimensional tolerances
- Honing or lapping the bore
- CNC machining with fine finishing passes
- Tolerance controlled via ISO/ANSI fit standards (H7/f7 etc.)

**Force fits:**
- Precision grinding to hold tight positive interference tolerances
- Cylindrical grinding of shafts to exact oversize
- Bore finishing via honing to exact undersize
- Assembly methods: hydraulic press, shrink fitting (heating hub), expansion fitting (cryogenic cooling of shaft)

---

The key manufacturing challenge in both cases is **holding dimensional tolerances consistently** — running fits require controlled clearance, force fits require controlled interference, and both demand surface finish quality that doesn't introduce variability beyond the tolerance band.

Follow up prompt: What machining processes could be used to achieve the tight tolerances required for these fits, and why would reaming or turning be used instead of only drilling? Do not recommend specific dimensions, tolerances, or make design decisions for me.

Claude: **Why drilling alone is insufficient:**

Drilling is a roughing operation — it generates heat, the bit deflects, and the resulting hole has poor cylindricity, surface finish, and dimensional consistency. Positional and size error from drilling alone is too large for either fit type.

---

**Reaming vs. turning for hole finishing:**

**Reaming** follows drilling to bring a hole to precise size and finish. The reamer removes a small, controlled amount of material with multiple flutes, improving:
- Diameter consistency
- Cylindricity
- Surface finish

It cannot correct position errors from drilling — it follows the existing hole path.

**Boring** corrects position errors that reaming cannot, using a single-point tool on a boring bar. More controllable than reaming for location accuracy.

---

**Shaft-side processes:**

**Turning** establishes the rough diameter but has limitations in surface finish and roundness at tight tolerances.

**Cylindrical grinding** follows turning when tighter tolerances and better surface finish are needed — removes very little material with high consistency.

**Lapping** or **honing** used when extreme surface finish and final size control are required, particularly for bore finishing on force fits.

---

**The core reason for multi-step processing:**

Each operation has a capability range. No single process spans from raw stock to finished fit-quality surface in one step economically or accurately — each stage removes less material with higher precision than the last.
