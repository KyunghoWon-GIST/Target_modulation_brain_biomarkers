# **Target Modulation & Brain Biomarkers**
### Kyungho Won, Sunghan Lee, Daeun Gwon, Sooyeon Kim
![alt text](https://github.com/KyunghoWon-GIST/Target_modulation_brain_biomarkers/blob/main/image_readme.png)

### ■ Stimulation Presentation Task
![alt text](https://github.com/KyunghoWon-GIST/Target_modulation_brain_biomarkers/blob/main/Stimulation_presentation_Task/images/image_mlapp.png)
#### It includes MATLAB, C scripts, and MATLAB based GUI application for basic stimulation presentation and feature extraction during motor imagery task

#### - External dependancies
For pre-processing and display scalp topography, MATLAB based EEGLAB (https://sccn.ucsd.edu/eeglab/index.php) and FieldTrip (https://www.fieldtriptoolbox.org/) toolbox are required. 

#### - Structure
```
>> Stimuluation_presentation_Task % 
./OpenViBE_scenario % OpenViBE scenario (*.MXS) files synchrnoized to mlapp. 
./functions
./images
./images_MI % Stimulation images
./matlabox_sync_with_openViBE % MATLAB scripts within OpenViBE onlien signal processing pieline
./Brain_Cognition_Modulation_Task.mlapp
```
#### - Mlapp tabs
```
- CONFIG % hyper parameter settings for motor imagery task and play (run) the task
- TRAIN % train EEG feature using EEG data collected during offline motor imagery task and export classifier weights in *mat format
```

### ■ Extract BioMarker VI Task

#### It includes scripts MATLAB scripts and deep learning models to extract features and classify user intention from visual imagery (VI) task

#### - Structure
```
./EEGNet-maser
./MATLAB
./MultiRocket-main
```

## Acknowledgements
This work was supported by the Republic of Korea's MSIT (Ministry of Science and ICT), under the High-Potential Individuals Global Training Program (No. 2021-0-01537) supervised by the IITP (Institute of Information and Communications Technology Planning & Evaluation).
