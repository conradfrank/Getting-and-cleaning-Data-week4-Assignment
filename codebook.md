# Tidy data set description

### The variables in the tidy data
Tidy data contains 180 rows and 68 columns. Each row has averaged variables for each subject and each activity.

### Only all the variables estimated from mean and standard deviation in the tidy set were kept.

* mean(): Mean value
* std(): Standard deviation

### The data were averaged based on subject and activity group.

Subject column is numbered sequentially from 1 to 30.
Activity column has 6 types as listed below.
1. WALKING
2. WALKING_UPSTAIRS
3. WALKING_DOWNSTAIRS
4. SITTING
5. STANDING
6. LAYING

### The tidy data contains 6 rows (averaged based on activity) and 88 columns for activity variables
1. "subject"                                          
2. "activity"                                         
3. "TimeBodyAccelerometerMean()-X"                    
4. "TimeBodyAccelerometerMean()-Y"                    
5. "TimeBodyAccelerometerMean()-Z"                    
6. "TimeBodyAccelerometerSTD()-X"                     
7. "TimeBodyAccelerometerSTD()-Y"                     
8. "TimeBodyAccelerometerSTD()-Z"                     
9. "TimeGravityAccelerometerMean()-X"                 
10. "TimeGravityAccelerometerMean()-Y"                 
11. "TimeGravityAccelerometerMean()-Z"                 
12. "TimeGravityAccelerometerSTD()-X"                  
13. "TimeGravityAccelerometerSTD()-Y"                  
14. "TimeGravityAccelerometerSTD()-Z"                  
15. "TimeBodyAccelerometerJerkMean()-X"                
16. "TimeBodyAccelerometerJerkMean()-Y"                
17. "TimeBodyAccelerometerJerkMean()-Z"                
18. "TimeBodyAccelerometerJerkSTD()-X"                 
19. "TimeBodyAccelerometerJerkSTD()-Y"                 
20. "TimeBodyAccelerometerJerkSTD()-Z"                 
21. "TimeBodyGyroscopeMean()-X"                        
22. "TimeBodyGyroscopeMean()-Y"                        
23. "TimeBodyGyroscopeMean()-Z"                        
24. "TimeBodyGyroscopeSTD()-X"                         
25. "TimeBodyGyroscopeSTD()-Y"                         
26. "TimeBodyGyroscopeSTD()-Z"                         
27. "TimeBodyGyroscopeJerkMean()-X"                    
28. "TimeBodyGyroscopeJerkMean()-Y"                    
29. "TimeBodyGyroscopeJerkMean()-Z"                    
30. "TimeBodyGyroscopeJerkSTD()-X"                     
31. "TimeBodyGyroscopeJerkSTD()-Y"                     
32. "TimeBodyGyroscopeJerkSTD()-Z"                     
33. "TimeBodyAccelerometerMagnitudeMean()"             
34. "TimeBodyAccelerometerMagnitudeSTD()"              
35. "TimeGravityAccelerometerMagnitudeMean()"          
36. "TimeGravityAccelerometerMagnitudeSTD()"           
37. "TimeBodyAccelerometerJerkMagnitudeMean()"         
38. "TimeBodyAccelerometerJerkMagnitudeSTD()"          
39. "TimeBodyGyroscopeMagnitudeMean()"                 
40. "TimeBodyGyroscopeMagnitudeSTD()"                  
41. "TimeBodyGyroscopeJerkMagnitudeMean()"             
42. "TimeBodyGyroscopeJerkMagnitudeSTD()"              
43. "FrequencyBodyAccelerometerMean()-X"               
44. "FrequencyBodyAccelerometerMean()-Y"               
45. "FrequencyBodyAccelerometerMean()-Z"               
46. "FrequencyBodyAccelerometerSTD()-X"                
47. "FrequencyBodyAccelerometerSTD()-Y"                
48. "FrequencyBodyAccelerometerSTD()-Z"                
49. "FrequencyBodyAccelerometerMeanFreq()-X"           
50. "FrequencyBodyAccelerometerMeanFreq()-Y"           
51. "FrequencyBodyAccelerometerMeanFreq()-Z"           
52. "FrequencyBodyAccelerometerJerkMean()-X"           
53. "FrequencyBodyAccelerometerJerkMean()-Y"           
54. "FrequencyBodyAccelerometerJerkMean()-Z"           
55. "FrequencyBodyAccelerometerJerkSTD()-X"            
56. "FrequencyBodyAccelerometerJerkSTD()-Y"            
57. "FrequencyBodyAccelerometerJerkSTD()-Z"            
58. "FrequencyBodyAccelerometerJerkMeanFreq()-X"       
59. "FrequencyBodyAccelerometerJerkMeanFreq()-Y"       
60. "FrequencyBodyAccelerometerJerkMeanFreq()-Z"       
61. "FrequencyBodyGyroscopeMean()-X"                   
62. "FrequencyBodyGyroscopeMean()-Y"                   
63. "FrequencyBodyGyroscopeMean()-Z"                   
64. "FrequencyBodyGyroscopeSTD()-X"                    
65. "FrequencyBodyGyroscopeSTD()-Y"                    
66. "FrequencyBodyGyroscopeSTD()-Z"                    
67. "FrequencyBodyGyroscopeMeanFreq()-X"               
68. "FrequencyBodyGyroscopeMeanFreq()-Y"               
69. "FrequencyBodyGyroscopeMeanFreq()-Z"               
70. "FrequencyBodyAccelerometerMagnitudeMean()"        
71. "FrequencyBodyAccelerometerMagnitudeSTD()"         
72. "FrequencyBodyAccelerometerMagnitudeMeanFreq()"    
73. "FrequencyBodyAccelerometerJerkMagnitudeMean()"    
74. "FrequencyBodyAccelerometerJerkMagnitudeSTD()"     
75. "FrequencyBodyAccelerometerJerkMagnitudeMeanFreq()"
76. "FrequencyBodyGyroscopeMagnitudeMean()"            
77. "FrequencyBodyGyroscopeMagnitudeSTD()"             
78. "FrequencyBodyGyroscopeMagnitudeMeanFreq()"        
79. "FrequencyBodyGyroscopeJerkMagnitudeMean()"        
80. "FrequencyBodyGyroscopeJerkMagnitudeSTD()"         
81. "FrequencyBodyGyroscopeJerkMagnitudeMeanFreq()"    
82. "Angle(TimeBodyAccelerometerMean,Gravity)"         
83. "Angle(TimeBodyAccelerometerJerkMean),GravityMean)"
84. "Angle(TimeBodyGyroscopeMean,GravityMean)"         
85. "Angle(TimeBodyGyroscopeJerkMean,GravityMean)"     
86. "Angle(X,GravityMean)"                             
87. "Angle(Y,GravityMean)"                             
88. "Angle(Z,GravityMean)"

### variable units
Activity variable is factor type.
Subject variable is factor type.
All the other variables are numeric type.
