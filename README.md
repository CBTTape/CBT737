# CBT737
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 737 is from Bob Glover and contains a package to be able  *   FILE 737
//*           to clear DASD, in bulk, to low-values after a D/R     *   FILE 737
//*           test.                                                 *   FILE 737
//*                                                                 *   FILE 737
//*           email:  Bob.Glover@fnf.com                            *   FILE 737
//*                                                                 *   FILE 737
//*                       BACKGROUND                                *   FILE 737
//*                                                                 *   FILE 737
//*     This package supports the following DASD types at           *   FILE 737
//*     SUNGARD:                                                    *   FILE 737
//*                                                                 *   FILE 737
//*       3390 Mod-3                                                *   FILE 737
//*       3390 Mod-9                                                *   FILE 737
//*       3390 Mod-L                                                *   FILE 737
//*                                                                 *   FILE 737
//*     A seldom used RACF feature is the "ERASE on SCRATCH".       *   FILE 737
//*     When RACF is set up correctly, it will write lo-vals on     *   FILE 737
//*     every track of its target data set when its scratched.      *   FILE 737
//*     DRCLEAR is a REXX that creates two sets of jobs that        *   FILE 737
//*     affect every UCB in the D/R exercise. These jobs are        *   FILE 737
//*     submitted by the technician after he has cleared off        *   FILE 737
//*     the VTOCS. The first set of jobs create dummy datasets      *   FILE 737
//*     on all the UCBs and the second set does the scratching.     *   FILE 737
//*                                                                 *   FILE 737
//*     In a typical D/R this procedure cleared to lo-vals in       *   FILE 737
//*     approximately 1 hour the following:  121 MOD-3, 121         *   FILE 737
//*     MOD-9, 126 MOD-L                                            *   FILE 737
//*                                                                 *   FILE 737
```
