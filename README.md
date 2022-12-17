# FPGA_Workshop_VSD

FPGA - Fabric, Design and Architecture is a 5-day workshop organised by VLSI System Design (VSD).
Format: Cloud based Virtual Training Workshop

Duration: 14-18 December 2022

Instructor: Dr. Nanditha Rao

# Agenda of the workshop:
Day1: 
[1.1. Introduction to FPGA](# 1.1. Introduction to FPGA)
[1.2. Counter example using Vivado]
[1.3. Counter Verilog explanation and implementation using Vivado]
[1.4. Vivado timing, power, and area measurement for counter]
[1.5. Introduction to VIO]

Day2:
1. Introduction to OpenFPGA and VTR (verilog-to-routing)
2. Introduction to VPR (versatile-place-and-route) using basic Earch fabric
3. Counter example using VPR/VTR openfpga flow

Day3:
1. Introduction to basic RISC-V core – rvmyth
2. Rvmyth – Vivado RTL to synthesis flow
3. Rvmyth – Vivado Synthesis to bitstream

Day4:
1. Introduction to opensource SOFA FPGA fabric
2. Steps to run counter example on SOFA
3. Characterize counter example in terms of area and timing
4. Post-implementation netlist and simulation using SOFA

Day5:
1. Steps to run RISC-V Core - on SOFA
2. Characterize RVmyth in terms of performance and area
3. Steps to generate rvmyth post-implementation netlist
4. Confirm RVmyth on SOFA behavioral simulation using Vivado

# 1.1. Introduction to FPGA
FPGA:
  -Generate customisable hardware
  -Study the effect of area, speed and power of the digital circuits.
  -Logic disgn in FGPA includes: LUTs, Flipflops, configurable CLBs.
  -FPGA vs ASIC Comparison
  |ASIC                                         |FPGA                         |
  |Application Specific Integrated Circuit      |Field Programmable Gate Array|
  |RTL to Layout                                |RTL to bitstream             |
  |Sent to semiconductor foundry for fabrication|Programmed on FPGA boards    |
  |Cannot be reprogrammed                       |Can be reprogrammed          |
  -FPGA Architecture
  
  <img src: "/images_fpga/fpga_architecture.png">

