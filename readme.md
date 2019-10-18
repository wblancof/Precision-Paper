
***After set the environment with the _C++ compile_ and the _Boost library_***

**How to compile**
> If your platform is Windonws
- Double
1. Open the Double directory and compile the make file named *MakefileWin*		
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

***For dt = 0.05, change the comand line 33 for 'const double dt = 0.05;' .
The files will be renamed with dt050, for example: _HH_BBT_rk4_dt050_100,0,vI70,t=8s_double_IappDES,Epis.txt_***

- LongDouble
1. Open the Long Double directory and compile the make file named *MakefileWin*		
2. After this, make sure that your have an HH_BBT2017_LongDouble.exe file
3. For neurons 100% Excitatory and dt = 0.01 it will make four files inside the results directory, are they:
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_LongDouble_IappDES.txt
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_LongDouble_IappDES,Epis.txt
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_LongDouble_IappDES.txt
	 - HH_BBT_rk4_dt0100_100_0_vI_70_t8s_LongDouble_IappDES_Spikes.m
4. For neurons 80/20% Excitatory/Inhibitory and dt = 0.01 it will make four files inside the results directory, are they:
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_LongDouble_IappDES,Epis.txt
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_LongDouble_IappDES,Iapp.txt
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_LongDouble_IappDES.txt
	 - HH_BBT_rk4_dt0100_100_20_vI_70_t8s_LongDouble_IappDES_Spikes.m

***For dt = 0.05, change the comand line 33 for 'const double dt = 0.05;' .
The files will be renamed with dt050, for example: _HH_BBT_rk4_dt050_100,0,vI70,t=8s_longDouble_IappInter,Epis_***

- Boost
1. Open the Boost directory and compile the make file named *MakefileWin*		
2. After this, make sure that your have an HH_BBT2017_Boost.exe file
3. For neurons 100% Excitatory and dt = 0.01 it will make four files inside the results directory, are they:
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_doubleBoost_IappDES.txt
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_doubleBoost_IappDES,Epis.txt
	 - HH_BBT_rk4_dt0100_100,0,vI70,t=8s_doubleBoost_IappDES.txt
	 - HH_BBT_rk4_dt0100_100_0_vI_70_t8s_doubleBoost_IappDES_Spikes.m
4. For neurons 80/20% Excitatory/Inhibitory and dt = 0.01 it will make four files inside the results directory, are they:
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_doubleBoost_IappDES,Epis.txt
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_doubleBoost_IappDES,Iapp.txt
	 - HH_BBT_rk4_dt0100_100,20,vI70,t=8s_doubleBoost_IappDES.txt
	 - HH_BBT_rk4_dt0100_100_20_vI_70_t8s_doubleBoost_IappDES_Spikes.m

***For dt = 0.05, change the comand line 33 for 'const double dt = 0.05;' .
The files will be renamed with dt050, for example: _HH_BBT_rk4_dt0100_050,20,vI70,t=8s_doubleBoost_IappDES,Epis_***

> If your platform is Linux or MacOS

> How compile the Figures

***After generated the archives for each platform and each precision***
- Figure 1
1. Open the Matlab software and search for the directory preciosion 
- Figure 2 
- Figure 3 
- Figure 4 
- Figure 5 

**For more informations about the code equations, check the _JCN_2019_Eqs_Parameters_**
