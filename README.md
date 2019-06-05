# OpenCaseStudies - ocs-opioid-medicare 

This case study is part of the [OpenCaseStudies]() project. This work is licensed under the Creative Commons Attribution-NonCommercial 3.0 ([CC BY-NC 3.0](https://creativecommons.org/licenses/by-nc/3.0/us/)) United States License.

The libraries used in this study are `library(datasets)`, `library(readr)`, 
`library(dplyr)`, `library(ggplot2)`, `library(ggrepel)`, `library(kableExtra)`, 
`library(tidyverse)`, `library(scales)`, `library(choroplethr)`, 
and `library(choroplethrMaps)`. In order to run this code please ensure you have these packages installed.

### Exploring State-level Opioid prescription using Medicare information   

Opioid prescription has become a popular topic because of 
the increasing prescription and concerns about overdose, 
opioid-related deaths, and other opioid-associated side 
effects. Our motivation is to understand the opioid prescription in the States 
using publicly available data. 

### Motivating question

          
1. Among the 50 States and District of Columbia, 
which five States had the highest and lowest number in    
    (a) **Total opioid claims** ,   
    (b) **Opioid prescription rate** 
( = total opioid claims / total claims ) , and    
    (c) **Opioid prescription per 100 enrollments** ?       
        
2. Did the total number of opioid prescriptions change over time?    
       
3. Can you visualize the opioid prescription rate on the U.S map?   

       

### Data

The Centers for Medicare & Medicaid Services (CMS) has 
prepared a public dataset, including information in the part D
covering calendar years 2013 through 2016, to make
our health care system more transparent, and to allow 
citizens to understand the medical expdenditure and 
relevant health issues. 
[Medicare part D dataset](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Downloads/Prescriber_Methods.pdf) 
 To search opioid-relevant CMS data, you can type "opioid" in 
the [CMS website.](https://data.cms.gov/browse?q=opioid). 
Details about the data aquisition was described in this 
project.
 
For learning purpose, links for download the data were provided, 
and the method to find the links were also provided.  

We also use the `library(datasets)` for States information. Details can be found 
in our other tutorial. 

### Data Import  
 

### Data wrangling 



### Data exploration (exploratory analysis)   


### Summary   

California, Florida, and Texas were the top three States with the highest opioid prescription claim counts in Part D in 2016. However, after taking the population of the States into account, they were not the top three States with the highest opioid prescription rates. Instead, Tennessee, Alabama, and Oklahoma had the highest opioid prescription claims per 100 enrollments. In general, the trend the opioid prescription rate was decreasing during 2013 - 2016 across most of the States. However, the data for 
this analysis came from Medicare Part D, and thus opioid presciption information for relatively younger adults was missing in the analysis. Though prescribers' 
information were added in this analysis, we did not show them in this analysis. 
Combining these data with opioid-related policies across States may be more informative. 

### Notes for instructors  
