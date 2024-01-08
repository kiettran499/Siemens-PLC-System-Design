# Siemens-PLC-System-Design

<p align="center">
  <img width="600" src="https://github.com/kiettran499/Siemens-PLC-System-Design/blob/main/Siemens%20PLC%20System%20for%20Sorting.png">

## Description
 
- Our team is expected to develop a PLC ladder program design proposed for a sorting application in smart manufacturing industry.
- The main goal of the system is to perform an automation task of categorizing black or white plastic and metal workpieces into slots of their respective materials and colours.
- The PLC program controls the interaction between 3 different modules of the system to accomplish the sorting task.
- The system has the following functions:
  - START button to turn on the system.
  - It has two operation modes which can be determined by the Selector Switch
    - Mode 1: the system will perform the sequence ONE time and stop.
    - Mode 2: the system will perform the sequence CONTINUOUSLY the stop conditions are met, or the EMMERGENCY STOP button is pressed.
  - STOP button to stop and return to its initial position at the beginning of the sequence.
  - FAULT button to indicate an error in the system.
  - EMMERGENCY STOP button in the case of an emergency.
 
## Result

<p align="center">
  <img width="500" src="https://github.com/kiettran499/Siemens-PLC-System-Design/blob/main/Test%20cases%20of%20the%20PLC%20system.png">
  
- According to the test cases in the figure above, the system has been successfully analysed, designed, and implemented. That is the system can transfer the workpieces through module A, B, and D, and pieces are allocated into correct slots. Plus, it also satisfies the requirements in mode 1 and mode 2 as well as some special cases like stop, fault, and emergency condition.

- A Demo Video about the design system in operation: https://www.youtube.com/watch?v=uv0dDycq3CU&t=76s
