# MemPrec_Age_Format_TimeofDay
This repository contains R scripts and data for the manuscript "Age-related differences in episodic memory precision are robust across time of day, chronotype, and testing format"

Overview of Scripts and Data generated from each:

**1. Scripts 01A and 01B**: Processing and cleaning of Raw Data from time of day video and non-video datasets 

-> Cleaned participant data from these scripts is located in the Learning_Recall folders in the respective [video](https://github.com/JuliaMaybury/MemPrec_Age_Format_TimeofDay/tree/6e4d3e0a0464d4ffcd2a027c91af34f58ce8f101/Cleaned_ToD_VideoData/Learning_Recall) and [non-video](https://github.com/JuliaMaybury/MemPrec_Age_Format_TimeofDay/tree/6e4d3e0a0464d4ffcd2a027c91af34f58ce8f101/Cleaned_ToD_NonVideoData/Learning_Recall) formats.

-> Script also creates summary memory file for [video (1A)](https://github.com/JuliaMaybury/MemPrec_Age_Format_TimeofDay/blob/6e4d3e0a0464d4ffcd2a027c91af34f58ce8f101/Cleaned_ToD_VideoData/Summary_Data_Video.csv) and [non-video (1B)](https://github.com/JuliaMaybury/MemPrec_Age_Format_TimeofDay/blob/6e4d3e0a0464d4ffcd2a027c91af34f58ce8f101/Cleaned_ToD_NonVideoData/Summary_Data_NonVideo.csv) formats, used in later analyses. 

**2. Script 01C/D**: Calculates mean absolute error by block and across all trials and identifies outliers for [video (1C)](https://github.com/JuliaMaybury/MemPrec_Age_Format_TimeofDay/tree/6e4d3e0a0464d4ffcd2a027c91af34f58ce8f101/Cleaned_ToD_VideoData/AbsErr_Data_Video) and [non-video (1D)](https://github.com/JuliaMaybury/MemPrec_Age_Format_TimeofDay/tree/6e4d3e0a0464d4ffcd2a027c91af34f58ce8f101/Cleaned_ToD_NonVideoData/AbsErr_Data_NonVideo) experiment formats.

**3. Script 02C:** Combines both experiment formats (video and non-video) demographic data, memory data (mean absolute error / recogntion score), and sleep (PSQI, MEQ) [data](https://github.com/JuliaMaybury/MemPrec_Age_Format_TimeofDay/blob/6e4d3e0a0464d4ffcd2a027c91af34f58ce8f101/ToD_Video_NonVideo_Data/Memory_Sleep_Demo_Vid_NonVid_FinalData.csv) used for analyses
(ANOVA Recognition Memory, Sleep MEQ). See also: [Bayes Factor Analyses Script](https://github.com/JuliaMaybury/MemPrec_Age_Format_TimeofDay/blob/6e4d3e0a0464d4ffcd2a027c91af34f58ce8f101/Scripts/RecAnova_AbsRegresssion_MEQ_Bayes.jasp).

**4. Script 02D:** Creates [trial-by-trial dataframe](https://github.com/JuliaMaybury/MemPrec_Age_Format_TimeofDay/blob/6e4d3e0a0464d4ffcd2a027c91af34f58ce8f101/ToD_Video_NonVideo_Data/NonVideo_Video_TrialData_SleepData_Final.csv) (combined video and non-video) used for Bayesian hierarchical modelling.

**4. Script 03A:** Bayesian Hierarchical Modelling Script. [Uses trial-by-trial data](https://github.com/JuliaMaybury/MemPrec_Age_Format_TimeofDay/blob/6e4d3e0a0464d4ffcd2a027c91af34f58ce8f101/ToD_Video_NonVideo_Data/NonVideo_Video_TrialData_SleepData_Final.csv) created in script 02D.
 
[ HModelResults ](https://github.com/JuliaMaybury/MemPrec_Age_Format_TimeofDay/tree/83f9fdaa57c129bd9b539055f81ca1453d016430/ToD_Video_NonVideo_Data/HModelResults)and [HMPlots](https://github.com/JuliaMaybury/MemPrec_Age_Format_TimeofDay/tree/6e4d3e0a0464d4ffcd2a027c91af34f58ce8f101/ToD_Video_NonVideo_Data/HMPlots): Contains summary of Models 1 and 2 and associated plots

**5. Script 03B:** ROPE (Region of practical equivalence) analysis

**6. Script 03C:** Supplementary Non-Video attention analysis.[ Attention Data found here.](https://github.com/JuliaMaybury/MemPrec_Age_Format_TimeofDay/blob/1ff094e3af34cbc366d85f41c95b15920f61265b/Cleaned_ToD_NonVideoData/Attention/Attention_MEQ_NonVideo.csv)

Note: Directories can be configured at the start of each script based on where the cleaned learning_recall data folders are located.

Final datasets used for analyses (combined video and non-video formats) can be found in: [ToD_Video_NonVideo_Data folder](https://github.com/JuliaMaybury/MemPrec_Age_Format_TimeofDay/tree/1ff094e3af34cbc366d85f41c95b15920f61265b/ToD_Video_NonVideo_Data)

**Memory Task:**

Code and materials used for the [video](https://github.com/JuliaMaybury/MemPrec_Age_Format_TimeofDay/tree/6e4d3e0a0464d4ffcd2a027c91af34f58ce8f101/PrecisionTask_VideoFormat) and [non-video](https://github.com/JuliaMaybury/MemPrec_Age_Format_TimeofDay/tree/c09b796a466750bb4d2727c1ab35840a425b137e/PrecisionTask_NonVideoFormat) precision task. 

