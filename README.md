# Pedestrian-avoidance-behavior-dataset (PABD)
## Introduction
This study proposes an experimental framework for extracting typical vivo pedestrian behaviour in motor vehicle conflicts. When the volunteers, i.e., pedestrians, entered near-real immersive virtual reality (VR) traffic scenarios. A well-controlled dangerous traffic scene was generated as a visual stimulus to pedestrians. Real-time kinetic and kinematic signals of the subjects were recorded during the subsequent natural reactions. 
![Figure 1  Overview of the experiment framework and the data flow](https://user-images.githubusercontent.com/63484220/114961249-3dddd600-9e9b-11eb-9237-0878c5baf1c8.jpg)
Figure 1. Overview of the experiment framework and the data flow.
## Download link
All data of PABD can be downloaded from:

https://drive.google.com/file/d/14e4hZGiU3VN5S6NWSIIY5RDDPaQOIYLF/view?usp=sharing

https://cloud.tsinghua.edu.cn/d/010c44008dcb48e18c26/

https://pan.baidu.com/s/1Ypu1G537Iin37UAAUZ5crQ , password:vy54

## Data content
For each experiment case that the file includes three data files.Take “Subj001_TSA” for instance, it represents the data of subject 001 participating in TSA scene:
1)	The “emg” file includes the EMG data in the experiment. Among, the “MVC_test” file includes the EEG data of lower limbs’ muscles in MVC test. The “muscle_MVC.xls” is the calculated EMG data under the state of muscle maximum voluntary contraction (MVC). The “EMG_4550-4700ms.xls” is the time history of EMG signal in the process of avoidance (bandpass:20-500Hz,smoothed with a 25 ms Root Mean Square window), and it corresponds to the kinematics data in the “motion” file. 
2)	The “motion” file is the kinematics data of subjects. You can view the pedestrian kinematics by using the OpenSim software to run the “Full Body Model” and call “EP_0001_PreTest_run2_4550-4700.trc” file (model reference: SimTK: Full Body Model for use in Dynamic Simulations of Human Gait: Downloads). Of course, you can use other human musculoskeletal dynamics software to view the data, such as Anybody, but the name of the corresponding marker point needs to be modified.
3)	The “videos” file is the recording video during the experiment that includes the in-lab and VR environment videos. 

## Reference
Nie, B., Li, Q., Gan, S., Xing, B., Huang, Y., Li, S.E., 2021. Safety envelope of pedestrians upon motor vehicle conflicts identified via active avoidance behaviour. Scientific Reports 11 (1), 3996.

Li, Q., Zhou, Q., Chen, W., Deng, G., Wei, X., Zhang, F., Li, S.E., Nie, B., 2020. In vivo pedestrian behaviour upon motor vehicle conflicts: Experimental framework and initial results. Proceedings of IRCOBI Asia Conference. Beijing, China.

