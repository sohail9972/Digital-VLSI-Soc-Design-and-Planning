# Digital-VLSI-Soc-Design-and-Planning

This Repo will Cover the Entire Action Items of the Digital VLSI Soc Design and Planning As Part of the **"NASSCOM-VSD SoC Design Program"** 



 ## CONTENTS
 - [DAY-1: Inception of Open-source EDA, OpenLANE and Sky130 PDK](https://github.com/sohail9972/Digital-VLSI-Soc-Design-and-Planning)
 - [DAY-2: Floor Planning and Introduction to Library Cells](https://github.com/sohail9972/Digital-VLSI-Soc-Design-and-Planning)
 - [DAY-3: Design library cell using Magic Layout and ngSpice Characterization](https://github.com/sohail9972/Digital-VLSI-Soc-Design-and-Planning)
 - [DAY-4: Pre-Layout timming analysis and importance of good clock tree](https://github.com/sohail9972/Digital-VLSI-Soc-Design-and-Planning)
 - [DAY-5: Final steps for RTL2GDS using tritonRoute and OpenSTA](https://github.com/sohail9972/Digital-VLSI-Soc-Design-and-Planning) 
 


1.   DAY-1: Inception of Open-source EDA, OpenLANE and Sky130 PDK
       - Chapter 1: Talking to Computers
         - Introduction to QFN-48
         - Introduction to RISC-V
         - Software application and Hardware
       
       - Chapter 2: Soc design and OpenLane
         - Introduction to components of Open Source ASIC design
         - Simplified RTL2GDS flow
         - Introduction to OpenLANE and strive chipsets
         - Detailed ASIC Flow
     
       - Chapter 3: Open-Source EDA Tools
         - OpenLANE Directory structure
         - Design Prepartion Step
         - File Review post design prep and run synthesis
         - OpenLANE Project Git Links
         - Characterize synthesis results
 
 2.  DAY-2: Floor Planning and Introduction to Library Cells
       - Chapter 1: Chip Floor Planning Considerations
         - Utlization Factor and Aspect Ratio 
         - Concept of Pre-placed Cells
         - De-coupling Capacitors
         - Power Planning
         - Pin Placement and Logical Cell Placement blockage
         - Steps to run floorplan using OpneLANE
         - Review floorplan files and steps to view floorplan
         - Review floorplan layout in Magic
       
       - Chapter 2: Library Binding and Placement
         - Netlist binding and initial place design
         - Optimized Placement using estimated wire-length and Capacitance
         - Final placement Optimization
         - Need for libraries and Characterization
         - Congestion awre placement using RePlAce
     
       - Chapter 3: Cell design and Characteriztion Flows
         - Input for cell design flow
         - Circuit design step
         - Layout design step
         - Typical Charcterization Flow
       
       - Chapter 4: General timing Characterization paramets
         - Timming threshold definitions
         - Propagation delay and transition time


3.  DAY-3: Design library cell using Magic Layout and ngspice Characterization
       - Chapter 1: CMOS Inverter ngspice simulations
         - IO Placer revision
         - SPICE deck creation for CMOS Inverter
         - SPICE simulation lab for CMOS Inverter
         - Switching Threshold Vm
         - Static and Dynamic simulation of CMOS Inverter
         - Lab Steps to git clone vsdstdcelldesign
       
       - Chapter 2: Inception of Layout and CMOS fabrication process
         - Create Active regions
         - Formation of N-well and P-well
         - Formation of Gate Terminal
         - Lightly doped Drain formation
         - Source Drain Formation
         - Local interconnect Formation
         - High Level Metal Formation
         - SKy130 basic layers layout and LEFusing Inverter
         - Lab steps to create std cell layout andextract spice netlist
     
       - Chapter 3: Sky130 Tech file
         - Final SPICE deck using Sky130 tech
         - Characterization Inverter using Sky130 model files
         - Lab introduction to Magic tool options and DRC rules
         - Lab introduction to sky130 pdk's and download labs
         - Lab introduction to Magic and steps to load Sky130tech-rules
         - Fixing Poly.9 error in Sky130 techfile
         - Implement poly resistor spacing to diff and tap
         - Lab Challenge exercise to describe DRC error as geometrical construct
         - Lab Challenge to find missing or incorrect rules and fix them


4.   DAY-4: Pre-layout timing analysis and importance of good clock tree
       - Chapter 1: Timing modeling using delay tables
         - Lab steps to convert grid info to track info
         - Lab steps to convert magic layout to std cell LEF
         - Introduction to timming libs and steps to std cel LEF
         - Introduction to timming libs and steps to include new cell in synthesis
         - Introduction to delay tables
         - Delay table usage Part 1
         - Delay table usage Part 2
         - Lab steps to configure synthesis setttings to fix slack and include vsdinv
       
       - Chapter 2: Timing analysis with ideal clocks using openSTA
         - Setup timing analysis and introduction to Filp flop setup time
         - Introdution to clock jitter and Uncertainity
         - Lab steps to Configure OpenSTA for Post -synth timing Analysis
         - Lab steps to optimize synthesis to reduce setup Violations
         - Lab steps to do basic timing ECO
        
     
       - Chapter 3: Clock tree synthesis TritonCTS and signal integrity
         - Clock Tree routing and buffering using H-Tree algorithm
         - Crosstalk and clock net shielding
         - Lab steps to run CTS using TritonCTS
         - Lab steps to verify CTS runs
       
       - Chapter 4: Timing analysis with real clocks using openSTA
         - Setup timing Analysis using real clocks
         - Hold timing analysis using real clocks
         - lab steps to analyze timing with real clocks using openSTA
         - Executing openSTA with right timing libraries 
         - Lab steps to Observe impact of bigger CTS buffers on setup and hold timing



5.   DAY-5: Final Steps for RTL2GDS using tritonRoute and openSTA
       - Chapter 1: Routing and design rule chekc(DRC)
         - Introduction to Maze Routing Algorithm
         - Lee Algorithm Conclusion
         - Design Rule Check
       
       - Chapter 2: Power Distribution Network and routing
         - Build Poer Distribution Network
         - Power straps to std cell power
         - Global and detail Routing and Configuration Triton Route
         
     
       - Chapter 3: TritonRoute Features
         - Triton F1 - Honors Pre-processed route gides
         - Triton F2 and 3 - Inter - guide connectivity and Infra -& inter LAyer routing
         - SKY_L3 - TritonRoute Method to Handle Connectivity
         - SKY_L4 - Routing Topology Algorithm and final list post-route
        