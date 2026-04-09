---
title: "SFL Client Outline & Pitch"
layout: project
image: /assets/sfl-sketch.jpeg

fontsize: 11pt
geometry: margin=1in
papersize: letter
pagestyle: empty
mainfont: Times New Roman
header-includes:
  - \usepackage{sectsty}
  - \sectionfont{\fontsize{14}{16}\selectfont}  # H1
  - \subsectionfont{\fontsize{12}{14}\selectfont} # H2
  - \usepackage{setspace}
  - \setstretch{1.15}

---

# Inline Separation of Spotted Lanternflies
**Team:** Di-Vine Intervention **Client(s):** Cornell CALS Extension / E\&J Gallo Winery / National Grape

---
## Table of Contents
[Client Pitch](#client-pitch)
[Functional Prototype](#functional-prototype)

## Client Pitch
## Problem Statement

Mechanical grape harvesters and grape growers working with clients like Cornell CALS Extension, E&J Gallo Winery, and the National Grape Association are trying to remove Spotted Lanternflies (SLF) from grapes during harvest in conveyor systems on mechanical harvesters, but SLF get collected with grapes, but more than 1–2 SLF per 1000g can trigger contamination concerns, leading to rejected loads.Current post-harvest washing or manual sorting removes only up to ~50% of SLF and reduces usable yield, making these methods ineffective at commercial throughput. The challenge is designing an inline solution that removes SLF without bruising grapes, slowing harvest, or requiring major harvester redesign, all while handling a harvest stream of crushed fruit, stems, juice, and debris.


## Impact
Growers and processors lose economic value when contaminated loads are downgraded or discarded. A reliable inline separator would preserve yield, reduce labor-intensive inspection, and allow uninterrupted harvest at commercial speed.
If this problem is successfully addressed, the likelihood of SLF contamination would be reduced, there would be an increase in production, and it would also be less disruptive to the ecosystems since it would be performed post-harvest.


## Proposed direction:


### Primary Concept: SLF Inline Sorter

**What it is:**  
 One potential prototype we have discussed is a conveyor belt that utilizes pneumatic and physical sorting to remove SLF from the grape mass that is collected by a mechanical grape harvester. The sorting system would consist of:
- Motor-driven roller with bristles attached for preliminary sorting
- Compressed air system to expel leftover SLF 
- Vacuum suction system to collect expelled SLF


**How it would be used:**
- Based on an estimated adult spotting lanternfly mass of about 0.2-0.3 grams, an air jet velocity of 5-10m/s would generate enough force to dislodge the insect. 
- Once the grape mass falls into the grape harvester and onto a conveyor belt, compressed air is blown from one side and a vacuum is sucked from the other side to remove any flies that move through.
- There are varying levels of compressed air as the grapes move through the conveyor to get flies that may be adhering to grapes or heavier. 


**Why it’s better than the status quo:**
- More specialized toward SLF than the current MOG (materials other than grapes) systems

**End-of-semester proof-of-concept:**  
Test conveyor belt with an effective sorting system attached to the conveyor

## Key risks / unknowns

- Our solution only mitigates the problem, but doesn’t handle the harmful effects SLF have on the vitality/productivity of grape vines. Could lead to reduced yields from harvests.
- Volumetric flow rate of grapes on the conveyor belt.  If this is too high, it will be very hard to sort bugs underneath large amounts of grapes. Also, a challenge if grapes/bugs get smushed together.
- May not have the right to modify the harvester
---

## Questions for the client

1. Are there any sanitation or cleaning requirements for inline equipment?
   *Decision affected:*
2. What level of grape loss or displacement is acceptable?
   *Decision affected:*
3. Is it easy for current harvesters to be retrofitted, or would a new harvest have to be created? 
   *Decision affected:*
4. What is the maximum upfront cost per harvester that would be acceptable?
   *Decision affected:*


## References
- evokeAG. “Harvest Optimisation Technology to Remove Matter Other than Grape (MOG).” YouTube, 26 July 2021, https://www.youtube.com/watch?v=JEM50O9d-M8. 
- Kurtural, S. Kaan. Mechanical Harvesting – Tools of the Trade. Department of Viticulture and Enology, University of California, Davis, https://wineserver.ucdavis.edu/sites/g/files/dgvnsk2676/files/inline-files/MechanicalHarvest_tools_tradeSKK.pdf. 
- WECO Sorting – “The Science of Optical Sorting,” A Duravant Company. “WECO TomatoTek II Sorter in Slow Motion.” YouTube, 14 Apr. 2022, https://www.youtube.com/watch?v=iSd4RgrFOtg.


## Figure

![Proposed inline pneumatic sorting system](/assets/sfl-sketch.jpeg)

## Functional Prototype
1 Overview
This report documents the design, assembly, and testing of our functional prototype for mechan-
ically removing spotted lanternfly (SLF) models from grape clusters. The prototype includes a
rotating brush mounted on a shaft powered by a drill and a manually simulated conveyor system.

2 Parts List and Specifications
2.1 Shaft
• McMaster Code: 8920K231
• Unit Cost: $9.77
• Length: 1 ft
• Length Tolerance: -0.005” to 0”
• Diameter 1”
• Diameter Tolerance: -0.002” to 0”
• Material: Low-Carbon Steel, Grade 1018
• Shape: Rod and Disc
• Yield Strength: 54,000 psi
• Fabrication: Cold Worked
• Hardness: Rockwell B70
• Heat Treatable: Yes
• Certificate: Material Certificate with Traceable Lot Number
• Specifications Met: ASTM A108
• Straightness Tolerance: Not Rated
• Coefficient of Thermal Expansion: 7.1 × 10−6
• Elongation: 15%
• Material Composition: C 0.13-0.20%, Mn 0.30-0.90%, P 0.04% max, Si 0.15-0.30%, S 0.50%
max, Fe remainder
• Additional Specifications: SDS, RoHS, REACH, DFARS
• Country of Origin: USA
• Fabrication Notes: Machined 1.75 in from one end to 0.48 in diameter to fit inside drill chuck.
2.2 Brush
• McMaster Code: 7442T11
• Unit Cost: $8.95
• Brush Length: 1ft
• Bristle Material: Polyester Plastic
• Backing Material: Stainless Steel
• Bristle Dimensions: 3/16” W × 7/32” H, Overall Diameter: 1”, Bristle Diameter: 0.008”
• Color: White
• Max Temperature: 200°F
• Compliance: FDA 21 CFR 177.1660
2.3 Drill
• Model: Dewalt Drill
• Source: Taylor Design Studio
2.4 Conveyor Simulation Components
• Cardboard Piece
– Simulates conveyor surface
– Source: Taylor Design Studio
• Wooden Boards
– Support frame
– Source: Taylor Design Studio
• Zip Ties
– Secure components
– Source: Taylor Design Studio
• Glue
– Temporary bonding
– Source: Taylor Design Studio
2.5 Assembly Sketches and Photos
<img width="521" height="401" alt="Image" src="https://github.com/user-attachments/assets/8e5080f8-b396-4749-a8a9-727c021c57dd" />
Figure 1: Annotated sketch of prototype. Arrows indicate brush rotation and conveyor motion.
<img width="509" height="387" alt="Image" src="https://github.com/user-attachments/assets/42c1610e-1295-4361-a646-27122b1165e8" />
Figure 2: Photo of assembled prototype showing brush, shaft, and conveyor simulation.

3 Assembly Instructions
3.1 Step 1: Shaft Preparation
1. Cut 1 ft low-carbon steel rod.
2. Machine 1.75 in from one end to 0.48 in diameter using lathe (RPL) to fit the drill chuck.
3. Deburr and clean the shaft.
3.2 Step 2: Brush Mounting
1. Cut the stock strip brush into three equal-length sections.
2. Position the sections so they are evenly spaced along the shaft for uniform bristle coverage.
3. Secure each brush section with zip ties wrapped tightly around the shaft and brush backing.
4. Apply a thin layer of glue between the brush backing and the shaft to prevent axial movement.
5. Inspect alignment to ensure bristles are perpendicular to shaft axis.
3.3 Step 3: Drill Interface
1. Insert machined shaft into drill chuck.
2. Tighten chuck to prevent slippage during testing.
3.4 Step 4: Shaft Mount
1. Prepare a wooden mounting board by drilling a 1-inch diameter hole to accommodate the
shaft.
2. Position the hole so that its center is offset 1-inch from the top edge of the board.
3. Secure this mounting board to a thicker base board using wood glue, ensuring it is perfectly
perpendicular to the base for proper shaft alignment.
4. Allow the glue to fully cure before proceeding with mounting the shaft.
3.5 Step 5: Conveyor Simulation Setup
1. Place cardboard piece underneath the base of the brush.
2. Install a partition on the cardboard to separate grapes from dislodged SLF.
3. Ensure smooth sliding surface for grape clusters.
3.6 Step 6: Collection Trough
1. Place a cardboard box behind the brush to collect SLF.
3.7 Step 7: System Integration
1. Place grape clusters on conveyor surface.
2. Operate drill to rotate brush at target RPM (450–500 RPM).
3. Slide the cardboard manually to simulate conveyor motion.
<img width="506" height="383" alt="Image" src="https://github.com/user-attachments/assets/253256da-f21d-4d7e-b395-f6f11fee8430" />
Figure 3: Visual representation of functional connections.
<img width="503" height="314" alt="Image" src="https://github.com/user-attachments/assets/3a8d6b93-13b7-4781-9d5d-ae5d17b8bd13" />
Figure 4: Annotated parts of the prototype showing brush, shaft, and conveyor components.

4 Design Tests
4.1 Test 1: Brush Rotation Speed
Part Tested: Shaft-mounted brush assembly
Purpose: Determine optimal brush speed to remove SLF models without damaging grape clusters.
Method: The drill was operated at 450, 500, 550, 600, and 650 RPM. At each speed, a cluster
of 20 grape models with attached SLF paper models was passed under the rotating brush. The
number of SLF models removed and any grape displacement or damage was recorded.
Results:
• 450 RPM: 6/7 SLF removed, negligible grape displacement.
• 500 RPM: 3/7 SLF removed, minimal grape movement.
• 550 RPM: 3/7 SLF removed, slight grape displacement.
• 600 RPM: 1/7 SLF removed, moderate grape displacement.
• 650 RPM: 1/7 SLF removed, significant grape displacement; clusters moved off cardboard.
Conclusion: Target rotation speed for optimal SLF removal with minimal grape displacement is
500 RPM. Future iteration will include an adjustable speed drill or motor with RPM control.
4.2 Test 2: Brush Bristle Coverage
Part Tested: Three-section strip brush mounted on shaft
Purpose: Evaluate uniformity of bristle coverage along the shaft to ensure consistent SLF removal.
Method: Paper SLF models were placed along the entire width of grape clusters. Brush rotated
at 500 RPM, and the number of SLF models removed from each section (left, center, right) was
recorded.
Results:
• Left section: 5/7 removed
• Center section: 7/7 removed
• Right section: 4/7 removed
Minor gaps at ends due to spacing between brush sections.
Conclusion: Adjust brush spacing and overlap sections slightly in future iteration to achieve ¿90%
SLF removal across full width.
4.3 Test 3: Conveyor Simulation Stability
Part Tested: Cardboard conveyor simulation
Purpose: Ensure stable grape movement and proper SLF collection.
Method: Cardboard manually slid beneath the rotating brush with 10 grape clusters. Observed
for tipping, sliding, or grapes falling off.
Results:
• 6/10 clusters remained fully on conveyor during all passes.
• 4/10 clusters experienced grapes falling off due to slight flexing and lack of lateral support.
• SLF models removed as expected, but grape displacement occurred where clusters fell off.
Conclusion: The current conveyor design allows some grape loss. In the next prototype, adding
side walls or guides along the conveyor will prevent grapes from falling off and improve stability.
Reinforcing the cardboard with a thicker backing or add light wooden boards on either side would
ensure stability.
4.4 Test 4: SLF Removal Efficiency
Part Tested: Integrated system: brush, shaft, manual conveyor
Purpose: Quantify overall SLF removal efficiency for a single pass.
Method: 20 grape clusters, each with 20 SLF paper models, passed under brush at 500 RPM
while sliding cardboard at 1 in/sec. Counted SLF removed per cluster.
Results:
• Average SLF removal: 72%
• Range: 65%–78% per cluster
• No visible grape damage noted.
Conclusion: System is moderately effective. Increasing bristle density, overlapping brush sections,
and introducing consistent conveyor motion will improve removal to ¿90%.
4.5 Test 5: Assembly Repeatability and Stability
Part Tested: Shaft mounting, brush sections, drill interface, conveyor base
Purpose: Evaluate ease of assembly, alignment, and structural stability for repeated use.
Method: Prototype was assembled and disassembled 5 times by two different team members.
Time to assemble, fit of shaft in drill, brush security, and cardboard stability were recorded.
Results:
• Average assembly time: 9 minutes
• Shaft fit consistently in drill chuck with no slippage
• Brush sections remained secure; minor shifting of zip ties observed
• Cardboard conveyor stable, minor flexing noted
Conclusion: Adding alignment markings on shaft and brush sections and using tighter zip ties
or small clamps will improve repeatability. Prototype is sufficiently stable for testing, but next
iteration should reinforce conveyor base.
5 Success Criteria
The prototype must efficiently remove SLF models while remaining safe and repeatable for testing.
• SLF Removal Efficiency: At least 90% removal of SLF models after one pass. Measured
by counting removed models. High priority.
• Grape Integrity: No visible damage to grapes; assessed visually. Medium priority.
• Assembly Time: Prototype can be assembled in under 10 minutes by one user following
instructions. Measured using stopwatch. Medium priority.
• Conveyor Consistency: Grapes move smoothly along simulated conveyor at a consistent
speed of 0.5–1 in/sec. Measured using ruler and stopwatch. Demonstrable on exhibit day.
High priority.
• Brush Speed Control: Brush rotates within 450–500 RPM range; measured with tachome-
ter. High priority.
