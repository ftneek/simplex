# Simplex
A linear programming solver and game theory library for the HP Prime and Xcas/Giac. It supports various types of linear programming problems including pure and mixed integer problems, binary variables, and unrestricted variables. A readable version of the source code is available in .txt format, while the ready to use versions are available for the HP Prime and Xcas in .hpprgm and .xws formats respectively.

## Installation
This software works on an HP Prime or PC/Mac via the Virtual Calculator or Xcas/Giac. To try this software, you can download the HP Prime Virtual Calculator (VC) and Connectivity Kit (CK) from [https://hpcalcs.com/download/](https://hpcalcs.com/download/). Transfer the .hpprgm files to the HP Prime using the CK. Alternativley, you can download Xcas from [https://xcas.univ-grenoble-alpes.fr/en.html](https://xcas.univ-grenoble-alpes.fr/en.html) and use it to open the simplex.xws file from the File menu.

## Verification
You can ensure everything is working properly by running the **test_simplex()** command, which will solve a number of different linear programming problems and returns a list of all 1's if everything matches the expected results (on the HP Prime, ensure you are in CAS mode). If you see any 0's, it means a test failed for some reason, and warrents investigation as to why. The same goes for changes to source code; if you make any changes, rerun the tests to make sure it didn't cause any issues.
