[![Build Status](https://travis-ci.org/frank-y-liu/SPRNT.svg?branch=master)](https://travis-ci.org/frank-y-liu/SPRNT)
[![License](https://img.shields.io/badge/License-EPL%201.0-red.svg)](https://opensource.org/licenses/EPL-1.0)

SPRNT 

=====

SPRNT is a river dynamics simulation software package. Technically it is a fully dynamic
Saint Venant Equation solver. Quite a few nice techniques are developed to make SPRNT not 
only fast but also capable of handling large networks. The code is mainly written by
Dr. Frank Liu at IBM Research, as the result of academic collaborations with Professor Ben
Hodges in the Civil Engineering Department of University of Texas at Austin. It is released
under Eclipse Public License. IBM owns the copyright.

Content: 
    src/        directory contains the core SPRNT routine source code
    spt/        contains the code of a front-end to run SPRNT as command-line 
    examples/   contains several netlist examples
    demo/       contains an example on how to run SPRNT through API
    doc/        contains a user's manual on the syntax of the netlist
    ThirdParty/ contains modules to build solver library as dynamic-linked library  

See INSTALL on how to build and install the software

For bugs/questions/comments/critiques, please send email through GitHub.

The following two references contain the descriptions of the theoretic work behind
SPRNT:

1. Liu, Frank, and Ben R. Hodges. "Applying microprocessor analysis methods to river
network modelling."  Environmental Modelling & Software 52 (2014): 234-252.

2. Hodges, Ben R., and Frank Liu. "Rivers and Electric Networks: Crossing Disciplines in
Modeling and Simulation" Foundations and Trends in Electronic Design Automation 8.1
(2014): 1-116.

