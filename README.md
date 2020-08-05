# CFD in Julia: 12-Steps to the Navier Stokes Equations

This is a Julian fork of the [12 steps to Navier-Stokes (Python)](https://github.com/barbagroup/CFDPython) by Lorena A. Barba and Gilbert F. Forsyth. 

## Related Forks

This work also derives from similar forks by [Cysor](https://github.com/Cysor/CFDJulia) (up to 06, as of August 1, 2020) and by [Wallace-dyfq](https://github.com/Wallace-dyfq/CFD-Julia-12-steps--o-Navier-Stokes-Equations).

## Feedbacks welcome!

The codes represent early efforts by a novice Julian programmer.  All constructive feedback, bug report, and suggestions would be greatly appreciated.  Please use pull request.

## Speeding it up!

One big item on the to do list is speeding up the loops

See ST_06_Array_Operations for my first attempt at speeding up the loops by implementing @simd and @inbounds macros and setting variable types...  
