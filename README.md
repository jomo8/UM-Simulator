# UM-Emulator
Creates a Universal Machine emulator. Using qcachegrind, I optimized bottlenecks in the code to improve scalability. 

*This code is after fixing the um_execute function*

Things I updated within um.c: 
* Remove the need for UArray_T for registers within um.c. They are instead
  c-arrays now.
