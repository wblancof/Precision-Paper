***After set the environment with the _C++ compile_ and the _Boost library_***
**For more informations about the code equations, check the _JCN_2019_Eqs_Parameters_**
**How to compile**
> **If your platform is Windows**
- Double
1. Open the **_double_** directory and edit the make file *MakefileWin*, with the correct path for the compiler and Boost library. Then, execute the make command.	
2. After this, make sure that your have an HH_BBT2017_doubleP.exe file
3. For simulations with 100% neurons Excitatorys with vInh = 70 mV type the following line code:
> HH_BBT2017_doubleP.exe -pExcN 1.0 -vInh 70
3. For neurons 100% Excitatory and dt = 0.01 it will make four files inside the results directory, are they:
