# MemPrec_Age_Format_TimeofDay
This repository contains R scripts and data for manuscript "Age-related differences in episodic memory precision are robust across time of day, chronotype, and testing format"

Overview of Scripts and Data:

**1. Scripts 01A and 01B**: Processing and cleaning of Raw Data from TOD Video and Non-Video datasets --> Cleaned Participant Data from these scripts is located in the Learning_Recall Folders in the respective format (Cleaned_ToD_VideoData for the video format data) (Cleaned_ToD_NonVideo_Data for the non-video format) 
-> Script also creates Summary_Data.csv for Video (1A) and non-video (1B), used in later analyses

**2. Script 01C/D**: Calculates mean absolute error per block and across all trials and looks for any outliers for video (1C) and non-video (1D) experiment formats --> creates csv files located in AbsErr_Data folders located in ClenedToD (Video/NonVideo) folders

**3. Script 02C:** Combines both experiment formats (video and non-video) demo data, memory score data, and sleep (PSQI, MEQ) data into a single data file located in the ToD_Video_nonVideo_Data Folder (MemoryABS_Rec_Video_nonVideo. csv) that is used for analyses(ANOVA Recognition Memory, Sleep MEQ (See also script RECAnova_AbsRegression_MEQ_bayes.jasp for Bayes factor analyses)).

**4. Script 02D:** Creates trial-by-trial dataframe (combined Video and Non-Video) used for Bayesian Hierarchical Modelling ("NonVideo_Video_TrialData_SleepData_Final.csv" located in ToD_Video_NonVideo_Data folder) 

**4. Script 03A:** Bayesian Hierarchical Modelling Script. Uses trial-by-trial data located in ToD_Video_NonVideo_Data (NonVideo_Video_TrialData_SleepData_Final.csv)
 
[ HModelResults ](https://github.com/JuliaMaybury/MemPrec_Age_Format_TimeofDay/tree/83f9fdaa57c129bd9b539055f81ca1453d016430/ToD_Video_NonVideo_Data/HModelResults)and HMPlots Folder: Contains a summary of Models 1 and 2 and associated plots

**5. Script 03B:** ROPE (Region of practical equivalence) analysis

**6. Script 03C:** Supplementary Non-Video attention analysis

Note: Directories can be configured at the start of each script based on where the cleaned data is located (located in Learning_Recall folder inside the cleaned data folders) 

**Memory Task:**

The precision task used for the video and non-video formats is included in the precision task folders, with a resource folder containing the task stimuli used and a conditions folder containing study/test files. 

