# Thesis_Transformer_model

## Dataset
**Biomedical Informatics Laboratory**  <br/>

The Smart-Insole dataset, includes data from a pair of pressure sensors insoles - 29 Participants <br/>
Moticon SCIENCE pressure sensor Insole has 16 pressure sensors and a 6 – Axis Inertial Measurement Unit (IMU) sensor for acceleration and angular raw data. <br/>

The dataset mainly has 2 groups; 
* Elderly people
* Parkison Patients

# First Case:
Use all data of Elderly (EL)  and Parkinson (PD) patients. 
In the data files Columns 18-20 are left foot acceleration and Cloumns 43-45 are right foot accelerations. <br/>
Initial case is binary classification where input signal is classified into EL or PD. So all EL get a label 0 whereas all PD get a label 1 <br/>


## Folders In Code

el_folder = 'EL': Directory containing Excel files for Elderly participants. <br/>
pd_folder = 'PD': Directory containing Excel files for Parkinson's Disease participants.
