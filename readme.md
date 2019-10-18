
***After set the environment with the _C++ compile_ and the _Boost library_***
**For more informations about the code equations, check the _JCN_2019_Eqs_Parameters_**
**How to compile**
> **If your platform is Windows**
- Double
1. Open the **_double_** directory and compile the make file named *MakefileWin*		
2. After this, make sure that your have an HH_BBT2017_doubleP.exe file
3. For neurons 100% Excitatory and dt = 0.01 it will make four files inside the results directory, are they:
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_double_IappDES,Epis.txt
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_double_IappDES,Iapp.txt
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_double_IappDES.txt
	 - HH_BBT_rk4_dt0100_100_0_vI_70_t8s_double_IappDES_Spikes.m

4. For neurons 80/20% Excitatory/Inhibitory and dt = 0.01 it will make four files inside the results directory, are they:
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_double_IappDES,Epis.txt
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_double_IappDES,Iapp.txt
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_double_IappDES.txt
	 - HH_BBT_rk4_dt0100_100_20_vI_70_t8s_double_IappDES_Spikes.m

5. ***For dt = 0.05, change the command line 33 for 'const double dt = 0.05;' .
The files will be renamed with dt050, for example: _HH_BBT_rk4_dt050_100,0,vI70,t=8s_double_IappDES,Epis_***

- LongDouble
1. Open the **_longDouble_** directory and compile the make file named *MakefileWin*		
2. After this, make sure that your have an HH_BBT2017_LongDouble.exe file
3. For neurons 100% Excitatory and dt = 0.01 it will make four files inside the results directory, are they:
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_LongDouble_IappDES,Epis.txt
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_LongDouble_IappDES,Iapp.txt
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_LongDouble_IappDES.txt
	 - HH_BBT_rk4_dt0100_100_0_vI_70_t8s_LongDouble_IappDES_Spikes.m

4. For neurons 80/20% Excitatory/Inhibitory and dt = 0.01 it will make four files inside the results directory, are they:
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_LongDouble_IappDES,Epis.txt
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_LongDouble_IappDES,Iapp.txt
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_LongDouble_IappDES.txt
	 - HH_BBT_rk4_dt0100_100_20_vI_70_t8s_LongDouble_IappDES_Spikes.m

***For dt = 0.05, change the command line 38 for 'const double dt = 0.05;' .
The files will be renamed with dt050, for example: _HH_BBT_rk4_dt050_100,0,vI70,t=8s_LongDouble_IappDES,Epis_***

- Boost
1. Open the **_boost_** directory and compile the make file named *MakefileWin*		
2. After this, make sure that your have an HH_BBT2017_Boost.exe file
3. For neurons 100% Excitatory and dt = 0.01 it will make four files inside the results directory, are they:
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_doubleBoost_IappDES.txt
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_doubleBoost_IappDES,Epis.txt
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_doubleBoost_IappDES.txt
	 - HH_BBT_rk4_dt0100_100_0_vI_70_t8s_doubleBoost_IappDES_Spikes.m

4. For neurons 80/20% Excitatory/Inhibitory and dt = 0.01 it will make four files inside the results directory, are they:
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_doubleBoost_IappDES.txt
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_doubleBoost_IappDES,Epis.txt
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_doubleBoost_IappDES.txt
	 - HH_BBT_rk4_dt0100_100_20_vI_70_t8s_doubleBoost_IappDES_Spikes.m

5. ***For dt = 0.05, change the command line 41 for 'const double dt = 0.05;' .
The files will be renamed with dt050, for example: _HH_BBT_rk4_dt050_100,0,vI70,t=8s_doubleBoost_IappDES_***

> **If your platform is MacOS Linux**

- Double
1. Open the **_double_** directory and compile the make file named *MakefileMacLinux*		
2. After this, make sure that your have an HH_BBT2017_doubleP file
3. For neurons 100% Excitatory and dt = 0.01 it will make four files inside the results directory, are they:
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_double_IappDES,Epis.txt
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_double_IappDES,Iapp.txt
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_double_IappDES.txt
	 - HH_BBT_rk4_dt0100_100_0_vI_70_t8s_double_IappDES_Spikes.m

