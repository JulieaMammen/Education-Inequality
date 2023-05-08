# Do socioeconomic factors impact educational opportunities in U.S. high school?

This project aims to address the inequality of educational opportunity in U.S. high schools, focusing on student performance on the ACT or SAT exams. We aim to determine whether socioeconomic factors impact the schools' performance.

## Data

This project utilizes two data sets, the EdGap_data.xlsx, the primary data set from 2016 which contains information about average ACT or SAT scores for schools alongisde socioeconomic characteristics of the school district. The second data set contains basic information about each school from the National Center for Education Statistics.

The data set from EdGap is under the file named: 
  EdGap_data.xlsx.

The second data set ccd_Sch_029_1617_w_1a_1121017.csv is too large, but can be acccessed from the dropbox link: 
  https://www.dropbox.com/s/lkl5nvcdmwyoban/ccd_sch_029_1617_w_1a_11212017.csv?dl=0
  
  ## Data Preparation
  
  In order to prepare the data, we will load the data sets and then join the two together to be able to identify missing values. From determining the missing values we then can impute them in order to get a more cohesive data set for us to start analyzing. 
  
  The file that contains the notebook that prepares the data is called: 
    Julie Mammen-DATA 3320 Education Inequality Data Preparation.ipynb
    
  The file that contains the clean data file is called: 
    clean_edgap_school_info.csv
    
    ## Data Analysis
    
    Analysis is performed on the cleaned data set now, primarily using single and multiple linear regressions in order to see the correlation between the socioeconomic factors and average ACT score. We use single input models to see the relationships between individual predictors and average ACT score, and also multiple input models to see the overall model for the data and see the overall relationship to average ACT scores. 
    
    The file that contains the analysis for the data is called: 
      JulieMammen_DATA_3320_Education_Analysis.ipynb

## Authors
 Julie Mammen

## License
 Creative Commons Zero v1.0 Universal
 
 cc0-1.0