4. For neurons 80/20% Excitatory/Inhibitory and dt = 0.01 it will make four files inside the results directory, are they:
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_double_IappDES,Epis.txt
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_double_IappDES,Iapp.txt
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_double_IappDES.txt
	 - HH_BBT_rk4_dt0100_100_20_vI_70_t8s_double_IappDES_Spikes.m

5. ***For dt = 0.05, change the command line 33 for 'const double dt = 0.05;' .
The files will be renamed with dt050, for example: _HH_BBT_rk4_dt050_100,0,vI70,t=8s_double_IappDES,Epis_***

- LongDouble
1. Open the **_longDouble_** directory and compile the make file named *MakefileMacLinux*		
2. After this, make sure that your have an HH_BBT2017_LongDouble file
3. For neurons 100% Excitatory and dt = 0.01 it will make four files inside the results directory, are they:
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_LongDouble_IappDES,Epis.txt
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_LongDouble_IappDES,Iapp.txt
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_LongDouble_IappDES.txt
	 - HH_BBT_rk4_dt0100_100_0_vI_70_t8s_LongDouble_IappDES_Spikes.m

4. For neurons 80/20% Excitatory/Inhibitory and dt = 0.01 it will make four files inside the results directory, are they:
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_LongDouble_IappDES,Epis.txt
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_LongDouble_IappDES,Iapp.txt
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_LongDouble_IappDES.txt
	 - HH_BBT_rk4_dt0100_100_20_vI_70_t8s_LongDouble_IappDES_Spikes.m

5. ***For dt = 0.05, change the command line 38 for 'const double dt = 0.05;' .
The files will be renamed with dt050, for example: _HH_BBT_rk4_dt050_100,0,vI70,t=8s_LongDouble_IappDES,Epis_***

- Boost
1. Open the **_boost_** directory and compile the make file named *MakefileMacLinux*		
2. After this, make sure that your have an HH_BBT2017_Boost file
3. For neurons 100% Excitatory and dt = 0.01 it will make four files inside the results directory, are they:
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_doubleBoost_IappDES.txt
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_doubleBoost_IappDES,Epis.txt
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_doubleBoost_IappDES.txt
	 - HH_BBT_rk4_dt0100_100_0_vI_70_t8s_doubleBoost_IappDES_Spikes.m

4. For neurons 80/20% Excitatory/Inhibitory and dt = 0.01 it will make four files inside the results directory, are they:
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_doubleBoost_IappDES.txt
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_doubleBoost_IappDES,Epis.txt
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_doubleBoost_IappDES.txt
	 - HH_BBT_rk4_dt0100_100_20_vI_70_t8s_doubleBoost_IappDES_Spikes.m

5. ***For dt = 0.05, change the command line 41 for 'const double dt = 0.05;' .
The files will be renamed with dt050, for example: _HH_BBT_rk4_dt050_100,0,vI70,t=8s_doubleBoost_IappDES_***
> **How compile the Figures**

***After generated the archives for each platform and each precision***
- Figure 1
1. Open the Fig1_as.m file from **_figures_** directory on Matlab software
2. Set the variables 'path_to_actual_directory' on the lines 5 (for Windows files), 18 (for MacOs files) and 31(for Linux files) for  each platform 
3. Verify that the names of the files read are the same within the directories
4. Compile the the file
- Figure 2 
1. Open the Fig2_as.m file from **_figures_** directory on Matlab software
2. Set the variables 'path_to_actual_directory' on the lines 5 (for Windows files), 18 (for MacOs files) and 31(for Linux files) for  each platform 
3. Verify that the names of the files read are the same within the directories
4. Compile the the file
- Figure 3 
1. Open the Fig1_as.m file from **_figures_** directory on Matlab software
2. Set the variables 'path_to_actual_directory' on the lines 5 (for Windows files), 18 (for MacOs files) and 31(for Linux files) for  each platform 
3. Verify that the names of the files read are the same within the directories
4. Compile the the file
- Figure 4 
- Figure 5 
